## Conexão de Dispositivos USB

A ESP32 suporta USB OTG (USB On-The-Go), o que significa que ela pode funcionar como um dispositivo USB ou host USB, dependendo de como você a configura.

- Como um dispositivo USB, a ESP32 pode ser reconhecida como um dispositivo de armazenamento USB em um computador, permitindo transferir dados entre a ESP32 e o computador.
- Você precisará usar a biblioteca apropriada para configurar a ESP32 como um dispositivo USB e implementar a funcionalidade que deseja, como armazenamento em massa ou emulação de teclado/mouse.

## Conexão de Cartão microSD

A ESP32 possui pinos GPIO que podem ser usados para se conectar a um leitor de cartão microSD.

- Para usar um cartão microSD, você deve incluir uma biblioteca que ofereça suporte a cartões microSD, como a biblioteca SD do Arduino ou outras bibliotecas disponíveis.
- O cartão microSD pode ser usado para armazenar dados, como arquivos, configurações ou registros.

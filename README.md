# IoTSensorAutomation
## O projeto realiza:
- Coleta de dados de sensores
- Acionamento de dispositivos automaticamente
- Comunicação via protocolos como MQTT ou controle local

## Tecnologias Usadas
- Microcontrolador: ESP32 / Arduino
- Linguagem: C++ (firmware) e Python (automação local)
- Comunicação: MQTT (opcional), comunicação serial ou Wi-Fi

## Como Rodar
### 1. Firmware
Carregue o código `firmware/main.ino` no seu ESP32 ou Arduino usando o Arduino IDE.

### 2. Scripts Python
Instale as dependências:
```bash
pip install -r requirements.txt
```
Rode o script desejado:
```bash
python automation/device_controller.py

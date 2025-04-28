| Pino MFRC522 | Pino ESP32  | Função                                  |
|:-------------|:------------|:----------------------------------------|
| SDA (SS)     | GPIO5 (D5)   | Slave Select (SS)                       |
| SCK          | GPIO18       | Serial Clock (SCK)                      |
| MISO         | GPIO19       | Master In Slave Out (MISO)              |
| MOSI         | GPIO23       | Master Out Slave In (MOSI)              |
| IRQ          | Não conectado| Não é necessário para leitura normal   |
| GND          | GND          | Terra (Ground)                         |
| RST          | GPIO22 (D22) | Reset do leitor RFID                   |
| 3.3V         | 3V3          | Alimentação (3.3V)                     |

| Pino Buzzer | Pino ESP32  | Função                                  |
|:------------|:------------|:----------------------------------------|
| Buzzer +    | GPIO12 (D12) | Controle de som                        |
| Buzzer -    | GND          | Terra (Ground)                         |

# Smart Switch ESP32-C3

Placa de interruptor inteligente para automação residencial, com ESP32-C3, fonte AC-DC 12V embutida e acionamento de carga por relé.

## Especificações
- MCU: ESP32-C3-WROOM-02 (Wi-Fi / BLE)
- Fonte: HS-40012 (AC 127V/220V → 12V DC)
- Regulador: AZ1117CH-3.3 (12V → 3.3V)
- Relé: SRD-12VDC-SL-C (10A/250V AC)
- Programação: header UART 4 pinos

## Instalação
O conector de saída (J3: COM / NF / NA) não tem ligação com a entrada AC (J1) na placa. Como normalmente só chega uma fase na caixa do interruptor, feche essa ligação com um jumper externo do terminal de fase do J1 até o pino COM do J3.

## Arquivos
- `fonte_rele_esp-c3.kicad_sch` — esquemático
- `fonte_rele_esp-c3.kicad_pcb` — layout da PCB
- `fonte_rele_esp-c3.kicad_pro` — projeto KiCad
- `GERBER_PROT1/` — gerbers do protótipo

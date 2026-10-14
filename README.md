# Smart Switch PCB (ESP32-C3)

[English](#english) | [Português](#português)

---

<a name="english"></a>
## English

### Description
Compact smart wall switch PCB designed around the ESP32-C3 microcontroller for IoT home automation. It integrates high-voltage AC mains power conversion, relay load switching, logic regulation, and dedicated status monitoring into a single board.

### Key Specifications
* MCU: ESP32-C3-WROOM-02 (Wi-Fi / BLE).
* Power Supply: HS-40012 AC-DC converter module (127V/220V AC to 12V DC).
* Voltage Regulation: AZ1117CH-3.3 LDO for 3.3V logic supply.
* Relay Control: SRD-12VDC-SL-C (10A/250V AC) for switching AC phase.
* Driver & Flyback: N-channel MOSFET driver with 1N4148 flyback diode.
* Status LEDs: Visual indicators for 12V, 3.3V, and relay state.
* Interface: 4-pin UART programming header.
* Safety: Fused AC input with strict AC/DC creepage separation.

---

<a name="português"></a>
## Português

### Descrição
Placa de circuito impresso para interruptor inteligente de parede baseada no microcontrolador ESP32-C3 para automação residencial IoT. Integra conversão de energia AC-DC da rede elétrica, acionamento de carga por relé, regulação lógica e sinalização de status em uma única placa.

### Especificações Técnicas
* Microcontrolador: ESP32-C3-WROOM-02 (Wi-Fi / BLE).
* Fonte de Alimentação: Módulo AC-DC HS-40012 (127V/220V AC para 12V DC).
* Regulação de Tensão: Regulador LDO AZ1117CH-3.3 para alimentação lógica em 3,3V.
* Controle de Carga: Relé SRD-12VDC-SL-C (10A/250V AC) para comutação de fase.
* Driver de Acionamento: MOSFET canal N com diodo de flyback 1N4148.
* Sinalização: LEDs de status para as barras de 12V, 3,3V e estado do relé.
* Programação: Conector UART de 4 pinos.
* Segurança: Proteção de entrada AC por fusível e isolamento físico AC/DC.

---

### File Structure / Estrutura de Arquivos
* `fonte_rele_esp-c3.kicad_sch`: Esquemático elétrico.
* `fonte_rele_esp-c3.kicad_pcb`: Layout da PCB.
* `fonte_rele_esp-c3.kicad_pro`: Arquivo de projeto KiCad.

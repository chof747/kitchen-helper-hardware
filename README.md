# kitchen-helper-hardware
Hardware specs, schematics and pcb design for the kitchen helper device

The KitchenHelper consists of the following features:

- ESP32-S3 MCU 
- TFT Display
- 2 push buttons and a rotary encoder
- 2 cinch slots for NTC temperature sensors
- Buzzer to play sounds
- An addressable led row to show status information and progressy
- Battery and power management 
- Programming Header


## Verification

1. [Done] Programming Header 
2. [Done] Display
3. [Done] Buzzer
4. [Done] Push Buttons

5. [Open] Power and Battery Management
   - protection ICs
   - Voltage regulation
   - charging with charger board

6. [Open] Rotary Encoder schematic 
   - pull-up circuit

7. [Open] Addressable Status Leds 
   - level shifting, 
   - voltage from Battery
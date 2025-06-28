# Keychain-PCB
My first PCB design. Made for solder at hackclub, a challenge that requires the partticipants to build a PCB using limited components.
It is a Keychain based on my PFP(profile picture) on hackclub's slack, @GB114.
## Features
- Two LEDs that light up when SW1 is pressed.
  - Photoresistor with transistor(NPN) to not turn on the LEDs in bright environments.
- DC_Motor(Vibrator) that vibrates when SW2 is pressed.
  - The intensity is adjustable by a potentiometer.
## BOM (Bill of Materials)
| Material        | Footprint                                  | Quantity | Types |
|-----------------|--------------------------------------------|----------|-------|
| Battery holder  | BatteryHolder_Keystone_3034_1x20mm         | 1        |       |
| LEDs            | LED_D5.0mm                                 | 2        |       |
| DC_Motor        | PinHeader_1x02_P2.54mm_Vertical            | 1        |       |
| Transistor(NPN) | TO-92L_HandSolder                          | 1        |       |
| Resistors       | R_Axial_DIN0207_L6.3mm_D2.5mm_P7.62mm_Horizontal | 7        | 6 - 220Ω, 1 - 4.7kΩ |
| R_Photo         | R_LDR_5.1x4.3mm_P3.4mm_Vertical            | 1        |       |
| Potentiometer   | Potentiometer_Vishay_T73YP_Vertical        | 1        |       |
| Push buttons    | SW_PUSH_6mm                                | 2        |       |

## Schematics
![image](https://github.com/user-attachments/assets/5905449a-1560-4ac0-88cb-7f497183a674)
## PCB
![image](https://github.com/user-attachments/assets/84425c31-a805-41c7-a75a-1b550a4908fa)
## 3D view
![image](https://github.com/user-attachments/assets/605ae2ca-486a-48dd-8536-88a17d1e79c8)
![image](https://github.com/user-attachments/assets/2269bff6-4268-4b94-a60b-91b6c842eea6)
![image](https://github.com/user-attachments/assets/7c1af195-3421-4a9b-9665-6b9a495dad48)
![image](https://github.com/user-attachments/assets/957ff615-37dd-48e8-a358-8b32dcfe8115)

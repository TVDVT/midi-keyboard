# midi-keyboard

<img width="847" height="775" alt="image" src="https://github.com/user-attachments/assets/e6968a80-4532-49e1-9fe2-12e2df3570b2" />
<img width="828" height="732" alt="image" src="https://github.com/user-attachments/assets/7cc1ced1-23df-455c-8484-0e241745ed83" />

A piano-like keyboard that can play music.
I used to play the organ and the piano when I was young, so I want to make this a compact 2-in-1, where I can change the sound of each note! Sadly it only contains the white notes, but a lot can be made from these.
This project was made for the third week of Half Life!

# Components (note: add their functions after writing firmware)

It has : 
- Three MX switches
- Two rotary encoders (to adjust the pitch)
- 7 capacitive touch keys (do, re, mi, fa, sol, la, si)
- 3 LED lights (DJ!)

# BOM

| Designator       | Footprint                                                  | Quantity | Value                    | LCSC Part # |
|------------------|------------------------------------------------------------|----------|--------------------------|-------------|
| D1, D2, D3       | LED_SK6812MINI-E_3.2x2.8mm_P1.5mm_ReverseMount            | 3        | SK6812MINI-E             |             |
| J1               | touch                                                      | 1        | Capacitive Touch Buttons |             |
| SW1, SW4, SW6    | SW_Cherry_MX_1.00u_PCB                                     | 3        | SW_Push                  |             |
| SW2, SW3         | RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm            | 2        | RotaryEncoder_Switch_MP  |             |
| U2               | Waveshare ESP32-S3-Zero                                    | 1        | Waveshare ESP32-S3-ZERO  |             |



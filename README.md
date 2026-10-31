# midi-keyboard

<img width="847" height="775" alt="image" src="https://github.com/user-attachments/assets/e6968a80-4532-49e1-9fe2-12e2df3570b2" />
<img width="828" height="732" alt="image" src="https://github.com/user-attachments/assets/7cc1ced1-23df-455c-8484-0e241745ed83" />

A piano-like keyboard that can play music.
I used to play the organ and the piano when I was young, so I want to make this a compact 2-in-1, where I can change the sound of each note! Sadly it only contains the white notes, but a lot can be made from these.

## Features 

- Three MX switches to play some beats
- Two rotary encoders (to adjust the pitch and volume)
- 7 capacitive touch keys (do, re, mi, fa, sol, la, si)
- 3 LED lights (DJ!)

## Schematic
<img width="1320" height="792" alt="image" src="https://github.com/user-attachments/assets/a5fe27b6-fda5-41fb-9e73-1f42ceb208d3" />

## PCB 
<img width="322" height="289" alt="image" src="https://github.com/user-attachments/assets/1426a5ea-ba9d-4f4d-be4b-b88a38dfc62d" />

## Case 
I made a case with a 10 degrees incline using Onshape. It now only has a bottom part, but I plan on making an upper one once I receive the 3d printer (fingers crossed!)
<img width="1164" height="712" alt="image" src="https://github.com/user-attachments/assets/3f069f66-f305-4ce1-b4cb-f6a5fb4eaec8" />


## Firmware 
Right now it's a bit incomplete but it has the pins connected correctly, I borrowed it from the guide and will change it once I have everything.

## BOM

| Designator       | Footprint                                                  | Quantity | Value                    | LCSC Part # |
|------------------|------------------------------------------------------------|----------|--------------------------|-------------|
| D1, D2, D3       | LED_SK6812MINI-E_3.2x2.8mm_P1.5mm_ReverseMount            | 3        | SK6812MINI-E             |             |
| J1               | touch                                                      | 1        | Capacitive Touch Buttons |             |
| SW1, SW4, SW6    | SW_Cherry_MX_1.00u_PCB                                     | 3        | SW_Push                  |             |
| SW2, SW3         | RotaryEncoder_Alps_EC11E-Switch_Vertical_H20mm            | 2        | RotaryEncoder_Switch_MP  |             |
| U2               | Waveshare ESP32-S3-Zero                                    | 1        | Waveshare ESP32-S3-ZERO  |             |



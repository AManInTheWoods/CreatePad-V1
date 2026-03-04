# CreatePad V1
CreatePad (formerly named Hackpad-Japanese-Matrix) is a multipurpose productivity macro pad with a 3x3 switch layout, two rotary encoders, an OLED screen and uses QMK firmware. Under the hood is a Japanese-Duplex-Matrix that made the large amount of inputs (15 in total, including both of the encoders' buttons!) possible. 

<H2>
Features: 
</H2>

  * 11 total switches (3x3 MX + 2 knobs)
  
  * A 0.91 inch OLED display
    
  * 10 customizable profiles with VIA support
  
  * Slanted case design for better (my personal) comfort :) 

<H2>
CAD Model, Made in Fusion360 (the free version):
</H2>

<H3>This is the overall CAD design of CreatePad:</H3> 


<img width="935" height="688" alt="image" src="https://github.com/user-attachments/assets/7928361e-c42e-447f-93c5-bf75ce24b0f0" />
<img width="528" height="710" alt="image" src="https://github.com/user-attachments/assets/aff0aef2-380d-4957-a879-2ad8f4e817ed" />


<H3>This is the separated (top case, PCB, bottom case) bodies:</H3> 


<img width="1094" height="563" alt="image" src="https://github.com/user-attachments/assets/c9ba929d-4d93-4e2e-b380-28ceaf18d0fd" />

<H2>Schematic & PCB (Made in KiCAD):</H2>

<H3>Schematic:</H3>

<img width="1503" height="876" alt="image" src="https://github.com/user-attachments/assets/a1d29457-f735-443d-acdb-bd7be2624da3" />

<H4>"Behold, The Japanese-Duplex-Matrix"</H4>

<H3>PCB:</H3>

<img width="664" height="846" alt="image" src="https://github.com/user-attachments/assets/112c4f57-12a4-4f8b-af41-233ef3e239e6" />

*<H4> I had such a dilemma making sure everything is aligned and symmetrical (some still probably aren't) </H4>*

<H2>Firmware Overview:</H2>

CreatePad uses QMK firmware and is highly customizable, even the OLED can be configured using it! The attatched firmware (as of now) can store up to 10 unique, fully customizable configurations (even the knobs' functions!) through VIA.

<H2>BOM:</H2>

* 1x Seeed XIAO RP2040 MCU

* 9x MX-Style Switches

* 2x EC11 Rotary Encoders

* 11x Through-hole 1N4148 Diodes

* 1x 0.91 Inch OLED Display

* 9x white DSA keycaps

* 4x M3x16mm screws



that's about it for now :). I've learned so much during the process of designing this project, I can't wait to assemble it in the future!

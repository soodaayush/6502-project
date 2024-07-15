# 6502 Project

![6502-project](https://github.com/user-attachments/assets/7b8f9f58-106a-4e0d-bbf5-20445e1a9b7c)

## Inspiration

I always wanted to learn and understand how computer hardware really works at the lowest level. When I stumbled upon Ben Eater's videos on YouTube, his explanation along with his builds allowed me to properly understand hardware concepts.

## Challenges

Making sure the wiring are in their respective spots and making clean builds. Troubleshooting the clock module was a challenge initially but as I got used to working with electronics, things became easier. I was able to use my existing Arduino knowledge to hook up the clock module and step through the process of debugging and troubleshooting. Another challenge I faced was sourcing the correct components for my project.

## Lessons Learned

This project helped me develop practical skills in electronics and low-level programming and created a deeper understanding for how computers work. This was done through my learning of concepts like logic gates, binary numbers, hexadecimals, address and data bus, and various other integrated circuits. I also learned how important the role of a computer clock is and how timing affects the CPU and synchronization between different components, and finally, writing Assembly code to send instructions to the 6502 processor. I also learned about other integrated chips that are required to make a meaningful computer system, such as EEPROM, Versatile Interface Adapter, and Static RAM.

## Clock Module

![clock-module](https://github.com/user-attachments/assets/a35d2239-feb1-47df-8425-1d51c7536b66)
![clock-module-close-up](https://github.com/user-attachments/assets/1cfd91e9-2298-4970-b661-0ae9221e5ad6)

### Videos

<a href="http://www.youtube.com/watch?feature=player_embedded&v=vF9_5MOZK2A
" target="_blank"><img src="http://img.youtube.com/vi/vF9_5MOZK2A/0.jpg" 
alt="Clock Module Video" border="10" /></a>

### Description

This Clock Module controls and coordinates CPU functions with other integrated chips. You can adjust the clock speed by turning the blue variable resistor at the top left. The clock can be halted using the on-on switch in the middle. You can step the clock by pressing on the tact button to the left of the switch to debug and step it in case of problems. Faster LED flashing means higher clock speed. Being able to control the clock speed is important because we want to be able to step through the program one clock signal at a time. I also learned about the concepts of rising and falling edge of the computer clock signal. 

## 6502 Computer

![6502-computer-setup](https://github.com/user-attachments/assets/89715c3a-3bcf-4938-97de-0e4ce2fd5347)
![6502-computer-side-view-1](https://github.com/user-attachments/assets/6a0d5b5c-c57d-45f2-9591-927295c3e8d6)
![6502-computer-side-view-2](https://github.com/user-attachments/assets/a6f140fa-9baf-4a21-b9d5-0506e0ca6216)
![6502-computer-hello-world!](https://github.com/user-attachments/assets/27e90150-db20-41ac-84ad-70b3a0646d79)

### Videos

<a href="http://www.youtube.com/watch?feature=player_embedded&v=xEQMLtH9U-g
" target="_blank"><img src="http://img.youtube.com/vi/xEQMLtH9U-g/0.jpg" 
alt="6502 Computer Video #1" border="10" /></a>

<a href="http://www.youtube.com/watch?feature=player_embedded&v=NjlViZYWf6I
" target="_blank"><img src="http://img.youtube.com/vi/NjlViZYWf6I/0.jpg" 
alt="6502 Computer Video #2" border="10" /></a>

### Description

This is a computer powered by the 6502 CPU. Timing for the computer is provided by the clock module described above. The phrase "Hello, world!" is printed through assembled code loaded onto the EEPROM which interfaces with the 6502 CPU. Versatile Interface Adapter is then interfaced with 6502 to execute the code that prints "Hello, world!" to the LCD display.

## 4-Bit Adder

![4-bit-adder](https://github.com/user-attachments/assets/e0704c7e-2f04-4259-9410-3cea893d554c)

### Videos

<a href="http://www.youtube.com/watch?feature=player_embedded&v=jo9BVc5GQh0
" target="_blank"><img src="http://img.youtube.com/vi/jo9BVc5GQh0/0.jpg" 
alt="Clock Module Video" border="10" /></a>

### Description

This adds two 4-bit binary numbers to produce another binary number. At the top there are three logic gates (AND, OR, Inverter from left to right) built using bi-polar transistor. In the middle there are the same logic gates built using integrated chips that are controlled by switches as inputs. At the bottom is the 4-bit adder itself. The adder is comprised of multiple gates taking in two switches with four inputs. From there, a flashing LED would mean 1, while a non-flashing LED would mean 0. In the photo above, the binary numbers 1010 (10) and 1010 (10) are being added together to produce 10100 (20).

## Virtual Interface Adapter

![via](https://github.com/user-attachments/assets/4b2d793a-ab0e-4d5a-8200-0301de595140)
![via-close-up](https://github.com/user-attachments/assets/171ccf06-eeaf-4330-aec9-ae07f9c70554)
![via-side-view](https://github.com/user-attachments/assets/9116a08a-a35b-4b9c-8b1b-9d0913a4ff78)

### Videos

<a href="http://www.youtube.com/watch?feature=player_embedded&v=GA4NfH3_2c8
" target="_blank"><img src="http://img.youtube.com/vi/GA4NfH3_2c8/0.jpg" 
alt="Clock Module Video" border="10" /></a>

### Description

This produces a pattern in the LED's through the VIA (Versatile Interface Adapter). Again, timing for this computer is provided by the clock module above. The different light patterns show if the VIA is reading from 6502 data bus. The pattern themselves are written using Assembly language. 

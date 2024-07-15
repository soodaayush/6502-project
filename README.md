# 6502 Project

![6502-project](https://github.com/user-attachments/assets/7b8f9f58-106a-4e0d-bbf5-20445e1a9b7c)

## Inspiration

I always wanted to learn and understand how hardware really works at the lowest level. When I stumbled upon Ben Eater's videos on YouTube, his explanation along with his builds allowed me to properly understand hardware concepts.

## Challenges

Making sure the wiring are in their respective spots and making clean builds.

## Lessons Learned

This project helped me develop practical skills in electronics and programming and created a deeper understanding for how computers work. This was done through my learning of logic gates, binary numbers and how they are added, the importance of the computer clock and how timing affects the CPU, and finally, writing Assembly code to send instructions to the computer.

## Clock Module

![clock-module](https://github.com/user-attachments/assets/a35d2239-feb1-47df-8425-1d51c7536b66)
![clock-module-close-up](https://github.com/user-attachments/assets/1cfd91e9-2298-4970-b661-0ae9221e5ad6)

### Videos

<a href="http://www.youtube.com/watch?feature=player_embedded&v=vF9_5MOZK2A
" target="_blank"><img src="http://img.youtube.com/vi/vF9_5MOZK2A/0.jpg" 
alt="Clock Module Video" border="10" /></a>

### Description

This Clock Module keeps track of time for the 6502 CPU. You can adjust the clock speed by turning the switch at the top right. The clock and be turned on or off using a switch in the middle. You can step the clock by pressing on the button to the left of the switch to debug it in case of problems. You will be able to determine the speed of the clock through the frequency of the LED flashing.

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

This is a computer powered by the 6502 CPU. Time for the computer is provided by the clock described above. The phrase "Hello, world!" is printed through binary code loaded onto the 6502 CPU. From there, the wiring retrives the information from the CPU and prints it onto the LED screen.

## 4-Bit Adder

![4-bit-adder](https://github.com/user-attachments/assets/e0704c7e-2f04-4259-9410-3cea893d554c)

### Videos

<a href="http://www.youtube.com/watch?feature=player_embedded&v=jo9BVc5GQh0
" target="_blank"><img src="http://img.youtube.com/vi/jo9BVc5GQh0/0.jpg" 
alt="Clock Module Video" border="10" /></a>

### Description

This adds two 4-bit binary numbers to produce another binary number. At the top there are three manual gates from that are controlled by buttons as inputs. Gates from left to right: AND Gate, OR Gate, and NOT Gate. At the middle there are two gates within a chip that are controlled by switches as inputs. Gates from left to right: AND Gate and OR Gate. At the bottom is the 4-bit adder itself. The adder is comprised of multiple gates taking in two switches with four inputs. From there, a flashing LED would mean 1, while a non-flashing LED would mean 0. In the photo above, the binary numbers 1010 (10) and 1010 (10) are being added together to produce 10100 (20).

## Virtual Interface Adapter

![via](https://github.com/user-attachments/assets/4b2d793a-ab0e-4d5a-8200-0301de595140)
![via-close-up](https://github.com/user-attachments/assets/171ccf06-eeaf-4330-aec9-ae07f9c70554)
![via-side-view](https://github.com/user-attachments/assets/9116a08a-a35b-4b9c-8b1b-9d0913a4ff78)

### Videos

<a href="http://www.youtube.com/watch?feature=player_embedded&v=GA4NfH3_2c8
" target="_blank"><img src="http://img.youtube.com/vi/GA4NfH3_2c8/0.jpg" 
alt="Clock Module Video" border="10" /></a>

### Description

This produces a pattern in the light bulb through the VIA (Versatile Interface Adapter). Again, time for this computer is provided by the clock above. The different light patterns show if the VIA is reading from 6502 data bus. 

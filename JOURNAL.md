---
title: "Camplight"
author: "Candy"
description: "Neopixel warning light thingy!"
created_at: "2025-6-19"
---

## Day 1
Today, I started some research about how I could do this, and I think I want to try and make a Attiny85 dev board thing (or something like that!). Andddd I found some resources:

- https://www.microchip.com/en-us/product/attiny85
- https://github.com/tomasr8/attiny85-dev-board
- https://github.com/SpenceKonde/ATTinyCore/blob/v2.0.0-devThis-is-the-head-submit-PRs-against-this/avr/extras/tinyNeoPixel.md

Weeeell, lets just say I didn't really understand the datasheet... Still, I did some googling and found some examples. I guess what they usually have is like, the chip, a voltage regulator, a bunch of resistors.. diodes... etc.. looking at the example though, it made me understand more, which was awesome :D

### The Plan
sooo here's what I'm gonna like add;

- battery
- built in neopixels or some led
- usb-c?

## Day 2
I did the schematic!! I kind of just followed an open source board but I used a usb-c and used smd components. I also added some neopixels :3 There's this tp4056 to charge the battery through the usb and i hope it works.

![image](https://github.com/user-attachments/assets/1450e587-e984-47df-9110-e8f39d636072)

(I wrote this on day 3 tho)

I looked at an open source board I found on github, yea.. and I think I want to try to use a hot plate so I guess there's like smd components (?) Btw tysm acon, I got on a call with acon and she help me with my usb c :3 

## Day 3
Today, I finished the schematic and added footprints.. uhh I will add to this a bit later cuz I need to do some stuff :(
Here's the pcb thing! without the wires connected tho

![image](https://github.com/user-attachments/assets/752df3a1-37ed-4942-b0ae-b23c67b16a53)

I don't know what to write here, but I guess... it looks pretty.. nice?

## Day 4
I spent around 2h routing the pcb! This is the end result and its like 4 layers. While routing the pcb, I kinda selected the wrong footprint for resistors so I had to redo some stuff.

![image](https://github.com/user-attachments/assets/c6211f49-8ec1-4888-ac49-e83982310b7b)

![image](https://github.com/user-attachments/assets/0ef97ea0-153c-419f-a9c3-2f92486dfa0a)

But then like there's this problem at the usb-c so idk how to fix it...

![image](https://github.com/user-attachments/assets/89c16daa-775f-4a76-a7e6-655f81ec1a9d)

### Silkscreen
I used figma and took around 30 minutes drawing kinda random stuff, and here's what happened:

![image](https://github.com/user-attachments/assets/dd9ef286-a210-4eab-b75b-17cc7d21005a)

![image](https://github.com/user-attachments/assets/e5cc30ea-8d91-438b-9c2c-7ee3ae0c3cdf)

![image](https://github.com/user-attachments/assets/6c9b4f15-490a-443e-af05-fa7eead045ca)

idk what to do at the back, i guess. its going to be covered by the case. next up tho imma go link the bom/make casing :3


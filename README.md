# Smart-Mirror using Raspberry PI 3 { Programming Language - Python }

Raspberry PI acts mini-computer with 1GB RAM. Its like Motherboard in our Computer but in tiny version. Raspberry PI has 40 GPIO pins ( 2 - 3.3V pins, 2 - 5V pins, 8 ground pins, remaining I/O pins), 1 Ethernet port, 1 - 3.3mm audio port, 4 USB ports, 1 HDMI port, 1 micro USB port, and 1 micro SD Card slot. It has Broadcomm Processor and Ethernet Controller (Works for wireless connection). All this makes Raspberry PI acts a motherboard.

Smart Mirror is like a modern mirror will displays the things we like to.
In this case, I took news, weather, time and our locality.

Material Required:  
1)Monitor,  
2)HDMI cable,  
3)Raspberry PI 3,  
4)SD Card,  
5)Acyrlic sheet,  
6)Power cable for Monitor  
7)Micro USB Cable for Raspberry PI's power supply .  

First, we need to install Raspbian OS (Type of Linux OS) in SD Card with acts as Windows/MasOC in our PC.  
Second, Insert SD Card into the Raspberry PI (Slot is located at bottom-behind).   
Now, connect Raspberry PI to Monitor through HDMI cable and provide power supply for both of them.

Download the files I provided, and store them in one folder.
Then Open Terminal and the following:

•sudo pip install -r requirements.txt

•sudo apt-get update -y

•sudo apt-get install -y python-pil.imagetk

•python smartmirror.py

This steps helps to reach our output.


Sample Output pics:

We need to cover the display with acrylic sheet, which changes black colored portion on the screen to reflecting mirror. [I didn't in the below picture]

![IMG-20200823-WA0006](https://user-images.githubusercontent.com/59284745/137160649-3b0cf9dc-4aa1-4028-bd99-451fd0e258a6.jpeg)


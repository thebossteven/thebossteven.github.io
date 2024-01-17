---
layout: post
title: Project: Hack Station pt.1
---
#**Project: Creating a mini hacking station on the Raspberry Pi**



I wanted a portable system I could use strictly for attacking that wasn’t connected to any of my other systems and I was getting pretty tired of looking at the virtual machine interface on my Mac. I could’ve just bought a new laptop and installed a version of the **Kali OS**, but deep inside I knew I wanted something slightly cooler and a whole lot more nerdy. 

That’s when I came across _“the Raspberry Pi Recovery Kit”_ by **Jay Doscher**. Just looking at the thumbnail made me want to create one of my own, as images of cyberdecks in my favorite novels came to mind. Immediately I set a new goal for myself, but being who I am, someone with very little actual technical knowledge, I needed to divide this project into a whole lot of baby steps. So after a lengthy introduction, welcome to **step 1: Choosing the system and installing the OS.**

I decided to go with the _Raspberry Pi 3_, as I had one lying around that was gifted to me. This specific Raspberry Pi had Retropie running on it, so I first had to clear out the **Micro SD** by formatting it. I also went ahead and downloaded an ISO for Kali linux. Seems pretty simple, how could I mess this up?

**-Issues pt.1:**

I had formatted the **Micro SD card**, yet when I inserted it into my system, it said it only had 57MB of capacity. What exactly was going on? My hypothesis is that it contained extra data that did not want to be formatted, as it was used to boot up a system(in this case retropie on the Raspberry Pi) Whenever I tried to format it using disk utility it gave me an error, which left me with only one choice, forcibly format it using the terminal and hope for the best.

(List off the commands to do this)

After typing all of that in, I pressed enter and…. It worked :)  which means I have finally gone from step 0 to step 1. Now to install Kali OS. 

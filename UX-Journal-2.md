
### Journal Entry Two: By Kyle Reeves, 5/1/2021

#### My user eXperience with dual booting my PC: 

  Two weekends ago I had little to nothing to do, so I decided I would create something for myself to do. I have always been curious about Linux operating systems so I figured I would try to get one working properly on my Windows 10 PC. My goal this weekend was to dual boot my computer so during startup, I could either pick my Windows 10 machine or my new Ubuntu Linux machine. My main reasoning behind doing this is because before, I had done all my schoolwork on my Apple Macbook and I wanted a work environment on my PC that wouldn’t distract me. This would cause my PC to become more **efficient** being that it achieves a higher maximum productivity because it now exists as both my gaming / casual computer and my work computer. With this however, I had no idea where to start or how I would accomplish this task.

  After doing some research on which Linux operating system I should use and ways of implementing a dual boot system, I decided on using Ubuntu 20.04 and creating my blank thumb drive into a boot drive that would allow me, on startup of my computer, to create an Ubuntu environment. Being that Ubuntu is free, it was easy to get the ISO file from the internet. An ISO file is an archived image that contains the exact data that can be found on an optical disk. Now with this ISO file is the only thing on my thumb drive, I used a program on my Windows 10 machine called “Rufus” which assists in turning my thumb drive into a boot drive that my computer will recognize. The next step in this process is preallocating space on my computer for this new Ubuntu machine. I accomplished this by going to disk management on my Windows 10 computer and allocating around 50GB of space from my secondary hard drive.

  Now that all the setup steps had been completed, I plugged my boot drive in and restarted my computer. This is where I ran into my first problem during this process. Whenever I restarted my computer, it booted my Windows 10 machine and ignored the boot drive completely. Luckily, after consulting the internet with this issue, the fix was simple. During the startup of my computer, I needed to enter my BIOS and change the boot order to recognize my boot drive before my default Windows 10 machine. The BIOS, or Basic Input / Output System, is the firmware used to perform hardware initialization during the booting process and to provide runtime services for operating systems and programs. (see figure 1) After this change, the next time I booted up my computer it ran the boot drive and began the Ubuntu live setup. This process is similar to other setup processes, Ubuntu had me choose my language, set up my wifi, create an account and password, and configure where it would be installed. (see figure 2 - 3) After this was done, I had successfully created a working version of Ubuntu on my computer.

  Now the last step in this process is to configure dual boot so that I can access both machines easily during my computer startup. To achieve this, I booted into my Windows 10 machine and used a program called “EasyBCD” which is designed to create these dual boot systems. After using the program, now wherever I startup my computer it displays a screen asking which machine I would like to boot up (see figure 4). Now my computer can either run Windows 10 or Ubuntu 20.04 and my dual boot goal has been completed. 

#### Figure 1
![Figure 1](https://i.imgur.com/gFp9wa8.png)
#### Figure 2
![Figure 2](https://i.imgur.com/r2xjrLv.png)
#### Figure 3
![Figure 3](https://i.imgur.com/Ndu7gzS.png)
#### Figure 4
![Figure 4](https://i.imgur.com/0tmB4fO.png)

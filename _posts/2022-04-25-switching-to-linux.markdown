---
layout: post
title:  "Switching to Linux"
date:   2022-04-25 08:30:00 -0500
categories: jekyll update
---
## Why is Windows bad for Privacy?

Windows Operating Systems are by design bad for privacy, being guilty of using Windows for years, I've
seen the invasion of privacy that it can pose. Nothing surprising I guess, just read through their
[privacy statement](https://privacy.microsoft.com/en-us/privacystatement).
I'll take them at their word and assume they're doing the maximum amount of monitoring, collecting, and harvesting
of our personal data within the limits of the current laws.

Enough said, let's check out our new OS..

## Why Linux?

##### Cost
This one is obvious, if you use Windows OS then you have to buy for the privilege to use it. I guess you could go sniffing around the black market for a free version ha but do so at your own risk.

Linux is FREE for the people.

##### Security
Windows is a blackbox. You have to put your trust and faith in Microsoft that their group of developers will be able to find near all of the security issues before releasing the OS to the public.

Linux is far superior in regards to security, it has a massive community of developers that are constantly reviewing the source code due to it being completely open-source. The developers can see every single line of code, greatly increasing the chances of finding and fixing a security issue before it becomes a [zero day](https://en.wikipedia.org/wiki/Zero-day_(computing)) attack.


##### Privacy
Once again, take Microsoft at their word and just look at their [Windows data collection summary](https://privacy.microsoft.com/en-us/data-collection-windows). Remember, this is just what they're willing to admit to, but big tech, including Microsoft, cannot be trusted; we're being watched.

Take Linux at their word and check out there [privacy](https://linuxmint.com/privacy.php) page. If you read through this page, you'll understand that they value privacy and security first and foremost, and knowing this, well... it just makes me feel all warm and cozy inside.

![Warm and Cozy](https://media.giphy.com/media/YnNKrPub6aYbc8u53S/giphy.gif)

<br/>
## My Adventure

##### Goal
My goal was to STOP using the Windows OS. To accomplish this, I'm going to take my old gaming computer, currently running Windows 7 Professional, and install Linux OS on it. I built this computer back in 2012 so the hardware WAS considered good but it's day has since past and I'm now just trying to squeeze as much energy and time as I can out of this old thang.

I have two Western Digital [HDD](https://en.wikipedia.org/wiki/Hard_disk_drive)'s currently installed in my computer, so I'm going to re-purpose the 2nd HDD to now be the main hard drive for my Linux OS. This setup will be considered a [multi-boot](https://en.wikipedia.org/wiki/Multi-booting) setup, simply meaning, I'll have both Windows and Linux available to boot.

#### Scenario & Setup
##### Old Gaming Computer Specs

|:--------------------|----------------------------------------------:|
| Operating System    | Windows 7 Professional                        |
| Processor           | Intel© Core™ i7-2600K CPU @ 3.40GHz × 4       |
| Memory (RAM)        | 8.00 GB                                       |
| Graphics Card       | NVIDIA Corporation GF116 [GeForce GTX 550 Ti] |
| Hard Drive 1        | WD Caviar Black WD1002FAEX 1TB 7200 RPM       |
| Hard Drive 2        | WD VelociRaptor WD3000HLFS 300GB 10000 RPM    |

<br/>

#### Step 1: Backup Hard Drive
I'm currently using a [Start9](https://start9.com) Embassy private server, setup with an external hard drive, and using the [File Browser](https://filebrowser.org/) software to store all of my files. I did a quick scan of my existing hard drive, that I'm planning on reformatting and using for the Linux install, and then backed up what I cared about; most were trash though.

#### Step 2: Wipe Hard Drive
Now that I confidently have everything backed up, I'm going to wipe the hard drive. Wiping is different than deleting, when you wipe a hard, you erase EVERYTHING that is currently stored on it, whereas deleting can just mark file/s for deletion at a later point. To perform the wipe, I'm going to use [Input Software Name](https://www.google.com/).

#### Step 2: Choosing Linux Distro
Luckily, I was exposed to Linux during a work project, that was long ago but I recall setting up many virtual machines, using [Oracle VirtualBox](https://www.virtualbox.org/), and these VM's used an Ubuntu image. Ubuntu was nice to use when I got the chance, but would I call it my favorite? No, but I understood the benefits of it in general.

Figuring my knowledge and opinions were outdated on Linux in general, I decided to do some additional research and I came across [Linux Mint](https://linuxmint.com/). Short overview, I found that it's based off of Ubuntu, it persists the open-source philosophy and privacy features loved by many, while introducing a simpler installation process that births a beautiful desktop baby. I won't bore you with all of my sales pitch in this blog, you can do your own research on that topic if you want, but long story short, I chose [Linux Mint](https://linuxmint.com/) to install on my machine.
![Linux Mint Logo](/img/LinuxMintLogo.jpg)

#### Step 3: Download Linux
I downloaded [Linux Mint](https://linuxmint.com/) from the [downloads](https://linuxmint.com/download.php) page. Saved it to a location on my existing Windows machine so I could access the downloaded files in the next steps.

<br/>

#### Step 4: Verify

Don't trust, verify!

I verified that the image I just downloaded was what I expected to download. These steps are provided [here](https://linuxmint-installation-guide.readthedocs.io/en/latest/verify.html).

<br/>

#### Step 5: Create Bootable USB Drive
Next I needed to create the bootable USB drive, all of this is also well documented [here](https://linuxmint-installation-guide.readthedocs.io/en/latest/burn.html). I used a SanDisk 128 GB USB drive that I had already purchased a while back, I had no issue with the steps and my Sandisk USB drive was now bootable.
![Confused-Keyboard](/img/Sandiskusb.jpg)

<br/>

#### Step 6: Installation
I next restarted my computer with the USB drive installed and entered bios. I can never remember which one it is ha so I was pressing F2, F10, and F12 simultaneously. Turns out it was DEL lol...
![Confused-Keyboard](https://media.giphy.com/media/52HjuHsfVO69q/giphy-downsized-large.gif)

Now in the bios, I clicked the "Boot Options" button, and then selected the USB flash drive.

Once Linux Mint was booted up, I clicked on the CD icon to Install Lint Mint.
![Install Linux](/img/InstallLinuxMintIcon.jpg)

There's also amazing documentation for this step [here](https://linuxmint-installation-guide.readthedocs.io/en/latest/install.html).

After successfully completing the installation setup and configuration, Linux Mint is installed!
![Linux Mint](/img/linuxmintdesktop.jpg)

<br/>

#### Step 7: Party
Sick dawg, I just completed 1 task off of my privacy 4 life list.
![Party](https://media.giphy.com/media/S4AnOkBwfcb4GyDzK7/giphy.gif)

Fuck Windows, Linux Mint is now up and running with the default setup. I'll probably create another post for the first software and/or applications to install but for now that's a wrap, thanks for reading!

---
layout: post
title:  "Switching to Linux"
date:   2022-04-25 08:30:00 -0500
categories: jekyll update
---
### Why is Windows bad for Privacy?

Windows Operating Systems are by design bad for privacy, being guilty of using Windows for years, I've
seen the invasion of privacy that it can pose. Nothing surprising I guess, just read through their
[privacy statement](https://privacy.microsoft.com/en-us/privacystatement).
I'll take them at their word and assume they're doing the maximum amount of monitoring, collecting, and harvesting
of our personal data within the limits of the current laws. Enough said, let's check out our new OS..

### Why Linux?

| Topic          |  Linux | Windows |
|----------------|--------|---------|
| Reliability    | [x] | [] |
| Customization  | [x] | [] |
| Variety        | [x] | [] |
| Cost           | [x] | [] |
| Support        | [x] | [] |
| Privacy        | [x] | [] |
| Open Source    | [x] | [] |

<br/>
### My Adventure

#### Goal
My goal was to STOP using the Windows OS. To accomplish this, I'm going to take my old gaming computer, currently running Windows 7 Professional, and install Linux OS on it. I'm going to wipe the 2nd drive in the system, since I'm planning on using that one solely for the Linux OS.

#### Scenario & Setup
##### Old Gaming Computer Specs

|:--------------------|:----------------------------------------------|
| Operating System    | Windows 7 Professional                        |
| Processor           | Intel© Core™ i7-2600K CPU @ 3.40GHz × 4       |
| Memory              | [x] |
| Hard Drive 1        | [x] |
| Hard Drive 2        | [x] |
| Graphics Card       | NVIDIA Corporation GF116 [GeForce GTX 550 Ti] |

<br/>

#### Step 1: Backup Hard Drive
I'm currently using a [Start9](https://start9.com) Embassy private server, setup with an external hard drive, and using the [File Browser](https://filebrowser.org/) software to store all of my files, so I did a quick scan of my files and then backed up what I cared about; most were trash though.

#### Step 2: Choosing Linux Distro
Luckily, I was exposed to Linux during a work project, that was long ago but I recall setting up many virtual machines, using [Oracle VirtualBox](https://www.virtualbox.org/), and these VM's used an Ubuntu image. Ubuntu was nice to use when I got the chance, but would I call it my favorite? No.

Figuring my knowledge and opinions were outdated on Linux in general, I decided to do some additional research and I came across [Linux Mint](https://linuxmint.com/). Short overview, I found that it's based off of Ubuntu, it persists the open-source philosophy and privacy features loved by many, while introducing a simpler installation process that births a beautiful desktop baby. I won't bore you with all of my sales pitch in this blog, you can do your own research on that topic if you want, but long story short, I chose [Linux Mint](https://linuxmint.com/) to install on my machine.


#### Step 3: Download Linux
Download [Linux Mint](https://linuxmint.com/) from the [downloads](https://linuxmint.com/download.php) page. Save it to a location on my existing Windows machine so I can access the downloaded files in the next steps.

#### Step 4: Verify
Don't trust, verify. Verify the image that you just downloaded is what you expected to download. Steps are provided for us [here](https://linuxmint-installation-guide.readthedocs.io/en/latest/verify.html).

#### Step 4: Create Bootable USB Drive
Next I needed to create the bootable USB drive, all of this is also well documented [here](https://linuxmint-installation-guide.readthedocs.io/en/latest/burn.html). I'm using a SanDisk Cruzer 128 GB USB drive that I had already purchased a while back, I had no issue with the steps.

#### Step 5: Installation
I next restarted my computer with the USB drive installed and entered bios. I can never remember which one it is ha so I was pressing F2, F10, and F12 simultaneously. Turns out it was DEL lol...

Now in the bios, I clicked the "Boot Options" button, and then selected the USB flash drive. I'm always nervous as shit in the bios, idk why haha gunna click wrong option and ruin everything...

Once Linux Mint was booted up, I clicked on the CD icon to Install Lint Mint. Also sweet documentation for this step [here](https://linuxmint-installation-guide.readthedocs.io/en/latest/install.html)

+++
title = "The Suckless Experience"
date = 2024-08-08T15:14:19-04:00
tags = ["blog","linux","tech"]
+++

# Introduction

So, after using AwesomeWM/Qtile on Arch Linux, I decided to try out Fedora for a little while with the KDE Desktop Environment.

Once I was done using KDE, I decided to switch back to Arch Linux and I decided to try out DWM.

# What is Suckless

[Suckless](https://suckless.org) is a software development group that focuses on making small, minimalistic programs for the Linux/BSD Desktop.

By Default, Suckless programs are very minimal with barely any features, the way you can add these missing features is through patching.

By using pre-existing patches that modify the code, you can essentially make your own program.

# Help, I can't install a suckless program

Calm down, the reason why is because the package maintainers for your distro decided not to package it.

Why? Because the way you configure suckless programs is different from other programs.

Unlike other programs that use config files, Suckless Programs have you directly edit the source code of the program.

The "config" file in suckless programs is basically just a C Header file

# Why is it like this?

Since all the configuration is done through the source code before compilation, your program probably will run faster due to it not having to read a config file that can change at any time.

# What Suckless Programs do I use

Programs I use (links lead to my build of the programs):
- [DWM](https://github.com/redkittty/dwm-envixty)
- [ST](https://github.com/redkittty/st-envixty)
- [Tabbed](https://github.com/redkittty/tabbed-envixty)

# DWM

DWM - Dynamic Window Manager is probably the most bloated suckless software, but it is also the most enjoyable to use.

The reason why it's the most bloated is because DWM has some features you wouldn't need for just a Window Manager.

An example of this is the fact DWM includes a bar by default when it isn't needed (Xmonad doesn't have one by default)

This is not to downplay DWM though as it is still a great peice of software.

Here is my current build of DWM:

![DWM Build](/img/dwm.png)

# ST

ST - Simple Terminal is a terminal emulator that is minimalistic while still supporting things like Unicode characters pretty well.

The only patch I added to ST is the ability to scrollback.

The special thing about ST (for me) is that, I was using ST when I was still using AwesomeWM/Qtile

# Tabbed

Tabbed is a program that allows you to add tabs to any program by running the program inside of Tabbed.

I really only use tabbed to get tabs inside of ST

# Conclusion

So far, I have had fun with using Suckless Programs.

I think everybody should atleast give Suckless Programs a chance and actually try them and see how they like it.

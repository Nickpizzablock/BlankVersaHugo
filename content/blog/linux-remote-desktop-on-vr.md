+++
date = '2026-03-04T09:55:49-08:00'
draft = true
title = 'Linux Remote Desktop on Vr'
+++

## Scope
My main laptop has a dual boot Linux/Windows setup with a Quest 3. I want a 
simple screen mirror solution. It would be a bonus to have a full remote 
desktop experience with client keyboard and mouse input, but the main usecase 
is just screen mirroring.

I use Ubuntu 24.04 LTS with mostly stock settings. I don't want VNC or RDP 
because of audio latency video lag. 

We will use Steam Link from the Meta Store. It is the most seemless way to get 
the features while maintaining official app support.

## Main Issues
The main issue are Linux Display Servers. Ubuntu uses Wayland by default, which 
is a more modern implementation compared to the dated xorg/x11 display server. 
This should not be confused with Window Managers which only dictate how windows 
are arranged, but not how they are drawn and organized.

Wayland has its advantages: app security, native trackpad gestures, 
and smooth scrolling to name the ones I know, but the biggest downside is on 
screen sharing. For example, screen sharing on Zoom, Teams, or Discord causes 
permission issues and shows a blank screen. Permission issues are the bane of 
my existence since the issue can scale from the app, installation procedures, 
or linux user account setup.

### Testing

### The 

### TOC

## Tutorial
1. Switch to xorg/x11. Log out of the computer, click on your profile, and 
click the gear icon on the bottom right. `Ubuntu` is Wayland. `Ubuntu on Xorg` 
is xorg. 

2. Add back gesture trackpad control. Install Touchegg for trackpad gesture 
monitoring. Install Touche for a GUI for Touchegg.

3. Restart your computer. 

4. Find a solution to get cursor support.

5. Start Steam on the computer. Put on the Quest and open Steam Link. Setup 
Steam Link via the on screen directions.

6. Choose between flatscreen and vr mode. With flatscreen, you get passthrough 
and use different apps on MetaOS. With VR mode, you will go to the Steam VR 
interface with the world being streamed. I assume this is more resource 
intensive but you get cursor support for free I think.

The quick brown fox jumped over the lazy dog.

`The quick brown fox jumped over the lazy dog.`
# Shunyan's SoftGraphic Plugin v1.5.0

![](/resources/img/softgraph.png)

!!!warning
Should be 100% accurate to console, but may have performance issues
!!!

[!file Download (manual setup)](https://www.dropbox.com/s/drfyqhpz0it5qw6/SoftGraphic_1.5.0.dll?dl=1)

This is a HLE graphics plugin using a modified MESS rdp core for graphics rendering, and using D3D9 or Direct Draw as output device.

!!!info
Make sure to enable **Graphics HLE** under Plugins in the general settings menu
!!!

!!!warning
The renderer is heavily CPU reliant, and so if you dont have sufficient CPU power check out the softrender fork of [GLideN64](GLideN64.md)
!!!

!!!danger This plugin is NOT recommended for speedrun usage

Due to the lack of multithreading, slowdowns are almost guaranteed on even the best CPUs. So instead use [angrylion](angrylion_RDP.md) which uses the same renderer but should deliver better performance
!!!

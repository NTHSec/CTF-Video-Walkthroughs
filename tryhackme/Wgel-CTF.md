![TryHackMe Beginner CTF Walkthrough (1)](https://github.com/NTHSec/CTF-Video-Walkthroughs/assets/150489159/7b83d5e6-ddcb-4822-9497-bf2829562901)

# https://youtu.be/n3wiUcBHM0k

This is the "Wgel CTF" box from [TryHackMe](https://tryhackme.com/room/wgelctf)! This was a straightforward box that abused a leaked RSA private key file. From this, you could SSH into the server and escalate privileges by abusing the elevated privileges the user had for the `wget` binary. With this privileges, we modified the `/etc/shadow` file with our own root password!

As always, all constructive criticism is welcome! I hope you learn something and Happy Hacking!

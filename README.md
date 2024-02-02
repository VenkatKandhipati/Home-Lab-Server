# Home-Lab-Server
Personal home lab server running a variety of self-hosted services. This project has been evolving every year.

The Home Lab project aimed to create a personal home server using a Raspberry Pi 400 running Ubuntu. The goal was to set up self-hosted services including a password manager, network-wide ablocking, file hosting, a proxy manager, and a media server.

Using Docker, the services were containerized, allowing for easy deployment, management, and scalability. Docker's containerization technology ensured that each service ran consistently across different environments without conflicts. This modular approach facilitated updates and maintenance of individual services without impacting the entire system.

The Raspberry Pi 400 provided a compact and efficient hardware platform, while Ubuntu served as the Linux-based operating system. The project successfully established a self-hosted home lab environment where I had more control and freedom over services that I use on a daily basis. 

This is the dashboard homepage (which is also a self-hosted service called FLAME running in a docker container):
![FLAME Dashboard](https://github.com/VenkatKandhipati/Home-Lab-Server/blob/2293fc6896eec89ad39e6f25a6275a1286b19fad/Screenshot%202023-05-10%20092005.jpg)

Recently I have upgraded from a Raspberry Pi to an old used Dell Optiplex server. This upgrade gave me more ram and a large hard drive!

Now I run Proxmox, which acts as a hypervisor, running 2 main VMs. One as a NAS (network attached storage) where I can store all my media and files. Another as my main Ubuntu Server hosting all of the same services on my Raspberry Pi.

Here is how my new dashboard looks (which is also a self-hosted service called HOMARR running in its own docker container):
![HOMARR Dashboard](https://github.com/VenkatKandhipati/Home-Lab-Server/blob/main/Screenshot%202024-02-01%20173707.jpeg)

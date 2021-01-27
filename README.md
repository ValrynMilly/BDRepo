# BD - 27/01/01/2021 - NOTES

## Installing Linux Ubuntu

You can do this however you like all you need to do is set up a LinuxVM in any enviroment you feel most comfortable, I first set up a linux VM on my desktop Windows machine, I did this by downloading both the Ubuntu ISO image & VirtualBox. Follow guides online but for a quick start I would suggest creating a virtual machine that utalizes at least 2 Physical Cores, 8-12GB RAM & 64GB Disk storage that preferably an SSD. 

[Download link for Oracle VirtualBox](https://www.virtualbox.org/wiki/Downloads) Select your OS and download installer

[Download link for Linux Ubuntu](https://ubuntu.com/download/desktop) ISO File

### Current Set-up

I have Git & MySQL set up on a linux virtual machine hosted on Google Cloud Platform, I chose to host on GCP only because it is the only platform where I can create such a machine only for personal use (free) without limitations. I believe this is the best way to work as you can access the machine from anywhere in the world on any host machine. 

### Commands Used on Linux (Mini Tutorial)

I am going to show you step by step how I installed Git & MySQL on a linux virtual machine using the Terminal.

Install git using apt-get

`sudo apt-get update`

Install git

`sudo apt-get install git`
Read messages and follow promts from the installer.

#### Login to Git
Username
`git config --global user.name "someuser"`
Email
`git config --global user.email "someone@gmail.com"`

#### Quickstarts!

Lets clone this repository
`git clone https://github.com/ValrynMilly/BDRepo.git`

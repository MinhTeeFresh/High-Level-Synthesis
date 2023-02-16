# High-Level-Synthesis - Getting Started
make sure to ```vagrant halt``` when finished using the virtual machine



## Step. 1 Install Oracle VM VirtualBox

https://www.oracle.com/virtualization/technologies/vm/downloads/virtualbox-downloads.html  
- runs our virtual machine [vargant]


## Step. 2 Install Vagrant AMD64
https://developer.hashicorp.com/vagrant/downloads  

vagrant cheat sheet: https://gist.github.com/wpscholar/a49594e2e2b918f4d0c4



## Step. 3 Clone this Repository
```
//open command terminal
cd into repo directory
vagrant up //uses our text file "Vagrantfile" with all the necessary commands
```


```
vagrant ssh
iverilog
vvp
```


### once successfully installed iverilog  this should print:  
![image](https://user-images.githubusercontent.com/88512549/213801450-ac907747-8503-498d-9515-65f27b400782.png)


--------------------------------------

~Sootty (in VagrantFile)~   


## DWFV
simple digital waveform viewer with vi-like key bindings  
https://github.com/psurply/dwfv

## PYNQ-Z2 Setup Guide

download zip with image: 
[choose the one for our board (PYNQ-Z2)  
http://www.pynq.io/board.html

write image into SD card   
[follow the link below for steps depending on your operating system]  
https://pynq.readthedocs.io/en/v2.3/appendix.html#windows


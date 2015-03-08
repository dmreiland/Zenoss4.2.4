# Zenoss4.2.4
Zenoss 4.2.4 Auto-deploy script with resources. 


Hello,

Decide to upload my auto-deploy.sh script file as the ones I've seen around the internet and in other repos contain broken links that will fail silently and without error. 

I used this script on on the following VM to test:

https://virtualboximages.com/CentOS+6.5+x86_64+Desktop+VirtualBox+VDI+Virtual+Computer

One of the tutorials I used was:

https://www.digitalocean.com/community/tutorials/installing-and-configuring-zenoss-on-a-centos-virtual-private-server

These are both bound in Resource List.txt included in this repo. It includes other links/info I found useful as well. 

TO INSTALL ------------------------------------------------------------------------------------------------------------------

First login to a root terminal.

Rmove old mysql-libs:

  yum remove mysql-libs
  
  copy over the core-autodeploy.sh onto your machine.
  
  cd into the directory where you saved core-autodeploy.sh and runt the following command:
  
  ./core-autodeploy.sh
  
  You have to press enter then press 'q' and type yes to contiune.
  
  The script will run and you will be left with a fresh install of Zenoss 4.2.4 running.
  
  
  From there, follow other setup guides to get started! 
  
  


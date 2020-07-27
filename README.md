
## How to open and use Linux Virtual Machine
First open git bash and make your way to the folder where the vagrant file is located,
On my PC this it is on my desktop and I cd to navigate to the directory


vagrant up - boots up the vm

vagrant status - check if the vm is running

vagrant ssh - grants access to vm

sudo apt-get update -y

nano name_of_file allows us to enter inside of a file and then edit it

touch nameoffile allows us to create a file in linux

deleting a file -- "rm nameoffile" (may have to use sudo for admin usage)

mkdir nameofdirectory allows us to create a directory

how to go inside a directory cd nameofdir
how to exit a directory -- "cd -"
how to return to the root directory -- "cd /"
how to go back one by one directory "cd .."

How to print on the command line -- echo "hello"

How to change to the root user -- "sudo su"
How to return to normal user (terminal) "exit"
How to check who is using the machine - "id"
 
- Sudo works by allowing us to run a command in admin

Where am I? - pwd command shows the current file location (present working directory)
What do I have in the current directory? ls (list)
How to find hidden files in a directory? - ls -a (a stands for all)
How to find the name of operating system? we use 'uname' 
- apt-get is a package manager where we can update/install packages
- sudo apt-get update -y
- Automates the updates without asking us. The 'y' is a way to get around the prompt, does optional and mandatory updates

vagrant halt - pauses vm
vagrant destroy - destroys vm
vagrant reload - refreshes vm and starts again

apt-get install nginx
apt-get already has many packages available so it is able to install nginx for us
if it cannot find nginx, it will look online to find the program on specific directories

How to check the status of the installed program -- "systemctl status nginx"
nginx is a web server that allows us to launch live websites, connecting to
IP's etc

When we search in a website we don't type in a IP address, we have a website name

Vagrant files are written in Ruby

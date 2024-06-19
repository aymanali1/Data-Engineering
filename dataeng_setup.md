### Installing multipass
sudo snap install multipass

multipass launch --name <name>

multipass exec <name> -- lsb_release -a

multipass list
multipass find

multipass start <name>
mutlipass stop <name>
multipass shell <name>
exit

sudo apt update
sudo apt upgrade -y

sudo addgroup <groupname>
sudo adduser --ingroup <groupname> <username>

sudo visudo 
su - <username>


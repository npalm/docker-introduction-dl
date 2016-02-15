# Hands on Labs
## Prerequisites


!SUB
### Environment
* For this Docker we use a VirtualBox VM to setup a common evironment.
* The VirtualBox appliance contains
  * Ubuntu 14.04 Desktop
  * Tools: Docker, Docker Compose nad Git (at least)
  * User: Vagrant, Password: Vagrant
* For setting up the virtual machine we use Vagrant. Vagrants automates the our setup.


!SUB
### Installation
* Download and install [Vagrant](https://www.vagrantup.com/downloads.html)
* Once vagrant is installed you open an terminal
  * Create a new directory.
  * Run the command `vagrant init npalm/ubuntu-1404-dev-desktop; vagrant up --provider virtualbox`. This command will download the virtual machine.

!SUB
### Using Vagrant and getting ready
* Below some useful vagrant commands.
```
vagrant up               # Starts the VM
vagrant halt             # Stops the VM
vagrant destory          # Removes the VM
vagrant box list         # Shows all the local vagrant boxes
vagrant box remove <id>  # Removes a box
```
* So get ready:
```
vagrant up
```


!SUB
### Some guidelines
* You will find the slides here: [http://npalm.github.io/docker-introduction-dl/](http://npalm.github.io/docker-introduction-dl/)
- Navigation through the slides is easy, just use your arrow keys. Left and right for going to the previous or next section and up and down for previous or next page. The space bar always give you the next page.
- All code blocks unless mentioned are meant to execute by your self.
- Have fun, take your time and feel free to ask questions.

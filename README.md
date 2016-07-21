# SubjectsPlus-Vagrant
A Vagrantfile and shell script to create a development environment for SubjectsPlus

## Setup 

* Install <a href="https://www.vagrantup.com/downloads.html">Vagrant</a>
* Clone the repo to your local machine
* In the SubjectsPlus-Vagrant folder: 
  ```
  vagrant up
  ```
* Visit <a href="http://localhost:8889/SubjectsPlus/control">http://localhost:8889/SubjectsPlus/control</a> to finish the installation
* The default database username is `sp` and the password is `grokgro3#3ogk3og3`

## Customization

The MySQL username and password are setup using the shell script and can be changed by altering the variables at the top of the script. 

In the SubjectsPlus-Vagrant folder there will be a new public/SubjectsPlus folder that you can use for development work. 

The script was forked from this GitHub gist: https://gist.github.com/rrosiek/8190550

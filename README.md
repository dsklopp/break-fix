# break-fix
## Purpose
Reading documentation is one way to get up to speed on a technology.  Implementing the tech is yet another; it familiarizes you with the components and their configuration files.  These exercises allow a different approach: tinkering in a simulated/safe environment.  Challenge yourself by spinning up a vagrant machine, breaking that environment with a provided script, and then learning the nitty-gritty details by making that technology work again.

## Method
1. clone the repo
1. cd <technology>
1. vagrant up
1. vagrant ssh
1. cd /vagrant/scripts
1. execute a script
1. repair the damage

While you can work on this solo, consider inviting someone along for the ride.  Pay attention to how they think, what they choose to investigate and when.  Discuss tools used and troubleshooting tricks.  Ask each other to whiteboard the components as you're working on them.  Running the vagrant machines is a fun way to learn the technology, but interacting with another admin allows should accelerate the process.

## Adding a new technology:
### Directory Structure
```
<technology>/
├── Vagrantfile
└── scripts
    ├── break01.sh
    └── break02.sh
```

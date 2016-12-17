# machine [![Build Status](https://travis-ci.org/markosamuli/machine.svg?branch=master)](https://travis-ci.org/markosamuli/machine)

Machine setup, powered by Ansible. 

I've just got a new laptop running Ubuntu 16.04 and I'm working on getting my environment 
set up, more or less from scratch. I have not tested any of these on my OS X systems.

This is forked off from [caarlos0/machine](https://github.com/caarlos0/machine) with my 
specific requirements and updates.

# Ansible Roles

[caarlos0](https://github.com/caarlos0) suggested splitting the tasks into roles that 
could be a good idea, especially for running tests in Travis CI, but for now this works 
quite nicely as I can keep all the files in one place.

- [nodesource.node](https://github.com/nodesource/ansible-nodejs-role)
- [kbrebanov.erlang](https://github.com/kbrebanov/ansible-erlang)
- [markosamuli.visual-studio-code](https://github.com/markosamuli/ansible-visual-studio-code)
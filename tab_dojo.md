---
title: dojo
displaytext: Dojo
layout:  null
tab: true
order: 2
tags: samuraiwtf
---

## Samurai-Dojo


Samurai-Dojo is a set of vulnerable web applications created by and for the Samurai security training and testing distributions like SamuraiSTFU and SamuraiWTF.  These vulnerable applications include:

- Dojo Basic:  A simple PHP app that can be used for demos and exercises
- Dojo Scavenger:  A student CTF-like challenge to test pentesting skills

### Vagrant
For ease of development a Vagrant configuration are available.  The Vagrant configuration and deployment are stored in the following files:
* `Vagrantfile` : contains a standard Vagrant config (no plugins required)
* `bootstrap.sh` : contains the installation script to get Samurai-Dojo up and running on Apache

## Development

The SamuraiWTF project team is currently rewriting dojo-basic.  This effort is to
modify the project codebase to be a complete modern application.  It is being worked on 
in the [dojo-basic-2](https://github.com/SamuraiWTF/dojo-basic-2) repo.

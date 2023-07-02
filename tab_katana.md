---
title: katana
displaytext: Katana
layout:  null
tab: true
order: 1
tags: samuraiwtf
---

# Katana
Katana is the package management tool and interface for SamuraiWTF 5.0+. Specifically Katana is intended to be used by instructors to set up a classroom lab that
will be distrubuted to their students, or by self-study students to install the tools and targets they desire to use.

_IMPORTANT NOTES:_
* _Katana runs as root. It is intended only to be used in a temporary classroom environment. Don't install it on any network that is important to you._
* _Katana is installed as part of the [SamuraiWTF Distribution](https://github.com/SamuraiWTF/samuraiwtf) and is not intended to be installed or run on a
  non-SamuraiWTF build._


## Using Katana
There are two ways to use Katana:

### Using Katana with the Web  User Interface
By default, Katana should be running at `http://katana.wtf` from within your SamuraiWTF environment. Simply visit the Katana URL from any web browser inside the
environment. From the. GUI you will be able to install, stop, and start any of the Katana-defined tools and targets. Note that an internet connection is required to
install tools and targets.

### Using Katana from the Command Line
From a command line terminal inside your SamuraiWTF environment, simply type katana and the desired arguments. Katana supports the following arguments:

| Argument | Description |
| :------------- | ------------- |
| `list` | List all available modules that are currently supported by Katana. |
| `install <name>` | Install the supplied module by name. |
| `remove <name>` | Remove the supplied module by name. |
| `start <name>` | Start the supplied module, assuming it is startable. |
| `stop <name>` | Stop the supplied module, assuming it is stopable. |
| `status <name>` | Output the status of the supplied module. This will include whether or not it is installed and if it is running (if it is runnable). |
| `lock` | Lock the current set of modules. This will require a restart of Katana. |
| `--update` | This is a special argument for updating katana to the latest version from this repo. For development purposes, an optional second parameter to pull from a specific branch.  |

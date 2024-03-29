# **Loops, conditions and parsing**
## About Bash projects

Unless stated, all your projects will be auto-corrected with Ubuntu 20.04 LTS.
# Background Context

[![Bash](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/6/b07e3333b1edfb9beed5.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220623%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220623T200127Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=52d2de02b8ee7168408092a5363744cc1144bb8bbbe5443505d6cd9fe62c981e)](https://youtu.be/BC2neyc5GcI)

# **Resources**

## Read or watch:

* [Loops sample](https://intranet.hbtn.io/rltoken/XnVjFM8a1W4RfRu4TCPY-g)
* [Variable assignment and arithmetic](https://intranet.hbtn.io/rltoken/IM0Gv6VPzwAmqzlJxETZkw)
* [Comparison operators](https://intranet.hbtn.io/rltoken/K3E6xI9-goDM-93vsjCpPA)
* [File test operators](https://intranet.hbtn.io/rltoken/0OZLLDT28KrRZdid-l6hwg)
* [Make your scripts portable](https://intranet.hbtn.io/rltoken/Dyrnap2UC-LrzrmCOJRx8A)

## man or help:

* env
* cut
* for
* while
* until
* if

## General

* How to create SSH keys
* What is the advantage of using #!/usr/bin/env bash over #!/bin/bash
* How to use while, until and for loops
* How to use if, else, elif and case condition statements
* How to use the cut command
* What are files and other comparison operators, and how to use them

# **Requirements**
## General

* Allowed editors: vi, vim, emacs
* All your files will be interpreted on Ubuntu 20.04 LTS
* All your files should end with a new line
* A README.md file, at the root of the folder of the project, is mandatory
* All your Bash script files must be executable
* You are not allowed to use awk
* Your Bash script must pass Shellcheck (version 0.7.0) without any error
* The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
* The second line of all your Bash scripts should be a comment explaining what is the script doing

# **More Info**
## **Shellcheck**

[Shellcheck](https://intranet.hbtn.io/rltoken/E7Pr2zeM3cdY5-C0HKwtbw) is a tool that will help you write proper Bash scripts. It will make recommendations on your syntax and semantics and provide advice on edge cases that you might not have thought about. *Shellcheck* is your friend! **All your Bash scripts must pass Shellcheck without any error or you will not get any points on the task.**

Shellcheck is available on the school’s computers. If you want to use it on your own computer, here is how to [install it](https://intranet.hbtn.io/rltoken/SOX0HZTMgzHbcxrvU1X4hw).

Examples:

Not passing ***Shellcheck***:

![Not Passing](https://github.com/Robert-octavo/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/img/Vxotqyj.png)

Passing ***Shellcheck***:

![Passing](https://github.com/Robert-octavo/holberton-system_engineering-devops/blob/main/0x04-loops_conditions_and_parsing/img/ubHWxDU.png)

For every feedback, Shellcheck will provide a code that you can use to get more information about the issue, for example for code SC2034, you can browse https://github.com/koalaman/shellcheck/wiki/SC2034.
# Overview
This is a quick and dirty example of how to use Packer and Ansible to create Docker images.
No more Docker files!

# Prerequisites
* a working [Packer](https://www.packer.io/) installation
* a working [Ansible](https://www.ansible.com/) installation

# Building
Type `./build.sh` to build the image and export it as a tar file.

# Installation
Noting gets installed.

# Tips and Tricks

Use `tar tvf image.tar | less` to examine the contents of the image.  You should see a JDK installed in
`/tmp`/

# Troubleshooting

# License and Credits
This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

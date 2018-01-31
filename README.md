# Docker on Power

A simple script that automates the installation and configuration of Docker for ppc64le. That's all!

To execute it, ensure you are logged as #root, then just execute ./install_docker.sh. 

You can allow an user to run Docker without sudo by executing the following commands:

# Add Docker group
groupadd docker

# Add current user as member of the Docker group
usermod -aG docker $USER


Reboot when the installation is completed.

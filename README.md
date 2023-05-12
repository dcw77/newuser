# newuser



sudo useradd -s /bin/bash -d /home/healthchk/ -m -G sudo healthchk
sudo passwd healthchk
sudo echo 'healthchk ALL=(ALL) NOPASSWD: ALL' > /etc/sudoers.d/healthchk

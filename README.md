Instructions
============
1.) Ubuntu Server 16.04

#!/bin/bash

apt -y update

apt -y install ruby

apt -y install wget

cd /home/ubuntu

wget https://aws-codedeploy-us-west-2.s3.amazonaws.com/latest/install

chmod +x ./install

./install auto
# Udacity-Linux-Server-Configuration

## Description
This project is a part of FSND offered by Udacity. It's the last project, and it involves deploying a previous project in the Nanodegree to a linux server (Apache) using Lightsail or any other service of your choice.

## App's and Grader's Information
IP Address: 18.224.158.93
Port: 2200
URL: http://ec2-18-224-158-93.us-east-2.compute.amazonaws.com/?_sm_au_=iVVB2nqMs3064JSQ

The commmand to connect to the server: `ssh -i .ssh/udacity.rsa grader@18.224.158.93 -p 2200`

## Summary of Software Installed and Changes
- In Lightsail, create a Linux instance, then download the key (.pem) file that comes with it.
- To make the key file secure, run chmod 600 [path to the key]
- To ssh into your remote server, run `ssh -i [path to the key] ubuntu@[public ip]`
- Install the needed software tools, including python modules used in the flask application.
- Upgrade the packages by running `sudo apt-get update && sudo apt-get upgrade &&
  sudo apt-gedist-upgrade`.
- Make the necessary modifications.


## Third-party Resources
- https://askubuntu.com/
- https://httpd.apache.org/docs-project/
- https://stackoverflow.com/

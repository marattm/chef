# Script

## 1. Get the Vagrantfile
```
curl http://learnchef.s3.amazonaws.com/Vagrantfile > Vagrantfile
```

## 2. Start the Virtual Machine
```
vagrant up
echo 192.168.33.199 chef-automate.test | sudo tee -a /etc/hosts #
```
https://chef-automate.test/

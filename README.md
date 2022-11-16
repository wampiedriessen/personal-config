# Personal Config
Launched as an ansible-pull thingymabob

## Installing
On a fresh Ubuntu installation run this:
```
sudo apt update && sudo apt upgrade && sudo apt install python3 python3-pip; pip3 install ansible;

# pip adds stuff to profile in order to find executables
source ~/.profile

ansible-pull -U https://github.com/wampiedriessen/personal-config.git -i localhost, config.yaml
```

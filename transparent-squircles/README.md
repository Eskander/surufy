# Surufy

*NOTE: DEPRECATED:* Yaru theme no longer have squircle icons.

## How to install
First install the dependencies
```
sudo apt install libmagickwand-dev
sudo pip3 install Wand colorthief
```
Then proceed with downloading the necessary files
```
sudo mkdir /usr/lib/surufy
sudo wget https://raw.githubusercontent.com/eskander/surufy/master/transparent-squircles/surufy.py -O /usr/lib/surufy/surufy.py
sudo wget https://raw.githubusercontent.com/eskander/surufy/master/92surufy -O /etc/apt/apt.conf.d/92surufy
```
And finally
```
sudo python3 /usr/lib/surufy/surufy.py
```

## How to remove
```
sudo rm -rf /etc/apt/apt.conf.d/92surufy /usr/lib/surufy ~/.local/share/icons/Yaru
```

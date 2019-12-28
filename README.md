# ubuntu practical operation
practical operation ubuntu 18.4, 16

## configuration bluetooth casque audio like bose
* install
```
  sudo apt-get install pulseaudio-module-bluetooth
```
* load
```
  pactl load-module module-bluetooth-discover
  source ~/.bashrc 
```
* ref: [makandracards](https://makandracards.com/makandra/47024-how-to-pair-a-bose-quiet-comfort-35-with-your-ubuntu-computer)

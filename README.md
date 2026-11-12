# Unitree Go 2
This is a repo for some scripts to control the Unitree Go 2 dog in floor pi.

## Setup
Make sure you're running python and have installed the python package `unitree_webrtc_connect`.

```sh
pip install unitree_webrtc_connect==2.0.3
```

## Controlling the Dog
You'll need to make sure the dog is in AP mode. This will get it to emit a wifi hotspot. The password for the wifi hotspot is the same as the password for the dog's account. Connect your computer to the wifi hotspot then run the scripts:

```sh
python ./src/play_mp3.py
```
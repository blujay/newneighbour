# Gorba (Uprooted)

![uprooted-inverted](https://user-images.githubusercontent.com/1101918/192806408-1235c124-f8f6-42df-aff8-e1966859f3d1.png)

## Story 
https://docs.google.com/document/d/1odMaYnIsCr9xT7w8lf1RdEppcVUIiUZvxR8cYVfWTM0/edit

## Presentation
https://www.canva.com/design/DAFM3GhyVJw/N9jeUAzH-P4_yOvN4Wn1LA/view?utm_content=DAFM3GhyVJw&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink

## Video trailer
https://www.youtube.com/watch?v=KSfRa1DVg-I

## VR setup

You can run an instance of this project in Unity yourself if you like. 
Follow these instructions to install Oculus Integration as well as Photon Pun 2. 

This template comes pre-configured with Universal Render Pipeline (URP), Multiplayer Quest Template, settings configuration and Holoncore. You will then need to install some packages. I'm using Unity version 2020 (LTS)

- Clone this repository (I find Github desktop fairly easy) https://desktop.github.com/
- Add project to Unity Hub (set to Android from Dropdown) https://unity.com/download
- Open Unity project

## Oculus & Sidequest
- Set up your Oculus ecosystem and sidequest https://sidequestvr.com/setup-howto
- Download and import Oculus Integration Unity Package (it's big) https://developer.oculus.com/downloads/package/unity-integration/


## Multiplayer
- Download Photon Pun 2 and Open in Unity > Import into project https://assetstore.unity.com/packages/tools/network/pun-2-free-119922
- Download Photon Voice 2 import into project https://assetstore.unity.com/packages/tools/audio/photon-voice-2-130518

- Create a new Photon account Pun app in Photon Dashboard https://www.photonengine.com/
- Copy Photon Pun App ID into the Photon server settings
- Update project material to URP shaders as they may appear magenta 

# Testing multiplayer setup
You will need to connect your Quest at this point.

- Save Unity Project (settings might not be saved otherwise)
- RESTART UNITY (seems to make a difference when things seem weird)
- Press Play on editor - you should see the test room after brief ‘connecting’ message



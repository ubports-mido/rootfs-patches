This repo contains patches that may be added to add/fix features (This repo is experimental and not affiliated with the official patches 
from UBports foundation)

Details:

Patch1 : This patch is for adding flashlight feature. This is a temporary fix and is not the proper fix for enabling flashlight globally.
This app creates an app in the home screen which runs a shell script for toggling the flashlight and thus flashlight can only be toggled with
this app

Patch2 : This patch is for fixing media decoding in the mediaplayer app, in addition to this the user must install gstreamer1.0-libav for 
installing the media decoding library

Instructions :

1) Extract the rootfs and cd into it, then run git-apply <Path to patch>
2) Compress the rootfs back and use  

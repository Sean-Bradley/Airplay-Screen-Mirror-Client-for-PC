# CBoxClient_Demo.exe
## Support System
* Windows XP
* Windows 7
* Windows 8
* Windows 10
## Feature
* Send PC Screen to receiver--"ScreenRenderDemo.apk"
* Auto Find receiver
* Support two screen while the pc has two display devices
* Support BJCast
* Support Hardware Encoder
* Support pin


# bjcast_receiver_demo_windows.rar
## Support System
* Windows XP
* Windows 7
* Windows 8
* Windows 10
## Feature
* bjcast receiver
* just support video in this demo (cursor and audio display support in sdk)

# 
# ScreenShare_pin.apk
## Support System
* Android 5.0+
## Feature
* Send Android Screen(Mirror) to receiver--"ScreenRenderDemo.apk"
* Auto Find receiver
* Support BJCast
* Support pin
# 
# ScreenRenderDemo_pin.apk
## Support System
* Android 4.0+
* PAD/phone/TV Box
## Feature
* Play Screen(Mirror) from sender--"BoxClient_Demo.exe/ScreenShare.apk"
* Play airplay mirror from iphone/ipad/mac
* Support BJCast
* Support Airplay
* Support Pin
# 
# airplay_demo_linux.zip
## Support System
* x86_64 linux(test in centos 7.1)
## Feature
* Airplay Mirror Receiver
* Record Mirror Streamer to video.h264 file.you can play this file with ffplay:
  ffplay video.h264 
* Record audio pcm data to file audio_44100_2_s16.pcm.you can play this file with ffplay:
  ffplay -f s16le  -channel_layout 3 -channels 2  -ar 44100 audio_44100_2_s16.pcm
## Note:
* we use mdns lib to suppot zeroconf in this demo.so you must stop avahi-daemon first.

# 
# airplay_mirror_receiver_demo_windows.rar
## Support System
* Windows XP
* Windows 7
* Windows 8
* Windows 10
## Feature
* Airplay Mirror Receiver
## install
please install BonjourPSSetup.exe first , then it would auto start 'Bonjour Service'
run run.bat to enjoy the airplay
# 
# License
* Free but has some limits
* maybe disconnect after mirroring 5-10min
* 1/3 probability maybe coredump while start airplay mirror
* Time intervals between multiple screens/mirrors are required
#
# QQ群技术交流
* 582349005

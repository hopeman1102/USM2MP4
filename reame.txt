- usm -> mp4
Run VGMtoolbox
Go to Misc->Stream Tools->Video Demultiplexer
Drop USM files
Run cmd: >ffmpeg -i example.m2v example.adx example.mp4

- mp4 -> usm
Run cmd: >ffmpeg -i example.mp4 audio.wav example%04d.tga
Run Scaleform exe and import first tga file and select audio then click Encode button.
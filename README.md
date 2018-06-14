Extract frames as an image from video files using FFMPEG
=======
In this repository, an example given to extract a frame as an image for each second of given video file using a python script that uses FFMPEG tool.

## Installing FFMPEG for Ubuntu 14.04
Firstly, you need to install the "libav-tools" package:
```
$ sudo apt-get install libav-tools
```

Then, install FFMPEG by using PPA:
```
$ sudo add-apt-repository ppa:mc3man/trusty-media
$ sudo apt-get update
$ sudo apt-get install ffmpeg gstreamer0.10-ffmpeg
```

Run the "get_frames.py" script with input and fps arguments as in below.
```
$ python get_frames.py -i data/videos/Smurf_Coloured_Glasses.mp4 -f 1
```

References
------
- https://medium.com/@alibugra/extract-frames-as-an-image-from-video-files-using-ffmpeg-65b52d3d97db

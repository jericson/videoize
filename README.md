# Videoize

This is just a placeholder for a script I plan to write to turn a podcast into a video for uploading to YouTube.

I'm using:
```
ffmpeg -r 1/5 -loop 1 -i image.jpg -i original.mp4  -c:v libx264  -vf "pad=ceil(iw/2)*2:ceil(ih/2)*2" -shortest with_video.mp4
```

I'm pretty sure this came from [this question](https://stackoverflow.com/questions/24961127/how-to-create-a-video-from-images-with-ffmpeg) and [this documentation](https://trac.ffmpeg.org/wiki/Slideshow).


A simple script for removing video watermark, using iopaint.  
Made this to use myself, but as it seems to work okay, I upload this.  
Only tested at NVIDIA windows environment.

Instructions:

Download files, at release tab, or code ZIP, or git clone, whatever.  
Run iopaint.  
Place "video.mp4" and "mask.png" in this folder, then double click to run "run.bat".  
("mask.png" is an image which has black background and white masking)  

If not working, pls check requirements below.

-- Requirements --

> iopaint must be running at 8080 port.

> Python3 must be installed. (Maybe you will automatically satisfy this requirement if you're running iopaint)

> No matter what is the original extension of the video, video file name must be "video.mp4".

> "mask.png" must be the exact same resolution with video file.

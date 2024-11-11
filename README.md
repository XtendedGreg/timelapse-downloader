# timelapse-downloader
Timelapse Recorder on Raspberry Pi 5 with NVME and FFMPEG

As seen on the XtendedGreg Youtube Channel stream: https://www.youtube.com/live/BK5nzT3SaUw

## Description
This is used to download a jpeg image from a URL every second, and then at the end of every hour, it will make an MP4 using those images.

## Applications
This is good for making timelapse from 
	- Security cameras
	- Screen captures
	- Anything else where a URL image will be updated automatically and can be downloaded

## Features
Some of the features of this script is that it is 
	- easy to install and configure
	- the output is H.265 MP4s
	- Files are organized in a folder structure by date and time 
	- automatically deletes the oldest files when the drive is full
	- can be securely accessed remotely using SFTP or SMB share
	
In this case we are going to record to an NVME drive using the Pi 5, but any solid state drive should suffice.

## Installation
Installation instructions are located in the root folder

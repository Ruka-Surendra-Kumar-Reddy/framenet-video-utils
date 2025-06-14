# FrameNet Video Utils

A simple Python utility to get video file details like duration, resolution, and frame rate.

This is an open-source tool developed and maintained by the team at [FrameNet.ai](https://framenet.ai), the AI-powered platform that makes video editing effortless.

## Installation

Install the package directly from PyPI:

```bash
pip install framenet-video-utils

Usage
The library provides one primary function, get_video_details(). It takes the path to a video file and returns a dictionary containing the video's properties. It returns None if the file cannot be processed.

from framenet_video_utils import get_video_details

# Get details from a local video file
details = get_video_details("path/to/my_video.mp4")

# The function returns a dictionary or None if it fails
if details:
    print(f"Resolution: {details['width']}x{details['height']}")
    print(f"Duration: {details['duration']} seconds")
    print(f"Frame Rate: {details['fps']} fps")
else:
    print("Could not retrieve video details.")

About FrameNet.ai
FrameNet.ai is a comprehensive suite of AI tools designed to simplify and automate your video creation workflow, from text-to-video generation to automatic subtitling.

➡️ Learn more about the FrameNet.ai platform

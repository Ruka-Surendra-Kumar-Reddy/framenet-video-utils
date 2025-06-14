# FrameNet Video Utils

[![PyPI package](https://badge.fury.io/py/framenet-video-utils.svg)](https://badge.fury.io/py/framenet-video-utils)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A simple Python utility to get video file details like duration, resolution, and frame rate.

This is an open-source tool developed and maintained by the team at **[FrameNet.ai](https://www.framenet.ai)**, the AI-powered platform that makes video editing effortless.

---

## Installation

Install the package directly from PyPI:

```bash
pip install framenet-video-utils
Usage
The library provides one primary function, get_video_details(). It takes the path to a video file and returns a dictionary containing the video's properties. It returns None if the file cannot be processed.

python
Copy
Edit
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


# CAPTURE-VIDEO-FRAME

PYTHON PROJECT FOR CAPTURING VIDEO FRAME

## Overview

CAPTURE-VIDEO-FRAME is a Python class designed to capture frames from a video file using the OpenCV library. This program reads a video file and saves each frame as a JPEG image in a specified directory.

## Installation

To use this program, you need to have Python and the required libraries installed. Follow the instructions below to set up your environment.

### Requirements

1. Python 3.x
2. OpenCV

### Steps to Install

1. Clone the repository or download the script.

```sh
git clone https://github.com/Dhruviba/CAPTURE-VIDEO-FRAME.git
```

2. Install the required libraries using pip:

```sh
pip install -r requirements.txt
```

### Usage

- Ensure you have a video file ready to process.
- Run the script from the command line:

```sh
python capture_video_frames.py path_to_video_file
```

- Replace path_to_video_file with the actual path to your video file.

### Output

- The frames from the video will be saved in a directory named captured_frames. Each frame will be saved as a JPEG file named framenumber.jpg, where number is the frame number starting from 0.

## Example

```sh
python capture_video_frames.py sample_video.mp4
```

This will create a directory called **captured_frames** and save the frames as *frame0.jpg*, *frame1.jpg*, and so on.

## ⚠️ Additional Notes

- Ensure that you have write permissions for the directory where the frames will be saved.
- If the directory captured_frames already exists, it will be deleted and recreated, so any existing data in that directory will be lost.

## Author
<img alt="View Dhruviba's full-sized avatar" src="https://avatars.githubusercontent.com/u/172467090?v=4" width="100" height="100" style="border-radius: 50%;" >

## Contributors
<a href="https://github.com/Dhruviba/CAPTURE-VIDEO-FRAME/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=Dhruviba/CAPTURE-VIDEO-FRAME" />
</a>

# CAPTURE-VIDEO-FRAME

## Overview

**CAPTURE-VIDEO-FRAME** is a Python class designed to capture frames from a video file using the OpenCV library. This program reads a video file and saves each frame as a JPEG image in a user-specified directory.

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

## Usage

- Ensure you have a video file ready to process.
- Run the script from the command line:

    ```sh
    python capture_video_frames.py path_to_video_file
    ```

- Replace `path_to_video_file` with the actual path to your video file.
- You will be prompted to provide a name for the output folder. Make sure to choose a unique name that does not already exist.

## Output

- The frames from the video will be saved in the directory you specified during the prompt.
- Each frame will be saved as a JPEG file named `frame<frame_number>.jpg`, where `<frame_number>` starts from 0.

## Example

```sh
python capture_video_frames.py sample_video.mp4
```

- This will prompt you to name your output folder.
- The frames will then be saved in the specified directory as frame0.jpg, frame1.jpg, and so on


## ⚠️ Additional Notes

- Ensure that you have write permissions for the directory where the frames will be saved.
- If the directory you specified already exists, you will be asked to provide a unique name.

## Author
<img alt="View Dhruviba's full-sized avatar" src="https://avatars.githubusercontent.com/u/172467090?v=4" width="100" height="100" style="border-radius: 50%;" >

## Contributors
<a href="https://github.com/Dhruviba/CAPTURE-VIDEO-FRAME/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=Dhruviba/CAPTURE-VIDEO-FRAME" />
</a>

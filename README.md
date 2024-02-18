
# Computer Vision Assignment
## Basketball Detection and Analysis:

This repository contains a computer vision pipeline for detecting basketballs, counting the number of dribbles, and estimating the position of players in basketball videos. The project utilizes OpenCV for basketball detection and MediaPipe for player tracking and dribble counting.

## Features:
### Basketball Detection:
* Utilizes OpenCV's object detection techniques to identify basketballs within a video frame.
* Implements techniques like color thresholding, contour detection, and morphology operations to accurately locate basketballs.
### Dribble Counting:
* Employs basic loigc along with math function and uses the y co-ordinates of the basketball to determine the number of dribbles
* Counts the number of dribbles performed by each player in the video.
### Player Position Estimation:
* Uses MediaPipe's pose estimation models to estimate the position of players within the frame.
* Provides coordinates or bounding boxes indicating the location of players relative to the basketball.

## Usage

Clone this repo:

```bash
  https://github.com/prxbhu/Computer-Vision-Assignment.git
  cd my-project
  cd Computer-Vision-Assignment
```
Install Dependencies:

```bash
  pip install -r requirements.txt
```
## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)



# Video & Audio Processing

## Overview

This project was developed as part of the Media Informatics
course at the German International University (GIU).

The project explores digital multimedia processing through
video and audio manipulation using Python, OpenCV, MoviePy,
and an online audio editing tool.

It focuses on video frame extraction, color space conversion,
chroma subsampling, motion detection, audio extraction,
and audio filtering.

## Project Objectives

- Extract individual frames from digital videos.
- Convert video frames from RGB to YCbCr color space.
- Implement 4:2:2 chroma subsampling.
- Analyze luminance and chrominance components.
- Detect motion using frame differencing.
- Extract audio tracks from video files.
- Apply and analyze audio effects.
- Explore practical multimedia processing techniques.

## Project Phases

### Phase 1: Video Frame Extraction

Extracted the first six frames from an MP4 video
for individual processing and analysis.

Key features:

- Video file processing
- Frame extraction
- Individual frame visualization

### Phase 2: Chroma Subsampling (4:2:2)

Converted extracted video frames from RGB to YCbCr
color space and implemented 4:2:2 chroma subsampling.

The three color components were displayed and analyzed:

- Y: Luminance component
- Cb: Blue-difference chrominance component
- Cr: Red-difference chrominance component

The components were compared before and after subsampling
to examine how color information can be reduced while
preserving luminance information.

### Phase 3: Motion Detection

Implemented motion detection using frame differencing
to identify movement between consecutive video frames.

The processing workflow included:

1. Reading consecutive video frames.
2. Converting frames to grayscale.
3. Calculating pixel-level differences.
4. Applying thresholding.
5. Identifying moving regions.
6. Saving the processed output video.

### Phase 4: Audio Extraction

Used MoviePy to extract the original audio soundtrack
from the input video.

This phase explored the separation of audio and visual
components from multimedia files.

### Phase 5: Audio Filtering and Manipulation

Applied audio effects using an online sound editing tool.

The experiments included:

- Pitch adjustment
- Amplitude adjustment
- Audio filtering
- Analysis of changes in sound characteristics

The resulting audio clips were examined to understand
how different effects influence the original soundtrack.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| OpenCV | Video and frame processing |
| MoviePy | Audio extraction from video |
| Online Audio Editing Tool | Audio filtering and effects |

## Key Concepts Applied

- Digital Multimedia Processing
- Digital Video Processing
- Digital Audio Processing
- Computer Vision
- Frame Extraction
- RGB and YCbCr Color Spaces
- Chroma Subsampling (4:2:2)
- Grayscale Conversion
- Frame Differencing
- Motion Detection
- Image Thresholding
- Audio Extraction
- Pitch and Amplitude Adjustment

## Project Outcomes

The project demonstrates practical techniques for
processing, analyzing, and manipulating visual and
auditory data.

It explores how multimedia components can be extracted,
transformed, and analyzed using programming and digital
media processing tools.

## Skills Developed

- Python Programming
- Computer Vision
- Video Processing
- Audio Processing
- Multimedia Processing
- Motion Detection
- Problem Solving

## Project Information

- University: German International University (GIU)
- Course: Media Informatics
- Duration: April 2024
- Project Type: Academic Project
- Programming Language: Python

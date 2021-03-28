# WhatThePreview

> Generate a few preview images for a video

## Setup

* Install `ffmpeg`
* Clone the repository


## Usage

The generated previews are saved into `previews/<name_of_the_video>`:

```
# Syntax
./generate-previews <name_of_the_video> <previews_amount>

# Example
# Extract 30 previews from the video 20210320_NERDDISCO.mp4
./generate-previews 20210320_NERDDISCO.mp4 30
```
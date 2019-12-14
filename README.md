# mp4-to-avi-converter

### Description

Convert `.mp4` file folder to `.avi` file folder.

**Important note:** Some AV readers cannot read new `.avi` format. Please note that this converter will convert to the old `.avi` format that generally all AV readers can process. Video files in `.avi` is still supported by modern media players though.

### Installation

1. [Python](https://www.python.org/downloads/) 2.7 or 3.6 is recommended.

2. Download [FFmpeg](https://ffmpeg.org/) and add `/path-to-ffmpeg/bin/` to your path environment variable.

### Run

1. Put all your `.mp4` files into a folder. This folder is called `origin` folder.

2. Prepare a `destination` folder.

3. Run `cmd` from this repository location and run

```
python converter.py {path-to-origin-folder} {path-to-destination-folder}
```

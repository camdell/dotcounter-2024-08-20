# Dot Counter

**Desciption**

This repository contains code to count brightly colored dots in an image.
Most image files are supported, including `.jpg`, `.png`.

## Example Usage/Documentation

To count dots and print out their counts by color, you can use:

```sh
python circount.py images/dots.jpg
# No. of red      circles detected = 10
# No. of green    circles detected = 39
# No. of yellow   circles detected = 31
```

To count dots, print out their counts by color, and visually inspect
what dots were classified as specific colors you can:

```sh
python circount.py images/dots.jpg --show
# No. of red      circles detected = 10
# No. of green    circles detected = 39
# No. of yellow   circles detected = 31

# Note: an image should pop up on your screen, backed by a Matplotlib GUI.
```

## Dependencies

This program has been tested to work with Python 3.12.4- no other versions
have been tested.

This program requires NumPy, SciPy, opencv2, and Matplotlib.
For versions of these programs, please see the `requirements.txt` file.

## Installation


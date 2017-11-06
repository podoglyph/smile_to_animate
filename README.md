# Smile to Animate

Smile to Animate is a simple project designed to run an animation when you smile. Using an open source smile detector from OpenCV, the app will open and play an animation when the camera sees you smile!

## Getting Started

Clone this repo.

### Prerequisites

This app was developed in Python 3 on a Mac. It is recommended to use a virtual environment when installing Python packages on your system.

The main dependency is `opencv-python`. Install it using your favorite package manager.

You'll also need to use your own animation. Download a video into the root directory and edit `line 29` of `smile.py` accordingly. Most video formats should work, but I've only tested `.mov`, `.avi` and `.mp4`.

To use an external (USB) camera, edit the argument in `line 30` from `0` to `1`.

### Installing

To start the app, from the project root:
`python smile.py`

Once loaded, just smile!

To quit, just press 'q'.

## License

This project is licensed under the MIT License.

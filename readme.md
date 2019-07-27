# Docker OpenCV

![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/hdgigante/opencv.svg) ![Docker Pulls](https://img.shields.io/docker/pulls/hdgigante/opencv.svg)

## Components

- [OpenCV](https://github.com/opencv/opencv) and [contrib](https://github.com/opencv/opencv_contrib)
- Tesseract
- and opencv image dependencies

## Images

| dist | lang | opencv | image | size
| :--- | :--- | :--- | :--- | :--- |
| fedora 30 | python 3 | 3.4.7 | hdgigante/opencv:fedora-python3-opencv3 | ![MicroBadger Size (tag)](https://img.shields.io/microbadger/image-size/hdgigante/opencv/fedora-python3-opencv3.svg)
| fedora 30 | python 3 | 4.1.1 | hdgigante/opencv:fedora-python3-opencv4 | ![MicroBadger Size (tag)](https://img.shields.io/microbadger/image-size/hdgigante/opencv/fedora-python3-opencv4.svg)
| alpine 3.10 | python 3 | 3.4.7 | hdgigante/opencv:alpine-python3-opencv3 | ![MicroBadger Size (tag)](https://img.shields.io/microbadger/image-size/hdgigante/opencv/alpine-python3-opencv3.svg)
| alpine 3.10 | python 3 | 4.1.1 | hdgigante/opencv:alpine-python3-opencv4 | ![MicroBadger Size (tag)](https://img.shields.io/microbadger/image-size/hdgigante/opencv/alpine-python3-opencv4.svg)


## Usage

```bash
$ docker pull hdgigante/opencv:fedora-python3-opencv3
$ docker pull hdgigante/opencv:fedora-python3-opencv4
$ docker pull hdgigante/opencv:alpine-python3-opencv3
$ docker pull hdgigante/opencv:alpine-python3-opencv4
```

## Credits

Based on...

- [OpenCV tutorial](https://docs.opencv.org/trunk/dd/dd5/tutorial_py_setup_in_fedora.html)

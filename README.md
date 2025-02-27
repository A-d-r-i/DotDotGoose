# DotDotGoose
DotDotGoose is a free, open source tool to assist with manually counting objects in images.

![Screen Shot](doc/source/example.png)

*Point data collected with DotDotGoose will be very valuable training and validation data for any future efforts with computer assisted counting*



## Installation

### Dependencies
DotDotGoose is being developed on Ubuntu 20.04 with the following libraries:

* PyQt6 (6.3.1)
* Pillow (9.2.0)
* Numpy (1.23.1)

```bash
python3 -m venv ddg-env
source ddg-env/bin/activate
python -m pip install --upgrade pip
python -m pip install pillow
python -m pip install numpy
python -m pip install PyQt6
```

## Launching DotDotGoose

```bash
git clone https://github.com/persts/DotDotGoose
cd DotDotGoose
python3 main.py
```

## Executables

Don't want to install from scratch? [Download DotDotGoose and start counting!](https://biodiversityinformatics.amnh.org/open_source/dotdotgoose/)
# Sign Wave

Sign Wave is a sign language recognition system built using Python and Tkinter. It utilizes machine learning classifiers and computer vision to detect and interpret hand gestures in real time.

---

## Project Overview

This project captures sign language gestures, preprocesses the data, trains a classifier, and provides an interactive GUI for recognition. It aims to improve accessibility by bridging communication gaps for the hearing impaired.

---

## Features

- Real-time gesture capture using webcam
- Dataset creation and preprocessing with `create_dataset.py` and `collect_imgs.py`
- Machine learning classification using trained models (`train_classifier.py`, `inference_classifier.py`)
- Interactive GUI built with Tkinter (`gui.py`)
- Uses pickled data for efficient storage (`data.pickle`, `model.p`)
- User-friendly interface with custom buttons and frames (`assets/`, `button_1.png`, `entry_1.png`, `signwave_logo.png`)

---

## Installation

1. Clone the repository:


git clone https://github.com/AbhishekKhond005/signwave.git
cd signwave
Install dependencies:

## Installation

1. Clone the repository:

```
git clone https://github.com/AbhishekKhond005/signwave.git
cd signwave
```

2. Install dependencies:
```
pip install -r requirements.txt

# Vehicle-Counter

## Overview

The Vehicle Counter is a simple yet powerful Python-based project designed for counting vehicles in a video stream or input video file. It utilizes computer vision techniques to detect and track vehicles, providing valuable insights into traffic patterns and vehicle flow.

## Features

> **Vehicle Detection:** Utilizes object detection algorithms to identify and locate vehicles within a video stream.

> **Counting Mechanism:** Accurately counts the number of vehicles passing through the specified region of interest.

> **Compatibility:** Works with both live video streams and pre-recorded video files.

> **Easy to Use:** Simple setup and configuration make it accessible for users with varying levels of technical expertise.

> **Customizable Parameters:** Adjustable parameters allow users to fine-tune the detection and counting process based on their specific requirements.

# Getting Started

### Prerequisites

> Python 3.x

> OpenCV

> NumPy

## Installation

**Clone the repository:**


```bash
git clone https://github.com/HimanshuGitCode/Vechile-Counter.git
```

**Install dependencies:**

```bash
pip install -r requirements.txt
```


## Usage

**Navigate to the project directory:**

```bash
cd Vechile-Counter
```

**Run the vehicle_counter.py script:**

```bash
python vehicle_counter.py

```

**Follow on-screen instructions to specify the input source (live stream or video file) and adjust parameters as needed**

# Configuration

The project provides a config.yaml file where users can customize various parameters such as detection threshold, region of interest, and video source.

```bash
# Example Configuration
detection_threshold: 0.5
region_of_interest:
  top: 100
  bottom: 400
video_source: "path/to/your/video.mp4"
```




## Contributing

Contributions are welcome! If you find a bug or have an enhancement in mind, feel free to open an issue or submit a pull request.

Please make sure to update tests as appropriate.




## License

[MIT](https://choosealicense.com/licenses/mit/)


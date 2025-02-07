# Object Tracking Application

![header_mots](https://github.com/user-attachments/assets/5b488311-0c3f-49ce-9e97-4fa165fed050)
This application tracks moving objects in a video using OpenCV and Streamlit. It uses the MOG2 background subtractor to detect moving objects and draws a green rectangle around them.

## Features

- Upload a video file in formats: mp4, avi, mov, wmv
- Detects moving objects using MOG2 background subtractor
- Draws a green rectangle around detected objects

## Requirements

- streamlit
- opencv-python-headless
- numpy

## Installation

1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd <project-directory>
   ```
3. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```
2. This App deployed on streamlit cloud.
3. Upload a video file and see the object tracking in action. [Here](https://objecttrackingprojectroute.streamlit.app/)

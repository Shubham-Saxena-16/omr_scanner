# OpenCV-Hacks-for-Educators-Build-a-Time-Saving-OMR-Scanner-in-Python
Drowning in test papers?  OpenCV Hacks for Educators offers a lifeline!  This guide equips you with the power of OpenCV, a free and powerful computer vision library.  Learn to code your own OMR scanner in Python, automating the grading of multiple-choice tests and reclaiming your evenings (and weekends!).

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Preprocesses scanned images to reduce noise and detect edges.
- Identifies the OMR sheet region within the image.
- Locates individual bubbles on the sheet.
- Maps marked bubbles to answer keys to calculate scores.
- Provides visual feedback on the processed OMR sheet, highlighting correct and incorrect answers.
- Handles multiple OMR sheets in one run.
- Configurable parameters via command-line arguments or a configuration file.
- Option to load the answer key from an external file (e.g., JSON or CSV).
- Develop a GUI for uploading OMR sheets, specifying answer keys, and viewing results interactively.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Imutils

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/omr-scanner.git
   cd omr-scanner

Install the required Python packages

pip install opencv-python numpy imutils

## Usage

Place your scanned OMR sheet images in the project directory.
Update the image_path variable in the script to point to your OMR sheet image.

Run the script:
 python omr_scanner.py

## Example 
# Load and preprocess the image
image_path = r"path_to_your_omr_sheet.png"
image = cv2.imread(image_path)
# ... rest of the code

## Project Structure 
omr-scanner/
├── omr_scanner.ipynb       # Main script for OMR scanning and grading
├── README.md            # Project README file
├── requirements.txt     # List of required packages
└── omr.pnj              # To store OMR sheet images

## Feedback and Contributions 
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes. You can also open an issue to discuss any changes or enhancements.

## License
This project is licensed under the MIT License. See the LICENSE file for details. 

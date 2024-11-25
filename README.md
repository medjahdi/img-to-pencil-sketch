# Img to Pencil Sketch

A Python project that converts images into pencil sketches using OpenCV.

## Description

This project takes an image as input and applies a series of transformations using OpenCV to convert it into a pencil sketch. It's useful for anyone looking to apply an artistic filter to their images.

## Installation

### Prerequisites

Make sure you have Python installed. You will also need the following Python packages:

- `opencv-python`
- `opencv-contrib-python`

You can install these dependencies using `pip`. If you don't have them installed already, run the following command:

```bash
pip install opencv-python opencv-contrib-python
```

### Cloning the Project

You can clone the project using Git, or simply download the ZIP file from the repository.

To clone the project, run:

```bash
git clone https://github.com/medjahdi/img-to-pencil-sketch.git
```

## Usage

Run the script using Python:

```bash
python main.py
```

When prompted, either drag and drop an image file into the terminal or manually enter the full path to the image.

The program will generate a pencil sketch of the image and save it to a specified local path. You can choose the location by entering it when prompted.

### Example

```bash
Drag and drop the picture here or write its path manually: C:\Users\iAt™\OneDrive\Bureau\pic.jpg
```

You will also be prompted to enter the local path where you'd like to save the resulting sketch. For example:

```bash
Enter the path to save the sketch (e.g., C:\Users\iAt™\OneDrive\Bureau\results\sketch_image.png):
```

The resulting pencil sketch will be saved at the specified location.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit pull requests with improvements or bug fixes.

### Note
Make sure to create the `results` directory or specify an existing directory path where you want to save the sketches before running the script.

This documentation now reflects the changes to allow users to specify a local path for saving the resulting sketches. If you need further modifications, let me know!

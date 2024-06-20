# ResNet Border Detection

This project utilizes the ResNet architecture for the task of border making and detection. The implementation focuses on detecting and marking borders in images.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project leverages the powerful ResNet model to perform border detection on images. By using the deep learning capabilities of ResNet, we aim to achieve high accuracy in identifying and marking borders.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/resnet-border-detection.git
    cd resnet-border-detection
    ```

2. Create a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To use the ResNet border detection model, follow these steps:

1. Place your images in the `input` directory.

2. Run the detection script:
    ```bash
    python detect_borders.py
    ```

3. The output images with detected borders will be saved in the `output` directory.

## Results

Example results of the border detection can be found in the `examples` directory. The following image showcases the detection capabilities of the ResNet model:

![Example Result](examples/result.png)

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

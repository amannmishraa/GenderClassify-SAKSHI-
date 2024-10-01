# Gender Classification Model

This repository contains a machine learning model for gender classification using facial images. The model is trained on the [Gender Classification Dataset](https://www.kaggle.com/datasets/cashutosh/gender-classification-dataset) from Kaggle.
App Interface can be accessed from this URL: (https://www.figma.com/proto/VOcY81587sfLKDOYEAkbSx/App-interface?node-id=74-38&node-type=canvas&t=si87nhfXhPxyu8Yw-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=74%3A38&show-proto-sidebar=1)

## Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [Gradio Interface](#gradio-interface)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

- Python 3.7+
- pip

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/amannmishraa/GenderClassify-SAKSHI.git
   cd GenderClassify-Sakshi
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Dataset

The model uses the Gender Classification Dataset from Kaggle. To use this dataset:

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/cashutosh/gender-classification-dataset)
2. Extract the downloaded zip file
3. Place the extracted `Training` and `Validation` folders in the `data` directory of this project

## Usage

1. Ensure you have downloaded and placed the dataset as described in the [Dataset](#dataset) section.

2. Run the training script:
   ```
   python train_model.py
   ```

3. After training, you can use the model for predictions:
   ```
   python predict.py path/to/your/image.jpg
   ```

## Gradio Interface

We provide a Gradio interface for easy interaction with the model. To launch the interface:

1. Ensure you have trained the model or downloaded a pre-trained model.

2. Run the Gradio script:
   ```
   python gradio_interface.py
   ```

3. Open your web browser and navigate to the URL provided in the terminal (usually `http://localhost:7860`).

4. Upload an image through the interface to get the gender classification prediction.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

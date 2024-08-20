# Plant Disease Detection

This project aims to detect plant diseases using machine learning models. The project includes a trained model, a web application for user interaction, and necessary scripts for data processing and model training.

## Description

The Plant Disease Detection project uses a Convolutional Neural Network (CNN) model to classify and detect diseases in plants. The model is trained on a dataset of plant images and can identify various diseases based on the input image.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/dahalroshish2/Plant-Disease-Detection.git
    cd Plant-Disease-Detection
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Ensure you have the correct Python version:
    ```bash
    pyenv install $(cat .python-version)
    pyenv local $(cat .python-version)
    ```

## Usage

1. Run the web application:
    ```bash
    python app.py
    ```

2. Open your web browser and go to `http://localhost:5000`.

3. Upload an image of a plant leaf to detect the disease.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code follows the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- [TensorFlow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [Flask](https://flask.palletsprojects.com/)
- [GitHub LFS](https://git-lfs.github.com/)


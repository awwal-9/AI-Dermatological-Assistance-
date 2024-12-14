# AI-Dermatological-Assistance-
This Project discusses the development of an AI-based tool using Convolutional Neural Networks (CNNs) for the diagnosis of various skin conditions. It includes details about the dataset used (HAM10000), the methodology for training the model.

# AI Dermatological Assistance

This project provides an AI-based tool for the diagnosis of skin conditions using Convolutional Neural Networks (CNNs). The tool classifies skin lesions such as melanoma, basal cell carcinoma, and benign lesions. It is trained on the **HAM10000** dataset and provides real-time diagnostic results through a user-friendly interface built with **Gradio**.

## Features
- **AI Classification**: Uses CNNs for skin lesion analysis.
- **Pretrained Models**: Implemented **MobileNet-V2** and **Inception V3** for efficient and accurate classification.
- **User Interface**: Created a real-time web interface using **Gradio** for easy interaction.
- **Dataset**: Trained on the **HAM10000** dermatology image dataset containing over 10,000 images.

## Requirements
To run this project, you'll need the following Python packages:
- **TensorFlow** for machine learning models.
- **Gradio** for the web interface.
- **NumPy** for numerical operations.
- **OpenCV** for image processing.

# Run the application:
python app.py

Open the provided URL in your browser to upload skin lesion images and get real-time diagnoses.


## Dataset

The project uses the HAM10000 dataset, which is available for academic use and includes various skin lesion images. 
You can access the dataset here.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements

HAM10000 dataset: For providing the dataset used for training.

TensorFlow: For building and training the CNN model.

Gradio: For creating the interactive user interface.

## Future Work

Expanding the model to classify more types of skin conditions.

Implementing deeper and more complex CNN architectures for higher accuracy.

Integrating the tool into a mobile application for easier access to dermatological diagnoses.

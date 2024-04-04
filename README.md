# Siamese Neural Network for Face Recognition

This project implements a Siamese Neural Network model for face recognition. The model has been designed, trained, and tested following the steps outlined in a YouTube video (reference provided). The provided Jupyter Notebook (.ipynb) file contains the detailed steps followed in the video and the implementation of the Siamese Neural Network.

#### Note :-

Please read the last section of this file for details of issues faced while making this project. That section is dedicated so that other people working on it don't have to invest time to tackle those issues.


## Reference

The design, training, and testing of the Siamese Neural Network model have been referenced from a YouTube video. Please refer to the video for a detailed explanation of the implementation.

Build a Deep Facial Recognition App from Paper to Code Link : [Click here ](https://www.youtube.com/watch?v=bK_k7eebGgc&list=PLgNJO2hghbmhHuhURAGbe6KWpiYZt0AMH&pp=iAQB)

## Libraries Used

- cv2 (OpenCV): For image processing tasks.
- os: For interacting with the operating system.
- random: For generating random numbers.
- numpy: For numerical computations.
- matplotlib: For plotting graphs and visualizations.
- tensorflow: For building and training neural networks.
- tensorflow.keras: High-level neural networks API for building and training models.
- tensorflow.keras.metrics: For evaluating model performance metrics.

## Installation

1. Clone or download the repository.
2. Open the provided Jupyter Notebook file in a compatible environment (e.g., Jupyter Notebook, Google Colab).
3. Follow the steps outlined in the notebook to train and test the Siamese Neural Network model.

## Usage

1. Ensure that you have the necessary libraries installed (listed in the "Libraries Used" section).
2. Open the Jupyter Notebook file and execute each cell in sequential order to replicate the implementation steps.
3. Customize the model parameters, dataset paths, and other configurations as needed for your specific use case.
4. Train the Siamese Neural Network model on your dataset.
5. Evaluate the model performance using appropriate metrics.
6. Use the trained model for face recognition tasks as per your requirements.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please feel free to fork the repository and create a pull request.

## Acknowledgments

Special thanks to the creator of the YouTube video for providing valuable insights and guidance on implementing the Siamese Neural Network model for face recognition.

## Future Scope

I am a Computer Engineering student currectly exploring various domains for interest. Originally my aim was to make my own face recognition model and convert it to a tflite model and use it a mobile application I've created previously (Can be seen available on my GitHub repo).

### Issues faced and solution

Following are couple of issues that I personally faced while making this project and solutions to avoid them.

- While making this project would recommend to create a new enviorment in Jupyter Notebook (Many youtube video available showing how to do so).
- Also download all required libraries via command line of the enviorment to avoid errors while writing the code.
- Would Highly not recommend to run the training epochs (It is a step training the model ) on cpu, use gpu instead.
- How to setup gpu configurations on Jupyter is not shown in the youtube video mentioned. Many references of how to run python on gpu is available on youtube.
- First of all download CUDA from Nvidia website (would sugget to follow any good youtube video). The real challenge is to get your Jupyter notebook codes to run on gpu (On a personal note took me 3-4 hrs to find a proper solution). Use [Link](https://www.youtube.com/watch?v=7KN9q31OXBs). Would highly suggest to install libraries files via conda command line instead of using the UI for downloading libraries.

These were the few hickups I faced while making this project. Others might face someother issues would suggest to find solutions using google(Stackoverflow), youtube or AI like ChatGPT (wouldn't suggest to use AI as they could be unreliable in certain situations.)


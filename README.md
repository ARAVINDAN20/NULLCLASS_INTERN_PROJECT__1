# NULLCLASS_INTERN_PROJECT__1
# Animal Emotion Classifier

This Python application uses a trained deep learning model to classify emotions (Angry, Sad, Happy) of animals from uploaded images. It provides a GUI interface built with Tkinter for easy interaction.

## Features
![image](https://github.com/ARAVINDAN20/NULLCLASS_INTERN_PROJECT__1/assets/116174602/6df6d2e4-a37f-4e34-b648-efec0fc12128)
![image](https://github.com/ARAVINDAN20/NULLCLASS_INTERN_PROJECT__1/assets/116174602/c0de048a-2989-4823-87c3-95705cc75e06)

![image](https://github.com/ARAVINDAN20/NULLCLASS_INTERN_PROJECT__1/assets/116174602/61e010e6-25b6-4a57-957d-bafbda263fb3)
- **Upload Image**: Allows users to select an animal image for emotion classification.
- **Detect Emotion**: Performs emotion classification on the uploaded image.
- **Display Result**: Shows the predicted emotion of the animal.

## Setup and Installation

### Prerequisites

- Python 3.x
- Required Python packages:
  - `tkinter`
  - `PIL (Pillow)`
  - `numpy`
  - `opencv-python`
  - `tensorflow`

### Installing Dependencies

Install the required packages using pip:

```sh
pip install tkinter Pillow numpy opencv-python tensorflow
```

### Model Training

Before running the GUI application, ensure you have trained the model to generate `pets_detection.keras`.

Open and run `animal_emotion-detection.ipynb` notebook to train the model and save `pets_detection.keras`.
Train this model with this data set link https://www.kaggle.com/datasets/anshtanwar/pets-facial-expression-dataset
use kaggle notebook to train

## Download the pre-trained models from the provided links and place them in the appropriate directories:
[pets_detection.keras](https://drive.google.com/file/d/1cFAbG8Oyb8_PDprmtaiFAQgqWZDwOQfc/view?usp=sharing)

### Directory Structure

Ensure your project directory looks something like this after training the model:

```bash
NULLCLASS_INTERN_PROJECT__1/
  - animal_emotion-detection.ipynb   # Jupyter notebook for model training
  - animal_emotion_gui.py            # GUI application script
  - pets_detection.keras             # Trained model file (generated after training)
  - README.md                        # Readme file (you are here!)
  - LICENSE                          # License file
```

## Usage

1. Clone this repository:

```sh
git clone https://github.com/ARAVINDAN20/NULLCLASS_INTERN_PROJECT__1.git
cd NULLCLASS_INTERN_PROJECT__1
```

2. Run the GUI application:

```sh
python animal_emotion_gui.py
```

3. Upload an animal image using the "Upload Image" button.
4. Click "Detect Emotion" to classify the uploaded image.
5. The predicted emotion will be displayed.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- TensorFlow/Keras for deep learning model support.
- OpenCV and PIL libraries for image processing.
- Tkinter for building the GUI interface.

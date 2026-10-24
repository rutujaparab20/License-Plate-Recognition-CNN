# License Plate Recognition System using CNN

A college mini-project that detects vehicle license plates and recognizes their alphanumeric characters using image processing and a Convolutional Neural Network (CNN).

## Project overview

The project workflow includes:
1. Detecting the license plate region using OpenCV's Haar Cascade classifier.
2. Preprocessing the cropped plate using grayscale conversion, thresholding, erosion, and dilation.
3. Segmenting individual characters using contours.
4. Classifying characters with a CNN built using TensorFlow/Keras.

## Technologies used

- Python
- OpenCV
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

## Files in this repository

- `LPD_notebook.ipynb` — project notebook and implementation.
- `Mini_Project_Report.pdf` — college mini-project report.

## Dataset availability

The original dataset used during college development is no longer available with the project owner, so it is **not included** in this repository. The notebook also contains Google Drive paths that refer to the original dataset and classifier file. These paths must be updated before running the complete workflow.

To retrain the CNN, provide your own compatible character-image dataset arranged in training and validation folders, and update the paths in the notebook. You may also need to provide a compatible Haar Cascade XML file.

## How to run

1. Download or clone this repository.
2. Open `LPD_notebook.ipynb` in Jupyter Notebook or Google Colab.
3. Install the required libraries.
4. Update the dataset and Haar Cascade file paths in the notebook.
5. Run the cells in order. Training requires a compatible dataset; the notebook will not run end-to-end without it.

Example installation:

```bash
pip install opencv-python tensorflow numpy matplotlib scikit-learn
```

## Reported project results

The college report describes testing on 15 vehicle images:
- License plates detected: 15 out of 15.
- License plate numbers correctly recognized: 12 out of 15.
- Reported recognition accuracy: 80%.

These are the results reported in the project report, not an independently reproduced benchmark.

## Limitations

- The original dataset is not included.
- The notebook uses machine-specific Google Drive paths that need to be changed.
- Performance may vary with image quality, lighting, plate angle, and character segmentation.
- The results should be re-evaluated if the model is retrained on a different dataset.

## Academic project and credits

This was a group mini-project completed at Sindhudurg Shikshan Prasarak Mandal's College of Engineering, Kankavli, during 2024–25. The submitted report lists Tejal V. Gawade, Rutuja S. Parab, and Tejasvi R. Parab as project authors, with Prof. D. P. Mhapasekar as guide.

Please retain the group credits and follow any college or dataset licensing requirements when sharing this project publicly.

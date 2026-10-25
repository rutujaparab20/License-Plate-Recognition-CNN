# 🚘 License Plate Recognition System using CNN

A computer vision project that detects vehicle license plates and recognizes alphanumeric characters using Python, OpenCV, and a Convolutional Neural Network (CNN).

## 📌 Project Overview

The License Plate Recognition System identifies a vehicle's number plate from an image and recognizes the characters present on it.

The project uses image processing techniques to detect the license plate, isolate individual characters, and classify them using a CNN model.

## 🎯 Objectives

- Detect vehicle license plates from images.
- Preprocess and isolate the license plate region.
- Segment individual characters from the plate.
- Recognize letters and digits using a CNN model.
- Display the detected plate and recognition output.

## 🛠️ Technologies Used

- Python
- OpenCV
- TensorFlow / Keras
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

## ⚙️ Project Workflow

1. **Input Image:** Load a vehicle image.
2. **License Plate Detection:** Detect the plate region using OpenCV Haar Cascade.
3. **Image Preprocessing:** Convert the image to grayscale and apply thresholding and morphological operations.
4. **Character Segmentation:** Extract individual characters using contours.
5. **Character Recognition:** Use a CNN model to classify the extracted letters and digits.
6. **Output:** Display the detected plate and recognized characters.

## 📸 Project Output

The following screenshots show the different stages of the project.

### 1. Original Vehicle Image

![Original Vehicle Image](car%20image_01.png)

### 2. Detected License Plate

![Detected License Plate](Detected%20number%20plate%20region_03.png)

### 3. Isolated License Plate Region

![Isolated License Plate](Isolated%20license%20plate%20region_04.png)

### 4. Character Segmentation

![Segmented Characters](Segmented%20Characters_05.png)

### 5. Isolated Characters

![Isolated Characters](Isolated%20characters%20from%20plate_06.png)

### 6. Final Character Recognition

![Final Recognition](Final%20recognized%20license%20plate_07.png)

### 7. Input Image for Recognition

![Input Image](Input%20image%20for%20license%20plate%20recognition_02.png)

## 📊 Reported Results

According to our college project report:

- Test images: 15
- License plates detected: 15 out of 15
- Plate numbers correctly recognized: 12 out of 15
- Reported recognition accuracy: 80%

These are the results documented in the college report and have not been independently re-evaluated.

## 📂 Project Files

- `LPD_notebook.ipynb` — Jupyter Notebook containing the project implementation.
- `Mini_Project_Report.pdf` — College project report.
- `requirements.txt` — Python library requirements.
- Output images — Visual examples of detection, segmentation, and recognition.

## 💻 Installation

Install the required Python libraries:

```bash
pip install opencv-python tensorflow numpy matplotlib scikit-learn jupyter
```

## ▶️ How to Run

1. Clone or download this repository.
2. Open `LPD_notebook.ipynb` in Jupyter Notebook or Google Colab.
3. Install the required libraries.
4. Update the dataset, model, and Haar Cascade paths in the notebook.
5. Run the notebook cells in order.

**Note:** The original dataset used during development is no longer available with the project owner. You will need a compatible dataset to retrain the model, and the notebook's original file paths must be updated.

## ⚠️ Limitations

- The original training dataset is not included.
- Machine-specific paths may require modification.
- Recognition performance may vary with lighting, image quality, plate angle, and character segmentation.

## 👥 Academic Project and Credits

This group mini-project was completed at Sindhudurg Shikshan Prasarak Mandal's College of Engineering, Kankavli, during 2024–25.

**Project Authors:**
- Tejal V. Gawade
- Rutuja S. Parab
- Tejasvi R. Parab

**Project Guide:** Prof. D. P. Mhapasekar

## 👩‍💻 Author

**Rutuja Santosh Parab**

GitHub: [rutujaparab20](https://github.com/rutujaparab20)

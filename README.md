# MiDaS Depth Estimation Model
![Cover Image](https://github.com/Brianhulela/MiDaS_depth_estimation/blob/master/cover_image.jpg)

This repository contains code to run the MiDaS Depth Estimation model locally. MiDaS (Monocular Depth Estimation via a Multi-Scale Network) predicts the depth of objects in an image, which can be useful for various computer vision tasks.

## Article

For a detailed guide on running the MiDaS Depth Estimation Model, refer to my Medium article [here](https://medium.com/@brianhulela/run-the-midas-depth-estimation-model-locally-in-3-steps-b715c0ae000e) where I walk you through the process.

## Setup Instructions

### 1. Create a Python Environment

Open your terminal and create a virtual environment with the command:

```
python -m venv env
```

Activate the virtual environment:

- On Windows:
  ```
  .\env\Scripts\activate
  ```

- On Mac/Linux:
  ```
  source env/bin/activate
  ```

### 2. Install the Required Libraries

With your virtual environment activated, install the necessary libraries using:

```
pip install -r requirements.txt
```

Alternatively, you can manually install the required libraries:

```
pip install timm opencv-python matplotlib
```

### 3. Run the Code

Use the following Python script to perform depth estimation using the MiDaS model and visualize the results:

- Download an image from the internet using `urllib`.
- Select the model type you want to use (e.g., "MiDaS_small").
- Load the model and transformations.
- Read and preprocess the image using `cv2`.
- Run the depth estimation model and get the depth map.
- Display the depth map using `matplotlib`.

## References

- MiDaS GitHub Page: [MiDaS GitHub Page](https://github.com/isl-org/MiDaS)
- Google Colab Notebook: [Link to Colab Notebook](https://colab.research.google.com/github/pytorch/pytorch.github.io/blob/master/assets/hub/intelisl_midas_v2.ipynb)
- Medium Article: [Link to Medium Article](https://medium.com/@brianhulela/run-the-midas-depth-estimation-model-locally-in-3-steps-b715c0ae000e)

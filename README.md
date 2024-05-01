# Acne-Detection-And-Removal

Computer Vision Final Project Repository

## Problem Statement

One of the most common skin conditions, acne, affects most people at some point in their lives. But in the present era, society values having healthy, attractive skin, thus many individuals utilise various applications/filters to digitally erase pimples from their photos before sharing them on social media. Thus, we have used computer vision techniques to create a pipeline that helps detect and remove acne from their photographs. To achieve this, several techniques have been used, such as thresholding, masking, blurring, etc.

## Dataset

We’ve used the Custom Dataset for this project. The dataset contains facial images and their corresponding masks are available. It consists of 30 images and corresponding acne masks.
The Dataset and its related files are available in the [Google Drive](https://drive.google.com/drive/folders/1oGuYy11tp83f16bV4O3QGkSU1QnjcIsO?usp=sharing)

## Code

All the required code is in the [Colab File](https://github.com/VinayN18/Acne-Detection-And-Removal/blob/main/B21AI023_B21CS031_B21CS045_B21CS063.ipynb)

We can run all the cells in the colab file with copying the dataset from the given drive link to the desired location (for not changing any code) or any desired location and importing it accordingly.

## Results
### 1) Input Image
![Image2](https://github.com/VinayN18/Acne-Detection-And-Removal/assets/114673422/e0f98c37-134c-4a33-be55-4e2068257bf9)

### 2) Image With Generated Mask (Mask shown is generated from the best method out of two methods)
![Image-with-mask](https://github.com/VinayN18/Acne-Detection-And-Removal/assets/114673422/af0900a9-2981-4712-87b8-038cf654c9c8)

### 3) Acne Removal 

#### --> Method 1 (OpenCV Integrated Painting)
![Final-Image-using-Opencv](https://github.com/VinayN18/Acne-Detection-And-Removal/assets/114673422/d8402885-d92c-457d-8d12-6b5b307f6b7b)


#### --> Method 2 (Deep Image Prior - Using UNet CNN Model)
![Final-image-using-Unet](https://github.com/VinayN18/Acne-Detection-And-Removal/assets/114673422/1e2ae742-0ab1-4a1d-a996-99cede6ee974)

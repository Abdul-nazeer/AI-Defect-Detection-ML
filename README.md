# Casting Defect Detection
## Based on data from Kaggle

This system can detect any defect in casting process based on data.
## Database
The database has been taken from kaggle, based on data provided
by Ravirajsinh Dabhi. It contains 6633 training images and 715 testing images.
The images have been distributed into two classes - def_front (defective)
and ok_front(OK).
The images have already been preprocessed into 300x300 grayscale resolution.

You can find the database on this [link](https://www.kaggle.com/ravirajsinh45/real-life-industrial-dataset-of-casting-product).


## Tech

- Python - Google Colab/Jupyter Notebook
- Pandas library
- Numpy library
- Keras library

## Data Augmentation
- rotation_range
- width_shift_range
- height_shift_range
- shear_range
- zoom_range
- horizontal_flip
- vertical_flip
- brightness_range
- rescale
- validation_split

## Models Used

- Convolutional Neural Network
-- Conv2D(filters = 16)
-- MaxPooling2D
-- Conv2D(filters = 32)
-- MaxPooling2D
-- Flatten
-- Dense(128)
-- Dropout(0.2)
-- Dense(64)
-- Dropout(0.2)
-- Dense(1)

#### Model summary
![image](https://user-images.githubusercontent.com/58364032/135392668-310c41db-c423-4eae-ae35-5f555dff8df2.png)

#### Training Evaluation
![image](https://user-images.githubusercontent.com/58364032/135392762-b8edbc12-f1a5-4a53-ad87-0e8f24596f01.png)

Happy predictions!!!

Also, feel free to contact me via email (kulshreshthabhinav@gmail.com) if you have any suggestions for the model or you find a model better than this.

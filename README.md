# Classifying Wildfire Presence in Images: DS4002 Data Divas Project 3
## Software and Platforms:
We used Python to run the majority of our code in Jupyter Notebooks in either Google Colab or virtually using Rivanna. Platform varied by group member, so we used both Mac and Windows. In order to use Python in the most efficient manner, we used the following additional packages imported with this code: numpy, os, seaborn, matplotlib.pyplot, keras, tensorflow, zipfile, and requests.

## Documentation Map: <br>![Sitemap Whiteboard in Green Purple Basic Style-4](https://github.com/user-attachments/assets/8f60223b-3cb2-4f3b-bcd2-2788b083158f)




## How to Reproduce our Results:
* **Step 1: Data Collection** <br>
Download the image dataset containing fire/nofire images from Digital Commons Data ([https://data.mendeley.com/datasets/gjmr63rz2r/1](url)). After accessing all of the data and perusing the technical appendix, save the subsetted dataset (fire_data_subsetted.zip).
* **Step 2: Exploratory Data Analysis & Cleaning** <br>
Use SCRIPTS/EDA to ensure all the images have the same dimesnions and to combine the subsetted test/train data back into one dataset. Use the same file to output visualizations such as sample images, hue distributions, and more to gain a deeper understanding of the data that you are working with.
* **Step 3: Train Convolutional Neural Network** <br>
Use SCRIPTS/Keras_training.ipynb to import the data, run data augmentation, build the model, and train it. We used an 80-10-10 training, validation, testing split and 15 epochs. 
* **Step 4: Evaluate our Model** <br>
Use the same file SCRIPTS/Keras_training.ipynb to evaluate the model's performance on the test set, as well as output some graphs about its accuracy over epochs and classification performance. 
* **Step 5: Conclusions** <br>
Summarize findings and assess the accuracy and utility of the trained model to determine whether a forest landscape is experiencing a fire or not.
Determine future applications for this model.

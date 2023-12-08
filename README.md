# CycleGAN_winter_to_fall
A model that converts fall images to winter and vice versa.

# Where to find data?
Hello! How are you doing?
Dataset is about 900 winter and 900 fall images collected by scraping of websites like Pixabay.
In this task, Beautifull soup is used to scrape images. There are two zip files which are train and test images
of winter and fall.

# What does this model?
This model converts winter images to fall and vice versa. The training has been done for only 20 epochs,
which took about 3 hours in google colab with GPU.
The model is cycle consistent generative adversial neural network.
(Originally this model has been used to convert horse images to zebra images)
Here you can find some of the pictures that has been converted using this model:
![image](https://github.com/ravankhidirov/CycleGAN_winter_to_fall/assets/112794999/154ce5d9-c174-4540-84bc-7479dfa017f7)
# .
![image](https://github.com/ravankhidirov/CycleGAN_winter_to_fall/assets/112794999/e3b79ea3-7722-4924-921f-ba80b128d844)

# How to use this model.
We have provided the dataset collected by web scraping. Addidtionally, we have saved our updated generators and discriminators.
These can be downloaded and used as in LoadingSavedWeightsAndBiases.ipynb file.
Datasets are in zip format. You can download and add them to your drive.After that the code will work in google colab.

# Contributors
I would like to give special thanks to Tural (https://github.com/tu0ral). We worked together while building the model, training, and finding dataset.




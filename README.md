# Image Captioning Using Deep Learning algorithms
### By Ahmed Amine MAJDOUBI

In this project we will be tackeling the problem of generating image captions. So we will be mainly using  image and text processing algorithms. This is a very interesting area of deep learning where humans excel at, which is compressing huge amount of images to just a few descriptive phrases. In this project, we will be using the ***'flickr30k_images'*** dataset along with a csv file containing reference captions.

We will start by performing a descriptive analysis of our data (both the images and the caption phrases), then we will proceed by writting out the problem we will be solving. The next step is to create our own algorithm to generate captions, and train it on our training dataset. Then we will define a specific accuracy metric to evaluate our model on the test dataset. Finaly we will perform a qualitative analysis of our results, and end the notebook with a conclusion on our work.

---

**Important Note:** If you want to run this notebook, you should do it using **Google Collaboration** service. Also you need to have a directory in your drive named **'Features'** to store the features that we will be creating, and another one inside it named **'models'** to store the deep learning models we will create. You also need to have a folder named **'flickr30k_images'** that contains the 'results.csv' file and another folder with the name **'flickr30k_images'** that contains all the **flickr30k** images. Here is the structure of the files in my drive:


*  ***/content/drive***

  *   Path to your '*flickr30k_images*' folder (for me, it's ***students-share/Projet***)
      * ***/flickr30k_images***
          * *Results.csv*
          * ***/flickr30k_images*** (this folder contains all the **flickr30k** images)
  *   Path to your '*Features*' folder (for me, it's ***/My Drive***)
        * ***/Features***
            * ***/models***
            
You can get the first **flickr30k_images** folder from this **[*link*](https://www.kaggle.com/hsankesara/flickr-image-dataset/version/1)** and the '**Results.csv**' file from **[my github](https://github.com/Mjidiba97/Image-Captioning/blob/master/results.csv)**.

# Images-color-compression-using-clustering
This project will be about manually implementing the K-means algorithm and using it for image compression.
* Starting with a sample dataset that will help us gain an intuition of how the K-means algorithm works. 
* After that, we will use the K-means algorithm for image compression by reducing the number of colors that occur in an image to only those that are most common in that image.

## Results Visualization:
![Screenshot (289)](https://github.com/Sameer-13/Images-color-compression-using-clustering/assets/106761486/b6a6e12b-c321-49cf-b86b-dac213451554)

## Getting Started:
1. use the following command to clone the repository:
   
   ```$ git clone https://github.com/Sameer-13/Images-color-compression-using-clustering.git```
2. Download your image in the images folder then go to section 4 and type your photo name here instead of bird_small.png:
   ```original_img = plt.imread('images/bird_small.png')```

**Note:** In Preprocessing step in 4.1, If you'll try this project later on a JPG file, you first need to divide the pixel values by 255 so it will be in the range 0 to 1. This is not necessary for PNG files (e.g. `bird_small.png`) because it is already loaded in the required range (as mentioned in the [plt.imread() documentation](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.imread.html)). I commented a line below for this so you can just uncomment it later in case you want to try a different file.*

3. Run the code and it will generate an color-compressed version of your image

## Author:
Sameer Alsabei(Sameer-13) [Github](https://github.com/Sameer-13) [Twitter](https://mobile.twitter.com/Sameer_Alsabei)

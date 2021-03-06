[//]: # (Image References)

[image1]: ./my_images/example_brittany.PNG "Example Output: Brittany"
[image2]: ./my_images/example_cat.PNG "Example Output: Cat"


## Dog Classification Project

Given an image of a dog, this algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.  


![Sample Output: Brittany][image1]

If supplied an image of something other than a dog or a human, the algorithm will know that, too:

![Sample Output: Cat][image2]


### Instructions

1. The dog dataset can be downloaded [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). You should then extract it to `path/to/dog-project/dogImages`. 

2. The human dataset can be downloaded [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip). You should then extract it at location `path/to/dog-project/lfw`. 

3. Finally, download the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset and place it to `path/to/dog-project/bottleneck_features`.

4. You can now run the Jupyter notebook [dog_app.ipynb](./dog_app.ipynb) and train the model! 


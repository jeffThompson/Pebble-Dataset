![A section of the pebble dataset, sorted by visual similarity](https://raw.githubusercontent.com/jeffThompson/Pebble-Dataset/master/HeaderImage.jpg)

# PEBBLE DATASET

> "Hoard and praise the verity of gravel./Gems for the undeluded. Milt of the earth."  
> — Seamus Heaney, *The Gravel Walks*, 1972

> "...we must always bear in mind that a pebble is a transient thing. It is th the half-way stage of a long existence. Beginning as a fragment of rock, which itself is millions of year old, it ends its existence by being pounded into minute particles or grains."  
> — Clarence Ellis, *Pebbles on the Beach*, 1954

In order to train a machine learning system to recognize an object, one needs lots and lots of examples to train it on. The [ImageNet dataset](https://en.wikipedia.org/wiki/ImageNet), a project started in 2009 at Princeton University, is now the defacto standard for training and testing object-detection systems. It contains hand-annotated URLs to 14-million images in 1000 categories, ranging from animals (dozens of different dog breeds and bird species) to everyday objects. Datasets abound across the internet, from massive sets of Tweets to videos of people performing household tasks.

If a neural network is a *system* wherein we do abstract work, a dataset is an *ecosystem* made up of things of and embedded in the world. (Or, in the [words of UC Berkely professor Alexei Efros](https://www.newyorker.com/magazine/2018/11/12/in-the-age-of-ai-is-seeing-still-believing): "data, data, data... the gunk, the dirt, the complexity of the world.") Of course, what we choose to gather data of, and subsequently train our networks on, creates a listing of the things we care about. We put our labor towards teaching computers to know the difference between 23 different kinds of terrier found in the ImageNet dataset, but what about the things we haven't yet compiled datasets of?

This project is a machine learning dataset consisting of 5000 images of pebbles gathered in Cambridge, England in the fall of 2018. Pebbles are literally cast-offs from something else, not the stone of buildings or triumphal sculptures but the thing left behind on the beach or after a glacier has moved through. A dataset of pebbles is a poetic addition to the overwhelmingly ultilitarian datasets that already exist.

<hr />

### CONTENTS

This project is made of up several parts:

* A dataset of images of 5000 pebbles  
    * The images have been color-corrected and centered checked by hand to ensure none are cut off or otherwise bad  
    * Also included are the extracted features of the dataset at 300 features (using the final fully-connected layer of Inception and PCA) and 2 features (using tSNE)  
* A large inkjet print of the pebbles in the dataset, sorted by visual similarity (a selection of which can be seen above – full version is in this repo)  
* A video showing the pebbles morphing one into another, which is not in the repo but can be seen here: [https://vimeo.com/301470836](https://vimeo.com/301470836)    
* A scanner calibration image, which includes color, gray, white, and black cards which were used to correct the pebble images  
* This Github repository, where the pebble images and related files are stored

<hr />

### LICENSE

In order to make this dataset as available as possible, all files in this repository are released under a [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/). You can use these files for anything, so long as you disclose the source, keep the license intact, and state any changes you've made. If you do something with this dataset, or would like to add to it, please let me know.


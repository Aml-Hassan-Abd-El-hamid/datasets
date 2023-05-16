# Datasets

I built this repo to store my dataset, I first used to keep my dataset on Kaggle, but after a while, I found that holding my dataset on GitHub is better and that's due to the fact that it's much easier to modify and maintain datasets than it's on Kaggle, also it's much easier to use GitHub datasets on google colab.

Here's the datasets available on that repo and some info on them.

## Cat Dataset 🐱

It contains 35 different cat breeds, the smallest class contains only 100 images and the largest class contains about 375 images.

I used this dataset in building my cat breed classifier website, I used 3 datasets to construct this dataset along with Google images.

I used all the classes from the Gano Cat Breed Image Collection except for the "Tuxedo" which isn't technically a breed, that was 14 classes. 

I used the Scottish fold class from the Cat Breed dataset. 

The rest of the 20 classes came from the Cat Breeds Dataset (Cleared), those 20 classes contained a lot of bad images - misclassified and low quality - and I cleaned them as much as I could manually, also I collected more data for the Selkirk Rex and Korat classes from Google images to make them at least 100 images.

After that I split the dataset into train and test, the test folders contains about 25% of the original dataset, and the train folders contain about 75% of the dataset

<b>Sources</b>:

 - Cat Breeds Dataset (Cleared): https://www.kaggle.com/datasets/denispotapov/cat-breeds-dataset-cleared <br>
- Gano Cat Breed Image Collection https://www.kaggle.com/datasets/shawngano/gano-cat-breed-image-collection <br>
- Cat Breed https://www.kaggle.com/datasets/solothok/cat-breed <br>
- Google Images

<b>Breeds</b> :

```
Abyssinian
American Curl
American Shorthair
Balinese
Bengal
Birman
Bombay
British Shorthair
Burmese
Cornish Rex
Devon Rex
Egyptian Mau
Exotic Shorthair
Extra-Toes Cat - Hemingway Polydactyl
Havana
Himalayan
Japanese Bobtail
Korat
Maine Coon
Manx
Nebelung
Norwegian Forest Cat
Oriental Short Hair
Persian
Ragdoll
Russian Blue
Scottish Fold
Selkirk Rex
Siamese
Siberian
Snowshoe
Sphynx
Tonkinese
Toyger tiger cat
Turkish Angora
```

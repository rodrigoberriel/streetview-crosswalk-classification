## Datasets

Three datasets are being released:

- IARA (daylight)
- IARA (night)
- GOPRO

Altogether, they have more than 35,000 images in ~40GB.

#### IARA (daylight)

The IARA dataset is named after the vehicle used to capture the images: the Intelligent Autonomous Robotic Automobile. IARA is an autonomous vehicle that is being developed in the High Performance Computing Lab (LCAD) of the Universidade Federal do Espírito Santo. The vehicle contains many sensors, but only one camera was used to record this dataset. The camera, a Bumblebee XB3, was mounted on the top of the car facing forward. This dataset was recorded during the day in a week-day, i.e. it contains usual traffic. In total, there are 12,441 images from 4 different sequences recorded in the capital of the Espírito Santo, Vitória.

![SamplesIARAdaylight](https://github.com/rodrigoberriel/streetview-crosswalk-classification/blob/master/images/samples-iara.png)

Download [here](https://drive.google.com/drive/folders/11ETzxerQnfDdxkOSvX9LWKyyxRoqT7Wr?usp=sharing). The images are in the four `.tar.gz` (images1, images2, images3, and images4) and the annotations in the `iara.txt` file.

#### IARA (night)

The sequence comprises 12,114 frames (in a temporal sequence) covering part of the IARA dataset and more (including a toll, a bridge, etc.) during the night.

![SamplesIARAnight](https://github.com/rodrigoberriel/streetview-crosswalk-classification/blob/master/images/samples-iara-night.png)

Download [here](https://drive.google.com/drive/folders/1cg0R5GpNBbtr2Sps8I6CUFrDRRseS-sr?usp=sharing). The images are in the `iara-night.tar.gz` and the annotations in the `iara-night.txt` file.

#### GOPRO

The GOPRO dataset comprises 11,070 images recorded in the city of Vitória, Vila Velha and Guarapari, Espírito Santo, Brazil. The videos were recorded using a GoPRO HERO 3 camera in Full HD (1920 × 1080 pixels) at 29.97 frames per second (FPS) in different days. Some of them were recorded in city roads and the others in the highways connecting these cities. The images are divided into 29 sequences. From them, 23 of them are short sequences (up to 15s) of a vehicle passing by crosswalks and the other 6 are longer sequences (up to 90 s) of a vehicle driving without any crosswalk in the field of view. The crosswalks in these sequences are presented in a variety of ways, such as with pedestrians, occluded by cars, painting fading away (i.e. aging), etc.

![SamplesGOPRO](https://github.com/rodrigoberriel/streetview-crosswalk-classification/blob/master/images/samples-gopro.png)

Download [here](https://drive.google.com/drive/folders/1x2FWpCpzv8TLwAGigRa3eEbWcvr3E5xT?usp=sharing). The images are in the `WITH_CROSSWALK.tar.gz` (the sequences that have at least one crosswalk) and `WITHOUT_CROSSWALK.tar.gz` (the sequences without any crosswalk); and the annotations in the `gopro.txt` file.

## Models

We're releasing two pre-trained models (the ones you could see in the videos):

- GSV-FA\*: the best out of the 10 models trained using fully-automatic dataset
- GSV-PA\*: the best out of the 10 models trained using partially-automatic dataset

You can find both models [here](https://drive.google.com/drive/folders/1dTFPQ8g2pA0M9G6zzOAYnboecqv4iUTE?usp=sharing). If the link is broken, feel free to send me an email or open an issue.

For each model, you'll find:
- Weights: `{model_name}.caffemodel`
- Mean: `mean.binaryproto` and `mean.jpg`
- Metadata: `{model_name}.metadata` (internal stuff, don't worry)

To test these models with your own data, you can follow the Python notebook provided [here](https://github.com/rodrigoberriel/streetview-crosswalk-classification/blob/master/inference/).
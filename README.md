# Automatic Large-Scale Data Acquisition via Crowdsourcing for Crosswalk Classification: A Deep Learning Approach

[Rodrigo F. Berriel](http://rodrigoberriel.com), Franco Schmidt Rossi, [Alberto F. de Souza](https://inf.ufes.br/~alberto), and [Thiago Oliveira-Santos](https://www.inf.ufes.br/~todsantos/home)

[Computers & Graphics](https://www.journals.elsevier.com/computers-and-graphics): [10.1016/J.CAG.2017.08.004](http://dx.doi.org/10.1016/J.CAG.2017.08.004)

[![Overview](https://github.com/rodrigoberriel/streetview-crosswalk-classification/blob/master/images/overview.png)](http://www.sciencedirect.com/science/article/pii/S0097849317301334)

Correctly identifying crosswalks is an essential task for the driving activity and mobility autonomy. Many crosswalk classification, detection and localization systems have been proposed in the literature over the years. These systems use different perspectives to tackle the crosswalk classification problem: satellite imagery, cockpit view (from the top of a car or behind the windshield), and pedestrian perspective. Most of the works in the literature are designed and evaluated using small and local datasets, i.e. datasets that present low diversity. Scaling to large datasets imposes a challenge for the annotation procedure. Moreover, there is still need for cross-database experiments in the literature because it is usually hard to collect the data in the same place and conditions of the final application. In this paper, we present a crosswalk classification system based on deep learning. For that, crowdsourcing platforms, such as OpenStreetMap and Google Street View, are exploited to enable automatic training via automatic acquisition and annotation of a large-scale database. Additionally, this work proposes a comparison study of models trained using fully-automatic data acquisition and annotation against models that were partially annotated. Cross-database experiments were also included in the experimentation to show that the proposed methods enable use with real world applications. Our results show that the model trained on the fully-automatic database achieved high overall accuracy (94.12%), and that a statistically significant improvement (to 96.30%) can be achieved by manually annotating a specific part of the database. Finally, the results of the cross-database experiments show that both models are robust to the many variations of image and scenarios, presenting a consistent behavior.

---

### Test with your own data
Pre-trained models are available [here](https://github.com/rodrigoberriel/streetview-crosswalk-classification/blob/master/models/).

This [Python notebook](https://github.com/rodrigoberriel/streetview-crosswalk-classification/blob/master/inference/) may help you with the inference process.


### Datasets
We are releasing three datasets: IARA (day and night) and GOPRO. The IARA datasets were recorded using the infrastructure of the IARA autonomous car (which we are developing in our lab), and the GOPRO dataset was recorded using a GOPRO camera attached to the windshield (close to the rear mirror). Altogether, these three datasets have more than 35,000 annotated images. More details can be found in the paper. Below, you can see some samples of the datasets and how to download each of them.

### IARA dataset


##### Daylight

Details and download [here](https://github.com/rodrigoberriel/streetview-crosswalk-classification/tree/master/datasets#iara-daylight).

![SamplesIARAdaylight](https://github.com/rodrigoberriel/streetview-crosswalk-classification/blob/master/images/samples-iara.png)

Results on the IARA dataset: [video](https://youtu.be/zrKU3duNwuo).

[![ResultsIARA](https://github.com/rodrigoberriel/streetview-crosswalk-classification/blob/master/images/youtube-iara.png)](https://youtu.be/zrKU3duNwuo)


##### Night

Details and download [here](https://github.com/rodrigoberriel/streetview-crosswalk-classification/tree/master/datasets#iara-night).

![SamplesIARAnight](https://github.com/rodrigoberriel/streetview-crosswalk-classification/blob/master/images/samples-iara-night.png)

Results on the NIGHT dataset: [video](https://youtu.be/afCBi1Pj1NE).

[![ResultsNIGHT](https://github.com/rodrigoberriel/streetview-crosswalk-classification/blob/master/images/youtube-iara-night.png)](https://youtu.be/afCBi1Pj1NE)


### GOPRO dataset

Details and download [here](https://github.com/rodrigoberriel/streetview-crosswalk-classification/tree/master/datasets#gopro).

![SamplesGOPRO](https://github.com/rodrigoberriel/streetview-crosswalk-classification/blob/master/images/samples-gopro.png)

Results on the GOPRO dataset: [video](https://youtu.be/jmYmQFiqY3c).

[![ResultsGOPRO](https://github.com/rodrigoberriel/streetview-crosswalk-classification/blob/master/images/youtube-gopro.png)](https://youtu.be/jmYmQFiqY3c)


#### BibTeX

If you find any of the datasets and/or our pre-trained models useful for your research, please cite the paper below.

    @article{berriel2017cag,
        Author  = {Rodrigo F. Berriel and Franco Schmidt Rossi and Alberto F. de Souza and Thiago Oliveira-Santos},
        Title   = {{Automatic Large-Scale Data Acquisition via Crowdsourcing for Crosswalk Classification: A Deep Learning Approach}},
        Journal = {Computers \& Graphics},
        Year    = {2017},
        Volume  = {68},
        Pages   = {32--42},
        DOI     = {10.1016/J.CAG.2017.08.004},
        ISSN    = {0097-8493},
    }

If any link is broken, feel free to send me an email or open an issue.

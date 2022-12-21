# simonitto-vipAge-progetto
The project work on data mining was to use machine learning algorithms on the a dataset taken at the following [link](https://www.kaggle.com/datasets/imoore/age-dataset).

The dataset shows thousands of VIPs, describing for each: Name, Short description, Gender, Country, Occupation, Birth year, Death year, Manner of death, Age of death.

Since the dataset is too big to work with, we reduced its size and did a pre-processing job.
In the pre-processing work we deleted the columns: Name, Short description, Birth year and Id, because they are not relevant.
Then we have grouped:
* the Country by continents
* the Occupations
* the Manner of death

Then we did some histograms to show some interesting things seen in the dataset.
We found that:
* Suicide was the most common Manner of death among artists.
* Many of these celebrities were Artists of various kinds.
* Most of them were Males.
* 500 of them died between 50 and 70 years of age.
* Most of the VIPs in the dataset were North American and European.


Then we trasformed categorical and ordinal features into numeric features to subsequently do the clustering.

# Code for ***An X-ray absorption spectrum database for iron-containing proteins***

## scripts
- `clean_folder.ipynb`: which is used for sort all extracted spreedsheets according to their x axis values, make sure extracted points are properly arranged.
- `generate_data.ipynb`: reading spectra come from Materials Project, we artificiallly generate XAS plot samples for Inter expert agreement experiment and annotation accuracy checking. The difference between these generated samples and plots come from papers is that, these samples have their absolute corresponding raw data, which eliminate the error of manual annotation and can be used for reference when we are doing extraction works.
- `save_dataset.ipynb`: after data cleaning and extraction, the dataset is almost complete but not organized, here we read the information recorded for each literarture and the data extracted together, then combine them into single JSON file, to present our dataset compatibly.
- `tech_validation.ipynb`: based on anonymous annotation of generated data, we compare these annotated values with raw data to conduct the inter expert agreement calculation and mean absolute error measurement.

## assets
assets for building our website which is used for presenting key points of our dataset

## index.html
the source code of our website of `XDIP`, which is available at `https://airscker.github.io/XDIP/`

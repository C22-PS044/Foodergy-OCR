# Foodergy-OCR
## Model Notebook
The model for the notebook are divided into two notebook. ``EAST_TFLite.ipynb`` host the text detection model, then ``OCR_TFLITE.ipynb`` host the text recognition. The notebook has sufficient information on how to run / build the model.

## Datasets
There are four kind of datasets in this repo. Alphanumeric, English food ingredients label, Indonesian food ingredients label, and generated text. The Alphanumeric is a standard OCR dataset and the generated text is a syntethic dataset generated from ``generate_image_text.py``. Only Indonesian food ingredients is labelled with ``.txt`` file of the same file name.

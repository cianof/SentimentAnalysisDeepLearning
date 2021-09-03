#Project Description and Outline
There are 2 notebooks included in the submission. The first is titled 'Original_Preproess.ipynb' - this notebook
trains the 2 specified models on the originally pre-processed dataset. The 2nd is Custom_Preprocess.ipynb', this
notebook trains the 2 specified models on data pre-processed by me.

All notebooks were run on the Google Colab interface (colab.research.google.com).
As a result, certain cells will not run correctly if run on a local machine e.g. any system
commands such as the setting up of kaggle api and the '!'' system commands.
To run notebooks locally it is a matter of changing paths to dataset. I have done my best to make the
code run as smoothly as possible across all environments but the first few lines in both notebooks ARE google
colab specific, these can be ignored if not running on colab.

Because colab is used, a fresh dataset is downloaded using Kaggle's API at the launch of 
each instance. This action requires the use of an API key. I have attached my API key in the 
submission folder under 'kaggle.json'. - This can be ignored if the notebooks are run locally. 
The api key must be uploaded with the launch of a fresh instance on colab, this can be done 
with the line 'kaggle_tok = files.upload()' and uploading the key this way.

The GloVe embeddings are also downloaded with fresh with each instance. They are downloaded in Google
Colab using !wget.
Again, if running locally then these WILL need to be downloaded and extracted from http://nlp.stanford.edu/data/glove.6B.zip and the path
variables changed to suit the folder the embedding are stored.

EVALUATION:
The models can be loaded in their respective notebooks, with the .h5 models appended with 'PRE' belonging in
the 'Custom_Preprocess.ipynb' notebook. They can be loaded under the 'Evaluation' section of each respective notebook.



INSTALL REQUIREMENTS:
pip install -r requirements.txt

if any issues are encountered in the running of any of the notebooks or if you would like access to the existing trained models please do not hesitate to contact me via
cian.ferriter@ucdconnect.ie

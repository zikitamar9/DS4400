# DS4400

Included in this repo you will find 4 files (outside this one)

**- data_generation.ipynb**
**- audio_features_df.csv**
**- categorical_decades.ipynb**
**- binary_centuries.ipynb**


Here is a brief description of each, and how to run them.

**data_generation.ipynb**
  - this is the file that generates our entire dataset by connecting to the spotify API. In it - we pull ~7000 songs from all the jazz playlists that spotify   publishes worldwide, and from then we pull ~14000 more songs via the reccomender function to create a comprehensive list of track_ids. We also ensure that our dataset is balanced and well distributed between 1900s and 2000s jazz. We extract the audio features from each song to then create the audio_features_df.csv. Unless you have a lot of time to spare, I would not suggest running this script as it can take an hour or two until its completion. Instead use the already created audio_features_df.csv


**audio_features_df.csv**
  - this is the csv file that we generate containing all audio feature data for each track pulled. This is the data we will use to generate models.


**categorical_decades.ipynb**
  - this is the notebook for our initial models that we ran to try to classify different decades of Jazz music. To run, simply execute all tabs sequentially in a juypyter notebook or Colab file. You will see metrics for each model as well as their supporting visualizations.


**binary_centuries.ipynb**
  - this is the notebook for our later models that we ran to try to classify 1900s vs 2000s Jazz. To run, simply execute all tabs sequentially in a juypyter notebook or Colab file. You will see metrics for each model as well as their supporting visualizations.


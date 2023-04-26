# VGAN-Model

## Data Collection

The gathered videos for the Philippine Violence Dataset is stored in a .csv file. There, each videos are named uniquely.

## Data Annotation

The gathered videos are then annotated, identifying moments of violence in each videos by marking timestamps.

### Video Trimming

After annotating the videos, trimming is done in order to create individual clips of violent and non-violent scenes.

## Frame Extraction

Taking the trimmed videos, farme extraction is done to collect individual images and frames.

## Numpy Creation

After taking the images, they are converted into data that is compiled into a numpy array.

## Model Training

With the data ready, generator and discriminator models are trained.

## Model Testing

The models are then tested and the results are noted. With this information, performance of each models trained into their respective data are gauged.

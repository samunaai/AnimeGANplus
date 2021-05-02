# AnimeGANplus
This repository contains our work on AnimeGANplus.

Please note that you may setup the required dependencies for running the Jupyter notebooks using 
`conda env create -f environment.yml`

The role of the various files and folders is as follows
- The `FID_tensorflow.ipynb` can be used to calculate the Frechet Inception Distance between true and generated cartoonised images
- The Linux commands in `ffmpeg.txt` can be used for video editing techniques such as stitching videos together downsampling, and addition of sound
- The `video_maker.ipynb` contains the code for stitching output frames from our model into a final movie result
- The `samples` folder contains sample inputs and outputs for individual frames generated using Paprika style. These frames were taken from the original video, as well as cartoonised version that we made, using the Katna keyframe extraction
- The `keyframe_extraction.ipynb` contains the code making use of Katna to perform keyframe extraction based on sum of absolute differences in LUV colorspace.

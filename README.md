# AnimeGANplus
This repository contains our work on AnimeGANplus.

Please note that you may setup the required dependencies for running the Jupyter notebooks using 
`conda env create -f environment.yml`.


The role of the various files and folders is as follows
- The `FID_tensorflow.ipynb` can be used to calculate the Frechet Inception Distance between true and generated cartoonised images
- The Linux commands in `ffmpeg.txt` can be used for video editing techniques such as stitching videos together downsampling, and addition of sound
- The `video_maker.ipynb` contains the code for stitching output frames from our model into a final movie result
- The `samples` folder contains `demo` inputs and outputs for individual frames generated using Paprika style. These frames were taken from the original video, as well as cartoonised version that we made, using the Katna keyframe extraction
- The `keyframe_extraction.ipynb` contains the code making use of Katna to perform keyframe extraction based on sum of absolute differences in LUV colorspace.
- `animeganplus.ipynb` contains the code for AnimeGANplus
 
The three training datasets for AnimeGANplus can be downloaded using a single block of code included in the `animeganplus.ipynb` file.


![authors_method](https://user-images.githubusercontent.com/22077758/116824306-8931fd00-ab9a-11eb-95e6-e2640423fc44.png)
![char_isolation](https://user-images.githubusercontent.com/22077758/116824319-94852880-ab9a-11eb-940c-608d888d6428.png)
![deathofvader](https://user-images.githubusercontent.com/22077758/116824320-9818af80-ab9a-11eb-9e94-630f7f88b348.png)
![epoch](https://user-images.githubusercontent.com/22077758/116824321-9949dc80-ab9a-11eb-8182-15c0dd1654a3.png)
![hoth_mustafar](https://user-images.githubusercontent.com/22077758/116824324-9a7b0980-ab9a-11eb-8a2e-69233e8fc8b5.png)
![superheroes](https://user-images.githubusercontent.com/22077758/116824325-9b13a000-ab9a-11eb-8fe3-8e85a0633bd2.png)

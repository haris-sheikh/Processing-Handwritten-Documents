# Processing-Handwritten-Documents

## Download models and data
We use the EAST text detector from [here](https://www.dropbox.com/s/r2ingd0l3zt8hxs/frozen_east_text_detection.tar.gz?dl=1).

For training our models we use the data downloadable [here](https://s3-eu-west-1.amazonaws.com/handwriting-curated-database/curated.tar.gz),
this was obtained from [this Github repo](https://github.com/sueiras/handwritting_characters_database?fbclid=IwAR14aXt_0EnBGzqJawkqriydhAgRf7IgeYv5Q4kwfjzm3jrQAPwKtH51auY).

To then run our code, insert the EAST model into the models folder, and the training data into the data folder. You will also need to set the project_dir variable to the directory of your project.

## References
### EAST Text Detection Model:
[EAST: An Efficient and Accurate Scene Text Detector](https://arxiv.org/abs/1704.03155v2)  
[Deep Learning based Text Detection Using OpenCV (C++/Python)](https://www.learnopencv.com/deep-learning-based-text-detection-using-opencv-c-python/)

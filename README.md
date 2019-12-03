# Processing-Handwritten-Documents

## Download models and data
We use the EAST text detector from [here](https://www.dropbox.com/s/r2ingd0l3zt8hxs/frozen_east_text_detection.tar.gz?dl=1).

For training our models we use the data downloadable [here](https://s3-eu-west-1.amazonaws.com/handwriting-curated-database/curated.tar.gz),
this was obtained from [this Github repo](https://github.com/sueiras/handwritting_characters_database?fbclid=IwAR14aXt_0EnBGzqJawkqriydhAgRf7IgeYv5Q4kwfjzm3jrQAPwKtH51auY).

To then run our code, insert the EAST model into the models folder, and the training data into the data folder. You will also need to set the project_dir variable to the directory of your project.

## Using the code
Open the python notebook and run the relevant cells in order. This was built on both Google Colab and on our personal computers, so there are cells that do not need to be run (and there will be errors if you run incompatible cells). Make sure you edit the second cell and update the project directory to point to where this repository is downloaded. 

If you would like to train the models yourself, you can download the character dataset and create the 'alphabet_most' and 'math_symbols' directories inside the Data folder. Then you need to copy the characters specified in the 'char_valid_targets' 'math_valid_targets' variables from the dataset into their respective folders.

If you just want to run the pre-trained models, you can just run the cells, but the ones concerned with loading data, training, and validating will fail. Just skip these.

## References
### EAST Text Detection Model:
[EAST: An Efficient and Accurate Scene Text Detector](https://arxiv.org/abs/1704.03155v2)  
[Deep Learning based Text Detection Using OpenCV (C++/Python)](https://www.learnopencv.com/deep-learning-based-text-detection-using-opencv-c-python/)

# SyntheticData

The script generates syntheric data that can be used in model training. 
Pre-requisites :
1. Install Python. Windows users refer : https://www.python.org/downloads/windows/
   Mac users https://www.python.org/downloads/mac-osx/
2. Install tensorflow using by running, source activate tensorflow_p27
3. Download script through web interface or command line.
   3.1 Web interface: Download zip from https://github.com/gandhiraketla/SyntheticData
   3.2 Command prompt : git checkout https://github.com/gandhiraketla/SyntheticData

Execution :

Execute script tfrecord_image_generator.py with below parameters
1. Path of folder where images are generates
2. No of training images
3. No of evaluation images

python tfrecord_image_generator.py <path_of_floder> <no_of_train_images> <no_of_evaluation_images>
Example : python tfrecord_image_generator.py /Users/gandhira/Documents/ML-Lab/SyntheticData 5 3

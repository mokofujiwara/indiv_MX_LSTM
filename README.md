
repository is mainatined by Ayesha Nirma and Hasan Nirma

This is **unofficial code/implementation** is available for research purposes. If you are using this code for your work, please cite the following papers

@InProceedings{Hasan_2018_CVPR,
author = {Hasan, Irtiza and Setti, Francesco and Tsesmelis, Theodore and Del Bue, Alessio and Galasso, Fabio and Cristani, Marco},
title = {MX-LSTM: Mixing Tracklets and Vislets to Jointly Forecast Trajectories and Head Poses},
booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2018}
}




The code is not clean nor optimize

Training
1) You can set the path in the utils.py file to any of the dataset you want to train on. Datasets are in the data folder
2) Launch Train.py
3) The trained model will be stored in save_lstm folder

Testing
1) Once the model is trained, you can launch test_pedestrian_wise.py
2) The output will be stored in VisualizeUtils/output 
3) Chnage the name of the model to load in evalLSTM.m
4) You can also plot prediction on the images, download the images and specify tha path in evalLstm.m and set genVisualization=1 

Evaluation is done using matlab script evallstm.m





----------------------------------------------------------------------------------------------------------------------------------


special thanks to the author of the paper in particular Irtiza Hasan for helping us in implementation. Please contact the authors for any queries.




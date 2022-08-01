# Traffic-sign-recognition
#using Python

Modules and Tech Stack

1.Tensorflow

2.Sci-kit Learn

3.tkinter

4.keras

5.Numpy

6.Pandas

7.Matplotlib

Computer vision objectives include, but are not  limited to, image acquisition and recognition. For example, the correct classification of traffic signs using image data of traffic signs can be of great benefit to automobile companies. To be able to classify traffic signs with good performance, it is important to find the best model using the corresponding hyperparameters. Therefore,  in addition to the analysis algorithm, it is necessary to implement a machine learning algorithm. The purpose of this multiclass classification analysis of traffic sign images is to examine the effectiveness of various classifiers for low quality off-center traffic sign images (in terms of both size and color) (surveyed by INI Benchmark). And provided. You can download it here: http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset).


The traffic sign data used is called GTSRB (German Traffic Sign Recognition Benchmark), which contains a total of 39,209 images and 43 classes (traffic sign type) in the training set alone. In addition to pre-computed features (such as HOG and hair), the data contains actual images and annotations. All of these were not used in this project. Everything was redone from the beginning. Image sizes range from 15x15 to 250x250 pixels. Images are not always square or centered. This explains why the INI Benchmark provides the actual road sign location in the  bounding box format for each image in the annotation CSV file. Since the purpose of this project is to classify low quality road signs, all images have been converted to grayscale and resized (reduced). Due to the original size mismatch, some images with a larger original size may contain more detailed information than the smaller image after resizing.



 The ability to build models with powerful predictive performance using low-quality or off-center images is a very common, time-sensitive, and computationally limited environment in the real world. It has an excellent effect. Random forest and multilayer perceptron classifiers fit  wrapper-based feature selection images and showed significant test f-score performance of 0.879842 and 0.911308, respectively. It also significantly reduces the time required for model fitting and hypertuning steps  compared to Gradient Boosting, Ada Boost, SVM, and XGBoost. Random forests have the fastest execution times with poor F-score performance, and multilayer perceptrons take significantly longer than random forests, but they have the best F-score performance of all the models examined.

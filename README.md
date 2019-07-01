# Distributed-Deep-learning-on-Caltech-UCSD-Birds-200-dataset
Deep Learning and Distributed Deep learning

Caltech-UCSD Birds 200 (CUB-200) is an image dataset with photos of 200 bird species (mostly North American ). For testing phase, we considered 5 birds and used VGG-16 CNN Architecture and with proper pre-processing and augumentation, we reached accuracy of 98.12 percent. The same, we implemented on distributed spark-environment on cluster and by using same architecture we got similar accuracy with way less execution time compared to the original python script on single system.

>> For executing the python script, get into the folder where it resides and run the following command :

python train.py --dataset dataset --model pokedex.model --labelbin lb.pickle

>> For executing the deep learning script on spark, get into the folder where it resides and run the following command :

 spark-submit birds_spark.py --dataset dataset --model pokedex.model --labelbin lb.pickle



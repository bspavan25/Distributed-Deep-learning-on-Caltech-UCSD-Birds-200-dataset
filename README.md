# Distributed-Deep-learning-on-Caltech-UCSD-Birds-200-dataset
Deep Learning and Distributed Deep learning

>> For executing the python script, get into the folder where it resides and run the following command :
 
python train.py --dataset dataset --model pokedex.model --labelbin lb.pickle


>> For executing the deep learning script on spark, get into the folder where it resides and run the following command :

spark-submit birds_spark.py --dataset dataset --model pokedex.model --labelbin lb.pickle



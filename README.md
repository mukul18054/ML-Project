# ML-Project
This is our final code for hand written digit classification using various models. 
In this project, we have trained various models for handwritten digit classification.

Abstract:
Humans’ reliance on machines has never been so highthat from classifying various objects in photographs to ap-pending sounds to silent movies, almost everything can beachieved using deep learning and machine learning tech-niques.  One of the significant fields of research and devel-opment with many possibilities is Handwritten text recogni-tion.  A machine can read and interpret handwritten char-acters from many sources like paper,  photographs,  laptopor  mobile  screens,  and  other  mediums,  known  as  Hand-written Text Recognition (HTR)[3].  This paper emphasizesHandwritten Digit Recognition, a subset of HTR, whereinwe are focusing on to be able to classify handwritten num-bers from 0-9.  With the help of MNIST Datasets, we willtrain  various  Machine  learning  models  like  Support  Vec-tor Machine (SVM)[3], Random Forests[2], ConvolutionalNeural Networks (CNN)[1][2][3][6], and Multi-Layer Per-ceptron  (MLP)[3].   This  paper’s  primary  objective  is  toget  the  best  possible  model  for  digit  classification  basedon  all  the  models’  accuracy  and  execution  time.Keywords- MNIST, Support Vector Machine, Perceptron,Neural Networks, Decision Tree

1. Introduction:
Handwritten digit recognition is the computer’s abilityto read and accurately classify the human handwritten dig-its from different sources like photographs, papers, mobiledisplays, etc., into ten predefined classes (0-9).  It is one ofthose topics involving boundless research in the field of Ar-tificial Intelligence. From number plate detection to sortingpostal mails, from bank cheque processing to reading nu-meric entries in forms filled up by hand, digit recognitionhas numerous applications.  Due to other peoples’ differentwriting styles, it is a challenging task to perform digit clas-sification.  This research brings up a comprehensive com-parison between many known classifiers available in Ma-chine Learning and Deep Learning. The algorithms we usedare Convolutional Neural Networks,  K-Nearest Neighbor,Logistic Regression, Support Vector Machines, MultilayerPerceptron, Decision Trees, Random Forests, and GaussianNa ̈ıve-Bayes.  The comparison is carried out based on ac-curacies and training times.The accuracy of a model is paramount because more ac-curate models will make better predictions.  For real-worldscenarios,  a  model  with  low  accuracy  is  not  suitable.   Inbank cheque processing, the system recognizes the amountfilled  and  date  written  on  the  cheque,  and  high  accuracyis crucial here.  Incorrect recognition can cause significantdamage,  which  is  undesirable.   So  this  paper  emphasizescomparing  different  classifiers  based  on  their  accuracy  toapply the best model in practical situations with the marginof error being as low as possible.This  report  aims  to  provide  a  good  understanding  ofmany  classifiers  available  in  Machine  learning  and  deeplearning for handwritten digit classification. It also gives in-formation regarding the efficiency of the algorithms in per-forming the required task.   The upcoming sections of thepaper will discuss some related works in this domain, fol-lowed by a description of the dataset used to train the classi-fiers and the required pre-processing. This will be followedby the methodology and implementation of the classifiersfor a better understanding and, lastly, the results’ analysisand conclusion.  The last section of the paper has citationsof references used


2. Dataset
  2.1. MNIST(”Modified National Institute of Standards and Technol-ogy”)The data initially has 60k samples of size 28*28.  Con-verted it to 784*1 (direct data in this format is
      also avail-able).[3][6][2]The first column is the actual label (i.e., 0,1,..9) and rests784 columns are features which have the value in range 0to 255 representing the 
      intensity of colour in that particularpixel.Some columns have a value 0 always for all the 60k sam-ples. So we have dropped those columns.
  2.2. EMNISTEMNIST Extended version of MNIST dataset and hassimilar features.  Along with digits, it also has letters in theclass labels

Added both ipynb and python code 

you can refer ipynb if you wants to check the outputs. 

keep both the data in the same folder 
1. MNIST -> train.csv
2. EMNIST -> emnist-digits-train.csv

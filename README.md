# COVID-Detection-using-CNN
COVID Detection using CNN

**Introduction**

Coronavirus Disease 2019 (COVID-19) continues to have a devastating effect on the well-being and health  of the world population, caused by the virus of individuals by the severe acute respiratory syndrome coronavirus 2  (SARS-CoV-2). The illness was first recognized in December 2019 in Wuhan, China, and has since spread all around  the world. This disease can cause respiratory problems and cause severe problems. Various symptoms of this virus  include fever, dry cough, aches, sore throat, tiredness, diarrhea, headache, and rashes on the skin, discoloration of  fingers or toes, conjunctivitis, difficulty in breathing, loss of taste or smell, chest pain, or pressure and loss of speech  or movement. As of February 2021, almost 2.49 million lives are lost to COVID-19, and these are only the confirmed  cases. The costs for the diagnosis of the disease are pretty high. Presently, most of the tests are genetic tests known  as Reverse Transcription Polymerase Chain Reaction. They are very accurate and can detect even the slightest trace  of the infection, but at the same time, the results take a long time and are also costly. So, not all hospitals can afford  to perform it. Now, studies show that viruses belonging to this family are detected well in radiographic images. So,  using computed tomography (CT) scans or chest X-rays is much faster, accurate, and also cheaper than Polymerase  Chain Reaction (PCR) tests. We used chest X-rays as they are more economical than CT scans and are available in  almost every hospital.  
In this epidemic situation, Artificial Intelligence (AI) and Machine Learning (ML) techniques are becoming  vital. AI is used to detect or predict various diseases like breast cancer detection, lung cancer detection, diabetes  detection, or heart disease detection at an early stage. The use of AI in healthcare has the potential to help healthcare  providers in many aspects of patient care and administrative processes. Deep Learning (DL) has gained a unique  place in the stream of AI for image-based classification and regression problems by providing successful results. DL  in healthcare has been seen in various healthcare streams, but especially in medical imaging, drug discovery, medical  insurance fraud, Alzheimer's disease, and genome. Using Convolutional Neural Network which is a DL algorithm  has enabled image-based applications to reach their popularity in the past few years. CNN is a neural network that  requires very minimal pre-processing of images before giving them to the network, and the efficiency of a CNN  algorithm is increased with the number of training steps. It is very capable of extracting features from images. It is  used in detecting healthy or cancerous tissues to help improve radiation treatments, pneumonia detection, and chest  tuberculosis detection.  
Therefore, detecting COVID using chest X-ray images is the best way. So, we have predicted the COVID 19 in patients by using their chest X-rays. We have used four different CNN models in order to do so. After cleaning  up the chest X-ray images and applying data augmentation, we used deep learning-based CNN models and checked 
the accuracies of their performance. The evaluation of results in terms of training and testing with confusion matrices  for the models is discussed. 

**Dataset**

For testing the results of our models, we have used chest X-rays of patients who have COVID and who are healthy.  We have gathered the dataset from GitHub open repository. Our dataset has a complete total of 940 images of chest  X-rays. Out of these images, 505 chest X-rays are of healthy patients and 435 chest X-rays are of COVID19 affected  patients. 80% of the data is used for training the model and 20% for testing the model. All the images are in different  dimensions, so we resized them to 224 x 224 and are normalized.  

**Conclusion & Future Scope**

COVID-19 is burgeoning very quickly. In this work, we have analyzed four CNN models to classify people who are  affected with COVID-19 using their chest X-rays. Our Xception model achieved the best accuracy with 93%. VGG19  & ResNet50 models achieved an accuracy of 91%. Inception V3 model achieved an accuracy of 89%. The Xception  model gave the best results. It has the smallest weight serialization. VGG19 has 19 weighted layers which make it  slow to train. ResNet50 also has many layers in it but it occupies less memory as instead of fully connected layers,  we use average pooling. InceptionV3 is slightly intricate in structure. We need to understand it even better in order  to make it perform better. We finally classified COVID-19 scans, and it shows possible scope for the future to  automate diagnosis tasks.  
Our future goal is to use it on a larger dataset to see if we can still achieve this high accuracy and make better  predictions as in machine learning, if you train a model on large data, the predictions on unseen data are more  accurate. As this is not clinically approved, it can be consulted with a professional to get a clear picture of how far 
the models are practically viable. As this is just an economically feasible solution, we can see that this research is  put into practice in the near future.  

DRONE-SWARMS-DETECTION


THE MAİN PURPOSE OF THE PROJECT

Security breaches that drone swarms may create in the air defense system must be determined in advance.In this study, an intelligent drone detection system is proposed for the detection of drone swarm.Among the object detection methods, the YOLO algorithm was preferred as the optimum method.


DETECTİNG WİTH YOLO ALGORİTHM

![image](https://user-images.githubusercontent.com/74248391/126878548-dc2bb999-19de-4496-b093-e8bcfc8fb766.png)

EXPERİMENTAL RESULTS

In studies with deep neural networks; It is known that model performances differ depending on the structure of the data set used, the size and depth of the architecture, the optimization methods used and the type of activation functions. In addition, the performance of optimization algorithms depends on the choice of parameters and how the neural network will be configured.The training process of the artificial neural network model designed in the study was carried out on the Google Colab platform, which provides free GPU support. Test processes were carried out with the Spyder IDE.
The initial learning rate and other parameters required for the system to work properly were taken the same as in the original YOLOv4 model. Only necessary hyperparameters have been modified to improve performance.The model was trained for approximately 8 hours. The training process took 2000 epochs and the weights of the model were backed up every 200 steps. These backed up weights were then run on the test data.


![image](https://user-images.githubusercontent.com/74248391/126878570-7a7b7424-b3d8-4031-96cc-87d194483311.png)



![image](https://user-images.githubusercontent.com/74248391/126878596-1efd75b6-6a10-46c3-98c4-3adea0884060.png)

As a result of the object detection process, an average of 97.48% success was achieved in the same type of drone types in the dataset, an average of 95.46% on noisy images with different scaled drone types, and an average of 95.67% on images of different weather conditions.

## Dataset of Mobile Sensors based Human Physical Activities Recognition to Pandemic Spread Minimization (KAU-COVID19-AR-Dataset)

* This repo describes a data collection campaign and a set of resulting data obtained from smartphone sensors that show useful functions in reducing the spread of COVID-19 (epidemic). 
* Database is released as a collection of CSV files containing more than 37K data samples, where each sample is composed of 7 features related to many mobile sensors, including accelerometer, gyroscope, speed, and GPS sensors, with the help of our application that we developed using Flutter application development platform. 
* First we collect the each sensor data locally in mobile device in a CSV format and then send this that to the PostgreSQL server. 
* In addition, a sample of each data is associated with a basic truth label that describes the user’s activity and the situation in which he or she was involved during a sensory examination (e.g., handshakes, hand washing, hand sanitizing and eyes nose and mouth touching, etc.). 
* To avoid introducing any bias during data collection, we performed a field-based sensory examination, that is, using multiple companies mobile devices, and without identifying any barriers to user behavior when performing any activity.
* The set of data collected represents a useful real data source to describe and evaluate a comprehensive set of novel activities aimed at helping to reduce the spread of COVID-19.

Table shows the Dataset (KAU-COVID19-AR-Dataset): Activities, No of samples
Activities          | Number of Samples
------------------- | -----------------
Walking             | 15866
Hand Washing        | 6422
Standing            | 5665
Sitting             | 2869
Hand Sanitizing     | 2105
Nose Eyes Touching  | 1770
Hand Shake          | 1397
Drinking Water      | 1404

#### Data Specification ####
Title                     | Discription
------------------------- | ------------------------------
Subject Area              | Artificial Intelligence, Machine Learning, and Deep Learning
Specific Subject Area     | Smart-phone based human physical activities detection using machine learning and deep learning
Type of Data              | Sensor’s Data including Accelerometer, Gyroscope, Speed and GPS Sensor.
Data Formate              | Raw and Featured
Experimental Factors      | Data was collected by performing multiple activities e.g. Hand washing, Hand sanitizing, Nose-eyes-mouth touching, and Hand shaking etc
Related Research Article  | Abdul Wasay Sardar, Computers in Biology and Medicine, https://doi.org/10.1016/j.compbiomed.2022.105662 [[6]](#6)

#### Value of the data ####
* This data is collected by performing multiple activities e.g. washing sanitizing and shaking hands, walking, sitting, standing, and drinking water, can be used
to build pandemic spread minimization system.
* The data can be used for behaviour analysis of individual, and group of peoples, and also helpful for the healthcare monitoring, health surveillance, medical
and disability assistance.
* The structure and quantity of data can be used for various activity detection tasks such as classification, recognition, and prediction.
* This dataset is - as far as we know - the first publicly available physical activities dataset for the pandemic spread minimization.

#### Dataset Description ####
* The novel dataset (KAU−COVID19−AR−dataset) collects by performing multiple activities such as washing hands, hand sanitizing, shaking hands, touching the nose
eyes or mouth, sitting, standing, walking and drinking water.
* The location of the smartphone is very important for the acquisition and higher accuracy of the dataset. Place your smartphone in a compatible watch-like position. Figure 1 shows the placement of the position on the smartphone.
* The location of the smartphone is similar to the location of Figure 1: Position of Mobile phone is (arm Position) for activity data collection the smartwatch that has achieved market penetration of in the past [[4]](#4). 

<p align="center">
<img src = "https://github.com/wasay530/-KAU-COVID19-AR-Dataset/blob/acd6c0007e57067e594fd107eac76d515b4ab8ad/mobile_position.png" title= "Dataset (KAU-COVID19-AR-Dataset):each activity" width="800" height="400" alt>
</p>
<p align="center">
  <em>Figure 1: Position of Mobile phone is (arm Position) for activity data collection</em>  
</p>

* It is important to note that the position of the smartphone on the participant’s body is fixed. 
* For in these experiments, we used smartphones from various companies.
* The orientation of the smartphone was vertically along the forearm. 
* Data for all activities was recorded at 10 samples per second. This sampling rate (10 samples per seconds) is sufficient to detect human physical activity [[3]](#3).
* Figure 2: Dataset (KAU−COVID19−AR−Dataset): Each activity In addition, recent advances have shown that less than 10 samples per second is insufficient for activity detection [[1]](#1)[[2]](#2). 

<p align="center">
<img src = "https://github.com/wasay530/-KAU-COVID19-AR-Dataset/blob/acd6c0007e57067e594fd107eac76d515b4ab8ad/Person_data.png" title= "Dataset (KAU-COVID19-AR-Dataset):each activity" width="600" height="400" alt>
</p>
<p align="center">
  <em>Figure 2: Dataset (KAU-COVID19-AR-Dataset):each activity</em>  
</p>

* Accelerometer, gyroscope, and speed sensor data are acquired at a speed of 10 samples per second, and GPSsensor data data are acquired at a speed of 1 sample per 
seconds [[5]](#5). 

## Note: If you use this dataset, you have to cite the paper [[6]](#6). Thanks  
## References
<a id="1">[1]</a>
Shoaib, Muhammad, Stephan Bosch, Ozlem Durmaz Incel, Hans Scholten, and Paul JM Havinga. "Fusion of smartphone motion sensors for physical activity recognition." Sensors 14, no. 6 (2014): 10146-10176.

<a id="2">[2]</a>
Wu, Wanmin, Sanjoy Dasgupta, Ernesto E. Ramirez, Carlyn Peterson, and Gregory J. Norman. "Classification accuracies of physical activities using smartphone motion sensors." Journal of medical Internet research 14, no. 5 (2012): e2208.

<a id="3">[3]</a>
Marusenkova, T. A. "An algorithm for detecting the minimum allowable accelerometer sample rate for tracing translational motion along a Bézier curve." Технічна інженерія 1 (85) (2020): 147-154.

<a id="4">[4]</a>
Samsung Galaxy S2. Available online: http://www.samsung.com/global/microsite/galaxys2/html/ (accessed on 14 May 2014)

<a id="5">[5]</a>
Nguyen, Khuong An, Zhiyuan Luo, and Chris Watkins. "Epidemic contact tracing with smartphone sensors." Journal of Location Based Services 14, no. 2 (2020): 92-128.

<a id="6">[6]</a>
Sardar, Abdul Wasay, Farman Ullah, Jamshid Bacha, Jebran Khan, Furqan Ali, and Sungchang Lee. "Mobile sensors based platform of Human Physical Activities Recognition for COVID-19 pandemic spread minimization." Computers in Biology and Medicine (2022): 105662.

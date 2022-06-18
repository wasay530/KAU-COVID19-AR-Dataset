# -KAU-COVID19-AR-Dataset
# Dataset of Mobile Sensors based Human Physical Activities Recognition to Pandemic Spread Minimization (KAU-COVID19-AR-Dataset)
Mobile Sensors Data collection for the Human Physical Activities Recognition for COVID-19 Spread Minimization
This repo describes a data collection campaign and a set of resulting data obtained from smartphone sensors that show useful functions in reducing the spread of COVID-19 (epidemic). 
Database is released as a collection of CSV files containing more than 37K data samples, where each sample is composed of 7 features related to many mobile sensors, including accelerometer, gyroscope, speed, and GPS sensors, with the help of our application that we developed using Flutter application
development platform. First we collect the each sensor data locally in mobile device in a CSV format and then send this that to the PostgreSQL server. 
In addition, a sample of each data is associated with a basic truth label that describes the user’s activity and the situation in which he or she was involved during a sensory examination (e.g., handshakes, hand washing, hand sanitizing and eyes nose and mouth touching, etc.). 
To avoid introducing any bias during data collection, we performed a field-based sensory examination, that is, using multiple companies mobile devices, and without identifying any barriers to user behavior when performing any activity.
For this reason, the set of data collected represents a useful real data source to describe and evaluate a comprehensive set of novel activities aimed at helping to reduce the spread of COVID-19.

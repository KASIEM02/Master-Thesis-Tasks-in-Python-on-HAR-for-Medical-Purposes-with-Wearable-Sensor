# Master-Thesis-Tasks-in-Python-on-HAR-for-Medical-Purposes-with-Wearable-Sensor
Some of the tasks involved are:

Collecting real-world human activity measurements from a wearable sensor on participants and single-person physical activities.

![Alt Text](image-url)
![Sensor Image]([The wearable sensors used in my Masters Thesis tasks.jpg](https://github.com/KASIEM02/Master-Thesis-Tasks-in-Python-on-HAR-for-Medical-Purposes-with-Wearable-Sensor/edit/main/README.md))



Cleaning the data and processing the signals by upsampling collected measurements due to inconsistencies in sampling rates from the multiple sensor sources.

Data annotation was done by manually labelling the sensor measurements with unique integer values using a business intelligence tool.

Data modelling by combining multiple sensor measurements (IMU, ECG, and pressure) to create a homogenous dataset.

Designed 1D CNN, LSTM, and 1D CNN-LSTM for comparison.

Conversion of the best-performing model to TFlite for deployment in an ARM Cortex M7 microcontroller.

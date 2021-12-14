## Anomaly_detection
**Anomaly detection on NASA Bearing Dataset**<br>
1. Aim was to detect the anomaly in the incipient stage of damage and also report the kind of defect if needed.<br>
2. Due to the absence of labelled data and presence of data from essentially one class, predictive modelling techique, like LSTM was used.<br>
3. LSTM models the normal behaviour of the bearings, and the prediction errors are subsequently used to identify abnormal behaviour.<br>
4. A level 0 warning is triggered when the errors cross the calculated upper/lower bounds. Continuous level 0 warnings lead to a level 1 warning (which means that the bearing is broken, and the machinery should be stopped to prevent further damage).<br>

**Detecting fault in a motor with broken rotor bars, with data recorded at different loads**<br>
1. Healthy and unhealthy data were both recorded at 4 load conditions: no load, minimum load, medium load, full load.<br>
2. The vibration data was loaded and used in further steps for model building.<br>
3. Features were extracted and selected and LSTM and One-Class SVM models were built. Both of them gave comparable results. <br>

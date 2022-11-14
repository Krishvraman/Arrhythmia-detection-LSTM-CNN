# Arrhythmia-detection-LSTM-CNN

The goal of the project is to detect abnormal heartbeat patterns. Extracting heartbeats have become a feature of smart watches and exploring this data better could give use potential insights to overall health.


Understanding the Signals:
- Using an annotated ECG dataset 
- The data is  represented by a matrix  𝑋∈ℝ𝑁×𝐷 . N is the number of training points. D is the data dimension. We will consider one data point as +/- 3 seconds sequence of samples centered around a normal or abnormal symbol. Therefore,  𝐷=6𝑓 , where  𝑓  is the sampling frequency.
- Applying bidirectional LSTM to detect arrythmia
- Applying 1D CNN to detect arrthymia
- Evaluation

![image](https://user-images.githubusercontent.com/117613924/201554403-f3899486-4320-4e5b-99d5-9818a82f8831.png)




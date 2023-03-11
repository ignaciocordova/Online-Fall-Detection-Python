# Online Fall Detection Mechanism Using Python 

Using data recorded from smartphone sensors I developed an online algorithm to detect the user's state between "Rest", "Walking" and "Fall". When a fall has been detected the algorithm asks for a user's input. This could be used to confirm the fall and ask for help. 

To work online the algorithm reads sensor data taken at $\sim 200 Hz$ and every second calculates the user's state. The user's state is determined using the standard deviation of the accelerometer signal during the last second. 

![](https://github.com/ignaciocordova/Online-Fall-Detection-Python/final_result.gif)

Related work: https://jneuroengrehab.biomedcentral.com/articles/10.1186/s12984-021-00918-z

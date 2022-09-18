# Hand_Driving_In_Airsim
In this project, I was able to drive a car in Airsim simulator without using the keyboard. 
AirSim is a simulator for drones, cars and more, built on Unreal Engine. It is open-source, cross platform, and supports software-in-the-loop simulation with popular flight controllers such as PX4 & ArduPilot and hardware-in-loop with PX4 for physically and visually realistic simulations. It is developed as an Unreal plugin that can simply be dropped into any Unreal environment.
## **1- install Mediapipe:**
In order to achieve the desired goal, i used the MediaPipe for hand detection. MediaPipe Hands utilizes an ML pipeline consisting of multiple models working together: A palm detection model that operates on the full image and returns an oriented hand bounding box. A hand landmark model that operates on the cropped image region defined by the palm detector and returns high-fidelity 3D hand keypoints. 

In your script, all you have to do is to install mediapipe (pip install mediapipe) and then import it

##**2- Download Airsim:**
you can download and install it from this link : https://github.com/microsoft/AirSim

##**3- Running both airsim_simulator and main.py:**

The code is so simple and there's comments that can help you understand everything written.

![1](https://user-images.githubusercontent.com/103439643/171045913-0705b065-cbe7-4aeb-9c4a-30c0c1a4f074.PNG)

![2](https://user-images.githubusercontent.com/103439643/171045920-5b4bae37-1a5c-41ad-94a1-8d2544dad1f1.PNG)

![3](https://user-images.githubusercontent.com/103439643/171045924-31c0f564-1760-4e7f-b95a-8e7035ba9b3e.PNG)

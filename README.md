The purpose of this rover is to roam around the fields and to provide video information from the given environment and to capture the images of crops and send them to a cloud platform. In the cloud using the collected pictures we apply certain inbuilt algorithms on the pictures to determine the condition of the crops. In this project, one can control the rover with the help of mobile or laptop through Internet of Things (IoT) and also can get the live streaming with the help of wireless camera from the rover. This rover also uses various sensors that collects data and sends it to the microcontroller which controls the rover behavior. 

**Methodology**

The system consists of three major sections - one is the user section , rover section and the other is training section.

For connecting the user system with the internet, the Arduino IDE software is used. Through this we can send commands and can easily control the robotic vehicle.

At the rover section we are using an Arduino/Node MCU microcontroller placed on the body of the rover, which is the integral part of the robotic vehicle. The microcontroller is coded with IDE software in order to operate the rover in appropriate directions.

The rover then captures the pictures of the crops and using those pictures we create a dataset or directly we can collect the images and train those images.

We develop a disease prediction algorithm using tensorflow algorithms and then we train the collected images using this algorithm.

Then the test image is passed into this algorithm and based on the training efficiency , the condition of the crop is predicted.

![image](https://github.com/user-attachments/assets/42a89720-582e-471f-8b07-557bc56dab4f)

![image](https://github.com/user-attachments/assets/9ceddef6-0c15-4c21-8ac7-4cb2f55adfd5)






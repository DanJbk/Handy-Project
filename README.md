The purpose of this project is to create a working solution for interaction between people and computers. The project aims to provide an intuitive and relatively cheap alternative that allows precise movement in real time. It harnesses Machine-learning architecture to extract hand and joint poses from a live input stream of RGB images then map them to a joystick coordinate output. This allows the user to emulate joystick input to the system by tilting his/her hand in front of the camera.

The project consists of two networks. 

1.	A hand landmark network that extracts the 3d coordinates of the joints of the hands from a stream of RGB images from a camera.

2.	A Coordinates-to-vector network which translates the 3d coordinates to the joystick coordinates required.

The system is fast enough to work in real time, and is functional in various conditions. The data for the training and testing phase was gathered using a physical joystick that functions as the baseline for our training phase and results. We calculated the MSE (mean squared error) between the joystick and the produced result.

This method is reliable and accurate enough for usage in many applications. The tracking works in various environments and types of hands, and requires only minor adjustments to be comfortably used  by different users.


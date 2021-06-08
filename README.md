# Object animation & texture mapping

It was a team project done by:

[Kareem Mostafa](https://github.com/KareemYaseen), 
[Marwa Abdelaal](https://github.com/MarwaAbdelAal), 
[Nada Ezzat](https://github.com/nadaezzat-99), 
[Noura Mahmoud](https://github.com/Noura-Mahmoud), 
[Youssef Mohamed](https://github.com/Youssef-elkeheil), 

***

We have build a complete 3D room consists of a floor , ball and sofa .

The robotic body we have already built in the previous task was put in this room with two different animation patterns :

1. First one is the body without any interactions with the surrounding objects.

- The Texture on The Floor and the body on it :

![alt text](images/1.jpeg?raw=true)    

- Changing The Floor Texture :

![alt text](images/2.jpeg?raw=true)

![alt text](images/3.jpeg?raw=true)

![alt text](images/4.jpeg?raw=true)


1. Second one is the body with interactions with these objects.

![alt text](images/5.jpeg?raw=true)

![alt text](images/6.jpeg?raw=true)

![alt text](images/7.jpeg?raw=true)

![alt text](images/8.jpeg?raw=true)

![alt text](images/9.jpeg?raw=true)

## Compile 

g++ -o main main.cpp imageloader.cpp glm.cpp -lGL -lglut -lGLU -lm

## Run 

./main
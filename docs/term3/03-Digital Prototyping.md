## Task 3

*Creating an artifact using CNC machine with Marius, Everardo, Sophie and Jorge*

### First step, ideating a pottery wheel

![alt text](<../images/digital_protyping/Risorsa 18RT1.png>)


## Task 4, Prototyping for interaction design

*Prototype and train a model that has three different OSC messages with Carmen*

Both Carmen and I are working on our projects in the more social sphere.
The reference was to create a kind of online phone call where, based on the emotions and movements detected, the camera feed would change colour and sound depending on how the person on the other end interacts with you. 
The inputs should be: Soft sensor, phone and face.

![alt text](<../images/digital_protyping/Risorsa 19RT1.png>){: .image-55-size-left}


### Soft sensor
we started by developing these first sensors created with fabrics and the velostat, i.e. this marial that allows the resistance between two charges to vary and thus be able to measure the pressure applied at a given point. We first created a single sensor and then a matrix that, connected to processing, could map the area of the sensor and detect the position of where the change in pressure is applied to the touch

(gif here)

### Second step, translating emotions into data
Our goal was to train a model to recognize emotions through different types of movements: anger, indicated by aggressive movements; happiness, shown by fluid movements; and confusion, characterized by minimal movement. The third input is a soft sensor that can pause all subsequent inputs. Essentially, face and phone tracking are similar as they both aim to recognize feelings and emotions, while the soft sensor acts as a switch, modifying how Wekinator and Max8 process inputs and outputs.
![alt text](<../images/digital_protyping/Risorsa 20RT1.png>)

## Final considerations
We were therefore able to train a model such as Wekinator by combining facial expressions with body language using both a camera and sensors. it was very interesting for me to implement a more 'emotional' connotation to my body language reading research (part of my thesis project) rather than a broadly physical one. 
Of course, it is not so direct and simple to create an intelligence that can accurately recognise human emotions as they are influenced by many factors 


## Final video

<iframe width="560" height="315" src="https://www.youtube.com/embed/KlrL4ZGIO6s?si=N830Mjcy5HCZkdNf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>



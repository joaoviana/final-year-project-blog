# An overview on sound spatialisation techniques
#### January 03, 2019

Before starting the development process of the final project, I had to do extensive background research on sound spatialisation techniques. 

Spatial sound’s main concern is to emulate the way that sound is propagated in an acoustic environment, but can also be used to create surreal ones. 
The main aspects that concern the recording of spatial audio are the audio content itself, but also the spatial properties of the source and the surrounding environment.

Chowning's theory resolves the simulation of moving sound sources, by taking into account perceptual cues which can be configured into sound installations. Chowning's setup would consist of a listener positioned in the centre of an enclosed rectangular room and 4-speakers in each corner of the same room. 
By it being limited to a 4 speaker array, I am going to point out other techniques that overcome this limitation. 

#### What if we can reproduce spatial sound recordings without having the user present in a set-up installation like Chowning's? 

This can be done with the synthesis of ‘binaural’ sound. 

Binaural technology is a body of methods that involves the acoustic signals to both ears of the listener for achieving practical purposes, for example, by recording, analysing, synthesising, processing, presenting, and evaluating such signals.
The process starts with recording and reproducing sound that simulates realistically the localisation of sound sources, by mimicking the response in human ear perception. It is intuitive to use two distinctively separated microphones in order to record audio as it is in real-life heard. The technique can be done by placing both microphones at both hears of a human head or can be also done on an artificial head. 

#### And what is currently the main method for rendering 360-sound in Virtual Reality Applications? 

That is ambisonics. 
Ambisonics is the most common audio standard technique to record, modify, and reproduce audio in 360°. It is also a multichannel audio format that represents the way that sound is produced in a three-dimensional sound space. 
The core of this approach is to treat the audio scene as a full spherical field, where sound is coming from all directions around a central point. That same point is where the microphone is placed while recording. The most popular format used in VR is Order 1 Ambisonic, which means: a 4-channel format which uses those same channels to reproduce an entire sound sphere.

<img src="https://i.ibb.co/gZSQF4y/ambisonics.png" alt="ambisonics" width="200px">



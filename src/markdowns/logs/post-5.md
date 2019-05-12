# Building the Application
#### February 28, 2019

This tool was made with A-Frame, Three.JS and the Resonance Audio SDK. The programming language used was JavaScript to declare the event listeners and registering re-usable A-Frame components, each with specific goals and usage throughout the VR experience. These components can be attached to any ‘a-entity’ in A-Frame and help scale the development process up. Also, there are open source components available online made by developers in the A-Frame community that are useful to set up stunning 3D sceneries that are optimised in a way that I did not have the necessity to program them myself. The aim of this project is to configure a tool that is easily partitioned into clear ‘chunks’ and understandable by other technology professionals.
In order to represent the power of A-Frame combined with RA, I have established three different concepts to portray in the developed tool:
-	The basic concept of sound spatialisation and artificial reverbertation.
-	The customisation of a sound field to explore what the changes added might influence.
-	More complex concepts, such as Occlusion and Lata Reflections.


### Considerations throughout the development process

Using vanilla JS with A-Frame is a bit tiring. I would rather be using the React-Aframe or the Vue-Aframe libraries and build the application in a resusable-component based design. However, this could mean that the app could 'break' in the future. 

I wish I have bought a different HMD. Oculus Go does not allow the user to move in the scene, only move their head. However, I have added this A-Frame technology that allows that: <a href="" target="_blank">https://github.com/donmccurdy/aframe-extras/tree/master/src/controls</a>. A downside of adding this component to the application is the effect it has on its performance:
- By tracking the user's and sound source's position and orientation in the scene on every milisecond.
- By applying real-time effects to the scene using the Resonance Audio SDK.
- By building a menu-based application.
- By using a HTML-templating system and swapping html code in real-time. 


### What I have got so far

Customisable Scene - sound source (sphere). User can change the materials/properties of the room, sound source shape, sound file, gain and how sound should be attenuated. 
Beginning the Learn Menu: Occlusion effect and explaining directivity patterns; Late Reflections durations - getting these values by inspecting the Resonance Audio JS file

## Supervisor Meeting Notes
Talked about User Testing Methods that are going to be applied

Talked about hibrid methods used in VR user testing; 

It was pointed out how important to the grade the Testing phase is and how to analyse and further discuss the results

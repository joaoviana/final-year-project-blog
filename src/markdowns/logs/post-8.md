# Final Thoughts
#### May 10, 2019

Most of the participants found this tool to be substantially useful for understanding the intricacies of sound spatialisation and modern techniques in WebVR development.
Also, they found the application to be fairly easy to use, well-organised, and comprehensive. 
 
Having an easy-access tool to learn the basis of 360 sound rendering and experiment with the Resonance Audio SDK is key to many if not all of the participants. 


### Limitations

However, other app design decisions could have been made during the development phase of the application: the Oculus Go device did not provide with camera locomotion, meaning that by default the user could not move around the scene, and the trackpad functionality had to be overridden by computationally expensive JavaScript methods; another aspect that was considered on the last phases of app deployment was that there is a scalability issue with the framework chosen for the application. 

### Maybe Unity??

Although A-Frame is impressively easy to use and enables less experienced developers to build immersive VR scenes, this tool may have to be migrated to a Unity application and then exported to WebVR. Unity provides with less computationally expensive high graphic fidelity and also has no compatibility issues with the Resonance Audio SDK. Another asset to developing with Unity and RA is the addition of a wide range of reverb baking tools, such as: the modelling of arbitrary geometries through a fast ray tracing algorithm; the possibility to add numerous materials to the same wall; can add complex-shaped geometries and not have to decompose them into ‘box-shaped’ components. And finally, with Unity’s RA plugin, reverb probes can be define a ‘region of application’, so when the user enters them, the pre-computed properties are applied. This is extremely useful when transitioning from one room to another and the transition needs to be as realistic as possible. For example, when developing a game where the player leaves a building and ‘enters’ a sonically different setting.
Implementing the recommendations and also continuing to work with users (next iteration with only game designers/developers) will ensure a more stable and improved version of this WebVR tool. 

## What's next?

Definitely make this in Unity.

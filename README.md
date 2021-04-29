This repository features a collision detection component for A-Frame that detects when an entity enters and leaves a space surrounding another entity. 

How to Run: 
1. Run the following command: `npm install && npm start`
2. A new tab should open in your web broswer. Bypass permissions when prompted. 
3. Open up the developer console to see output from the collision detection component.
4. Use the arrows to move Buzz closer to the box, which the collision detection component is mounted on. When Buzz gets within a certain distance from the box, a collision has started and output is printed to the console. 
5. Use the arrows to move buzz away from the box. When Buzz exits the collision radius, the collision has ended and output is printed to the console. 
6. Take a look at the collision-detector.js file to learn more. When using this component in other projects, change the function bodies of onCollisionStart() and onCollisionEnd() to perform any functionality you desire when a collision starts or ends, respectively. 

Credits: 
1. The A-Frame code was written by Akshay Sathiya and built upon examples and existing code from the A-Frame documentation (https://aframe.io/docs/1.2.0/introduction/) and Mozilla's trigger volume compoment (https://github.com/mozilla/hubs/blob/hubs-cloud/src/components/trigger-volume.js).
2. The 3D model of Buzz was created by William Colin Freeman. 

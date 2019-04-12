# Install :

* clone this repo
* open the index.html file you want in a recent browser
* enjoy :D

# Each folder is a independent demo/test

### test 1 :  
* [V1] :
    * threejs "getting started", create scene & camera
    * basic game loop with requestAnimationFrame & time managment 
    * basic vertex and fragment shader to interract with mesh position/color via the GPU
    * send JS computed variables to shader for interractive shader
    * basic CPU 3DObjects manipulation using Quaternion angles and Vectors

### test 2 :  
* [V1] :
    * basic force interactions applying gravity force and move force
    * green line shows moveForce vector (for a future update it may be cool to control it by user input (simple to do) => DONE)
    * red line shows gravity vector (for a future update it may be cool to angle it toward another element to see gravitational movements)
    * cyan line shows the processed velocity of the body (the cube) (from all forces)
* [V2] :
    * handle user input (ZQSD or ArrowKeys)
    * Added inertia (momentum? 'don't know the exact term)  
        * new guizmos : 
            * fixed green is the normalized user inputs direction
            * fixed red is this same direction with inertia
* [V3] :
    * now move on 3D plan
    * jump (with space)
    * ground collision
    

# Ideas for later (maybe one day...) :  
* interractive vertex shader, subdivide mesh and apply locale modifications around cursor
* stream webcam input in material texture
* apply GPU realtime filter on image (e.g: chromakey on webcam stream (improvement of the canvas playground project))
* complex user input handler (keys, mouse, touchScreen, controllers, sensors)
* GPU based basic particles system
* GPU based physx
* learn how light stuff works
* basic ray-tracing implementation
* procedural mesh generation (basic terrain shape)
* procedural animated (vertex)shader
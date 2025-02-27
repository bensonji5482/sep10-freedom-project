# Entry 4
##### Benson Jiang
##### 2/24/2025

## Tool Chosen
The tool that I chose is AFrame and the way I tinkered with it is by testing what the code does and how it changes the simulation after I test the simulation by using `http-server` in my IDE as I thinkered the AFrame code there. I learned some things about AFrame which I learned can help support me later on as I move forward in class. The 3 things I fist learned is that the 1st number controls the direction the shape is moving left and right, the 2nd number controls the shape up and down and 3rd number controls moves the shape forward and backward in the perspective when you first spawn into the simulation.

### Ways I tinkered with Aframe
```language
<a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
<a-sphere position="0 1.25 -5" radius="0.75" color="#EF2D5E"></a-sphere>
<a-cylinder position="0 0.75 -5" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
<a-plane position="0 0 -4" rotation="-90 0 0" width="99" height="99" color="#7BC8A4"></a-plane>
```
This code above is how I first started to see in Aframe (the numbers are modified not the original one). Then I started teaching myself how to use it at first and I was thinking if there is code that are shapes in Aframe I should be able to try and add more shapes of my own into the simulation so I ended up adding...
```language
<a-tetrahedron position="-5 0.5 -7" rotaion="0 45 0" height="2" color="red"></a-tetrahedron>
<a-cone position="2 0.5 -3" radius="0.5" height="1.5" color="green"></a-cone>
```
This is what I added as a tetrahedron is a trianglar pyramid in Geometry. In order to add this shape I first tried using pyramid rather than tetrahedron given that I didn't know the word or what it was actually called in Aframe I tried it and it didn't work as no other shapes showed up and this was before I added the code of the cone to the snippet.

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)

# Tool Learning Log

## Tool: **Aframe (For Freedom Project)**

---

### 3/4/2025:
* I used aframe for my freedom project and I learned some things about aframe.

#### Things I learned
* I learned that I can create shapes as long as it has the right name to it such as instead of `pyramid` use `tetrahedron` because it is more like a triangular prism.
* I learned that it is a simulation where you can move around in making it a virtual reality for creations that you want to use.
* The numbers that are in the code controls a specifc guideline. Such as the 1st number controls the direction left and right, the second controls up and down while the last goes backwards.

```language
<a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
<a-sphere position="0 1.25 -5" radius="0.75" color="#EF2D5E"></a-sphere>
<a-cylinder position="0 0.75 -5" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
<a-plane position="0 0 -4" rotation="-90 0 0" width="99" height="99" color="#7BC8A4"></a-plane>
/* Split Here */
<a-tetrahedron position="-5 0.5 -7" rotaion="0 45 0" height="2" color="red"></a-tetrahedron>
<a-cone position="2 0.5 -3" radius="0.5" height="1.5" color="green"></a-cone>
<a-sky color="lightblue"></a-sky>
```
* The first four were original shapes of the simulation while I modified the numbers. I ended up learning 2 new shapes for the simulation and learned how to change sky color with it already being there at the start.

### 3/10/25:
#### Found a source to help me with Aframe
* I found a source that helps me with aframe and I found the source because I wanted shapes and I searched `all shapes in aframe` on google and I found this [github file](https://github.com/aframevr/aframe/blob/master/docs/components/geometry.md) that had everything about the most or all the components of Aframe and that helped me with shapes because I ended up learning more shapes in aframe which ma come in handy in the future.
```langauge
<a-torus position="1 3 -4" radius="0.75" height="0.5" color="cyan"></a-torus>
<a-octahedron position="3 1 -7" radius="0.75" height="1.5" color="green"></a-octahedron>
```
* I learned new shapes such as the `torus` which is a 3d verison of a `ring` and a `octahedron` which is a 3d verison of a `diamond` and I plan to use most of the shapes that I can find it the [github file](https://github.com/aframevr/aframe/blob/master/docs/components/geometry.md) and to study the components on days that I have to do the freedom project specifically speaking as `Freedom Mondays.`

### 3/17/2025
#### Challenges that I have
* First I noticed that I am only using some 3d shapes and I thought to try and use some 2d shapes so I did and the problem being is that i tried to make the shape show 2 ways instead of showing just one direction and I found no solution to it as that is a big problem for me because I can't show my design for my topic properly. And the thing I did was ...
```langauge
<a-ring position="8 3 -2" radius="0.75" height="0.5" color="cyan"></a-ring>
<a-circle position="3 2 -7" radius="0.75" height="1.5" color="green"></a-circle>
<a-triangle position="4 2 -6" radius="0.75" height="1.5" color="red"></a-triangle>
```
* I made my resolve to try and see if there may be solutions to fix my problem after seeing what I had to deal with. I will also try to tinker a bit more often so I can understand the material better.

### 3/24/2025
#### Things I started to do and some more things I learned
So now I got far in learning my freedom project tool and I started to make a chessboard since it is related to my topic so I made it using many many lines of code and some number tinkering for the postion of the piece and I made ...
```langauge
<a-plane position="1 -3.3 -11" rotation="-90 0 0" width="20" height="20" color="lightblue"></a-plane>
<a-plane position="-6 -3 -4" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="-4 -3 -4" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="-2 -3 -4" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="0 -3 -4" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="2 -3 -4" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="4 -3 -4" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="6 -3 -4" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="8 -3 -4" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>

<a-plane position="-6 -3 -6" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="-4 -3 -6" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="-2 -3 -6" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="0 -3 -6" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="2 -3 -6" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="4 -3 -6" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="6 -3 -6" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="8 -3 -6" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>

<a-plane position="-6 -3 -8" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="-4 -3 -8" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="-2 -3 -8" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="0 -3 -8" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="2 -3 -8" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="4 -3 -8" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="6 -3 -8" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="8 -3 -8" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>

<a-plane position="-6 -3 -10" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="-4 -3 -10" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="-2 -3 -10" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="0 -3 -10" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="2 -3 -10" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="4 -3 -10" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="6 -3 -10" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="8 -3 -10" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>

<a-plane position="-6 -3 -12" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="-4 -3 -12" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="-2 -3 -12" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="0 -3 -12" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="2 -3 -12" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="4 -3 -12" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="6 -3 -12" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="8 -3 -12" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>

<a-plane position="-6 -3 -14" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="-4 -3 -14" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="-2 -3 -14" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="0 -3 -14" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="2 -3 -14" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="4 -3 -14" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="6 -3 -14" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="8 -3 -14" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>

<a-plane position="-6 -3 -16" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="-4 -3 -16" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="-2 -3 -16" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="0 -3 -16" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="2 -3 -16" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="4 -3 -16" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="6 -3 -16" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="8 -3 -16" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>

<a-plane position="-6 -3 -18" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="-4 -3 -18" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="-2 -3 -18" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="0 -3 -18" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="2 -3 -18" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="4 -3 -18" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
<a-plane position="6 -3 -18" rotation="-90 0 0" width="2" height="2" color="white"></a-plane>
<a-plane position="8 -3 -18" rotation="-90 0 0" width="2" height="2" color="black"></a-plane>
```
Each plane represents one square of the chessboard which took much effort to produce which also means big progress towards the final freedom project. Another thing I learned about the 3 numbers that postions the pieces are ... 
```language
1st number controls (negtaive number) left and (positive number) right
2nd number controls (positivenumber) up and (negative number) down
3rd number controls (negative number) forward and (positive number) backward
```
This also helped me make the board otherwise I would have a hard time figuring out directions of where each square goes to a certain postion.

### 3/31/2025
#### Challenges that I starting to face
When I made my chessboard as seen above I went ahead and attempted to make another one to the left of it but smaller for one of my inventions in the freedom project. I started having trouble with the first line and I plan to fix it when I am tinkering. The problem is that the directions of the pieces are going left and right because I was trying to do them like how I did it before which was a big mistake and before long I messed up on my code. This means yhat I have to learn my directions for the pieces to get control of it back again so by tinkering I can fix it.

```language
<a-plane position="-16 -3 -18" rotation="-90 0 0" width="1" height="1" color="white"></a-plane>
<a-plane position="-14 -3 -18" rotation="-90 0 0" width="1" height="1" color="black"></a-plane>
<a-plane position="-12 -3 -18" rotation="-90 0 0" width="1" height="1" color="white"></a-plane>
<a-plane position="10 -3 -18" rotation="-90 0 0" width="1" height="1" color="black"></a-plane>
<a-plane position="12 -3 -18" rotation="-90 0 0" width="1" height="1" color="white"></a-plane>
<a-plane position="14 -3 -18" rotation="-90 0 0" width="1" height="1" color="black"></a-plane>
<a-plane position="16 -3 -18" rotation="-90 0 0" width="1" height="1" color="white"></a-plane>
<a-plane position="18 -3 -18" rotation="-90 0 0" width="1" height="1" color="black"></a-plane>
```

### 4/7/2025
#### Things I started learning while making chess pieces as my topic for freedom project
I started using some shape combinations when I was trying to make my pieces. For example when I made my bishop I used 1 sphere and 2 cones with the cones being on the bottom and stacked on top of each other while the sphere stayed at top. The code that I used to make my bishop while tinkering in aframe is shown below this text.

```language
<a-plane position="-23 -3 -8" rotation="-90 0 0" width="1" height="1" color="black"></a-plane>
<a-cone position="-23 -2.5 -8" geometry="radiusBottom: 0.36; radiusTop: 0.1" color="#22BCF2" height="1.1"></a-cone>
<a-cone position="-23 -2 -8" geometry="radiusBottom: 0.32; radiusTop: 0.1" color="#22BCF2" height="1.1"></a-cone>
<a-sphere position="-23 -1.8 -8" radius="0.25" color="#22BCF2"></a-sphere>
```
The plane shown is for where the bishop is placed on the board, the cone that comes first stays at the very bottom barely touching the plane, next the second cone that comes is stacking on top of the first cone making its shape, lastly the sphere that is shown up top is somewhat below the top of the second cone to make the bishop look like it has 2 spheres on top to also make it more similar and alike to the bishop that is normally used in chess.


<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->

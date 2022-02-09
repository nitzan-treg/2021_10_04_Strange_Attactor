#  Strange Attractor
This project is based on Entagma's tutorial: https://entagma.com/vex-in-houdini-strange-attractors/
the tutorial teachs how to create an attractor by following a differtial equation from the site http://3d-meier.de/

I found a way to optemize the setup by running the whole simulation inside a single attribute wrangler where each step is run over in a for() loop, this optimization is about 500 times faster and can be developed further to be multithreaded

<img src="Images/Node Tree.png"  >
<img src="Images/2021_10_07_Abstract%20Art.jpg" width = 1024 >





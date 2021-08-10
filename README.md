# Room_Layout_Recommendation_System
## Installation
Please install the dependencies via conda:
 * PyTorch >= 1.0.0
 * networkx
 * numpy
 * Python >= 3.6

## Introduction

It's a recommendation system which produces different kinds of furniture layout for a room in a 2D simulation environment. 

One model recommend 5 kinds of different furniture layout in a 2D simulation environemnt for the room incudling typical bedroom, U-shape bedroom, L-shape bedroom, two-shape-bedroom and child bedroom. The running time on a GPU is 0.2~0.3s.

![Typical Layout](bedroom2.jpg)

![L Layout](bedroom1.jpg)

![U_Layout](bedroom6.jpg)

![Two-shape_Layout](bedroom3.jpg)

![Child Layout](bedroom4.jpg)

One model recommend 2 kinds of different furniture layout in a 2D simulation environment for the livingroom including the parallel and the vertical livingroom. The running time on a GPU is 0.2~0.3s.

![Parallel](livingroom1.jpg)

![Vertical](livingroom2.jpg)

One model recommend 4 kinds of different furniture layout in a 2D simulation environemnt for the kitchen including the one-line, the L-line, the U-line and the two-lines. Both the area and 5 key cabinets(ice-box|cut|cook|middle|wash|) are predicted.

![one-line](kitchen1.jpg)
![two-line](kitchen2.jpg)
![U-shape](kitchen3.jpg)
![L-shape](kitchen4.jpg)

Other kinds of layout recommendation will be predicted soon.

Please contact deepearthgo@gmail.com if have any questions.


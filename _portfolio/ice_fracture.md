---
title: "Ice fracture"
excerpt: "Material conditions that permit fracture in glacier ice<br/><img src='/images/skaftarkatlar-2015-atlantsflug.jpg'>"
collection: portfolio
---

I am interested in how and why glacier ice breaks.  Understanding the conditions and material properties that
permit ice fracture will help inform our representation of iceberg calving in ice-sheet models, and that, in turn,
will help us make better estimates of future ice loss due to calving.

My work combines theory (viscoelastic and plastic rheologies to approximate rapid ice collapse),
cutting-edge remote sensing data (2-m resolution digital elevation model from [ArcticDEM](https://www.pgc.umn.edu/data/arcticdem/)),
and numerical modelling (particle-based simulations in [LAMMPS](https://lammps.sandia.gov/doc/Manual.html))
to develop a well-rounded picture of the ice fracture process.

## Example: Ice cauldron collapse 
Usually, the ice at Eastern Skaftá ice cauldron, Iceland, is supported by some volume of subglacial water.  Every few years, though, the water drains suddenly downstream and the ice is left unsupported.
The resulting deformation is large and rapid.  We are fortunate to have ArcticDEM observations of the ice surface elevation from very shortly after an October 2015 collapse of
the Eastern Skaftá Cauldron.  

![Skafta-transects](http://ehultee.github.io/images/20190822-transect_compos.jpeg)

The image above shows the difference in ice surface elevation, in m, before and after the cauldron's 2015 collapse.  At right are transects sampling the observed pre- and post-collapse surfaces (dashed and solid black lines, respectively).
In solid green, you can see a deformation profile calculated using a linear elastic rheology.  Dashed green lines show profiles resulting from continued viscous deformation after an initial elastic drop.  
Notice also that you can see ice surface crevasses near the edges of the cauldron in the ArcticDEM observations.
We use the locations of those crevasses, and the stresses associated with the ice deformation, to estimate how much stress glacier ice can withstand before it breaks.

You can check out the code for viscoelastic cauldron collapse (using the wicked-cool correspondence principle, which relates elastic and viscoelastic solutions through a Laplace transform) in [this GitHub repo](https://github.com/ehultee/VE-cauldrons).  To run it you'll need some data files that are too big to store on GitHub--please email me if you need them.


## Collaborators
Colin Meyer (Dartmouth), Brent Minchew (MIT), Alex Robel (Georgia Tech), Tómas Jóhannesson (Icelandic Met Office)

## Publications
Ultee, L., Meyer, C. R. and Minchew, B. M. (2020). "Tensile strength of glacial ice deduced 
from observations of the 2015 eastern Skaftá cauldron collapse, Vatnajökull ice cap, Iceland." 
<i>Journal of Glaciology</i> <a href='https://doi.org/10.1017/jog.2020.65'>doi:10.1017/jog.2020.65</a>

Bassis, J. N. and Ultee, L. (2019). &quot;A thin film viscoplastic theory for calving 
glaciers:toward a bound on the calving rate of glaciers.&quot; <i>Journal of Geophysical 
Research: Earth Surface</i> 124. <a href='https://doi.org/10.1029/2019JF005160'>doi:10.1029/2019JF005160</a>

Ultee, L. and Bassis, J. N. (2016). &quot;The future is Nye: an extension of the perfect 
plastic approximation to tidewater glaciers.&quot; <i>Journal of Glaciology</i>. 62(236): 
1143-1152. <a href='https://doi.org/10.1017/jog.2016.108'>doi: 10.1017/jog.2016.108</a>


## Extensions
Findings about the material properties of ice can inform process modelling and broader-scale model parameterizations of iceberg calving.
Further, the study of ice deformation and fracture has appealing similarities to the study of rock deformation and fracture.
New collaborations applying insight from rock mechanics to ice, or vice versa, would be very interesting.

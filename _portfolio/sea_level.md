---
title: "Global sea level rise"
excerpt: "How fast can glaciers shed mass to icebergs?<br/><img src='/images/SLE-smb_forced-min2c_ice-example.png'>"
collection: portfolio
---


As the climate warms, glaciers and ice sheets shed mass to the ocean, and sea levels rise.  That shedding of ice mass can happen through melting,
breaking off of icebergs, or changes in glacier flow.  The latter two comprise "dynamic mass loss" and have been a major source of uncertainty
in projections of 21st-century sea level change.

I have written a model called SERMeQ - the Simple Estimator of Retreat Magnitude and ice flux (Q) - 
to produce an upper-bound estimate on calving glaciers' contribution to 21st-century sea level 
rise. The model is applicable to any marine-terminating glacier whose front is not floating.  One 
important application is to study changes on each of the 200 outlet glaciers draining the Greenland Ice Sheet.

## Example
Below is an animation of a SERMeQ-simulated retreat on Columbia Glacier, Alaska.  We see a profile of the glacier (grey) along
a centerline. The grey glacier ice flows from figure left to right over bedrock (brown) down to the sea (blue).  Observed glacier profiles appear
in purple for comparison.

![Animation of Columbia Glacier, AK](https://ehultee.github.io/files/Columbia-1980_2010-retreat.gif)

You can check out the core model code for SERMeQ in [this GitHub repo](http://github.com/ehultee/SERMeQ).  SERMeQ is under active (re)development; please do drop a line with any questions about your specific use case.

## Collaborators
Jeremy Bassis (University of Michigan), Anna Chau (MIT undergraduate)


## Publications
Ultee, L. and Bassis, J. N. (2020). &quot;SERMeQ model produces a realistic upper bound on 
calving retreat for 155 Greenland outlet glaciers.&quot; <i>Geophysical Research Letters</i> 
<a href='https://doi.org/10.1029/2020GL090213'>doi:10.1029/2020GL090213</a>

Bassis, J. N. and Ultee, L. (2019). &quot;A thin film viscoplastic theory for calving 
glaciers:toward a bound on the calving rate of glaciers.&quot; <i>Journal of Geophysical 
Research: Earth Surface</i> 124. <a href='https://doi.org/10.1029/2019JF005160'>doi:10.1029/2019JF005160</a>

Ultee, L., Arnott, J. C., Bassis, J. N., and Lemos, M. C. (2018). &quot;From ice sheets to 
main streets: Intermediaries connect climate scientists to coastal adaptation.&quot; 
<i>Earth&apos;s Future</i> 6(3): 299-304. <a href='https://doi.org/10.1002/2018EF000827'>doi:10.1002/2018EF000827</a>

Ultee, L. and Bassis, J.N. (2017). &quot;A plastic network approach to model calving glacier 
advance and retreat.&quot; <i>Frontiers in Earth Sciences</i>. 5(24). 
<a href='https://www.frontiersin.org/articles/10.3389/feart.2017.00024/full'>doi:10.3389/feart.2017.00024</a>

Ultee, L. and Bassis, J. N. (2016). &quot;The future is Nye: an extension of the perfect 
plastic approximation to tidewater glaciers.&quot; <i>Journal of Glaciology</i>. 62(236): 
1143-1152. <a href='https://doi.org/10.1017/jog.2016.108'>doi: 10.1017/jog.2016.108</a>


## Extensions
Perhaps the most exciting use of SERMeQ is as a module within a more sophisticated global model.  For example, SERMeQ could produce a calving criterion to describe a moving ice-ocean boundary in Earth system models.  Please get in touch if you're interested in exploring this idea.
Be on the lookout as well for the core physics of SERMeQ to be incorporated into a new module of the Open Global Glacier Model: development proceeding in 2022!
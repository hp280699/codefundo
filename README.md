# cyclone path predictor

You suddenly get an alert that a cyclone has taken birth close to where you live. How do you predict the course of this cyclone? How do you know whether you are safe or you have to evacuate? To answer all this and more, we have come up our app. 

So, basically there is recurvature of the paths of cyclones due to their forced precession with the rotation of the earth. Due to this fact cyclones in the northern hemisphere gets accelerated towards north pole and cyclones of southern hemisphere towards south pole. This is the major driving force of cyclones and approximated path of the cyclone can be predicted if we are able to account for this force.

The explanation for recurvature lies in the fact that cyclones possess angular momenta with respect to their spin axes. This will be referred to as their spin angular momenta. They also possess angular momenta with respect to the axis of rotation of the Earth, which will be called their terrestrial angular momenta. The turning of the spin angular momentum vector with the rotation of the Earth is a forced precession which creates a torque on the cyclone that accelerates it toward the nearest pole.

<b>dL/dt = Ldk/dt = L(Ω×k)</b>

L is the magnitude of the spin angular momentum of a cyclone,<br>
Ω is the angular velocity vector for the Earth's rotation,<br>
k= unit vector along radial direction of earth

If the cyclone is to be carried along at the same latitude there must be a force of -(LΩ/r)cos(φ) applied to it. In the absence of such a force the cyclone will move poleward subject to a force equal to (LΩ/r)cos(φ). This is analogous to the matter of centrifugal force on a body moving in a circular orbit. Here φ is the angle made by the cyclone from earth's axis.

So we can get the polewards force on a cyclone by the above equation. To calculate L of cyclone we will first observe the cyclone for some time and calculate average acceleration. Comparing average acceleration and force in that period of time we can get L of cyclone which we will consider as constant for furthur analysis. We will do this calculation for small change in latitude such that force can be taken as constant.

So basically we will track the path of the cyclone for some initial time and record changes in latitude of the cyclone and calculate its angular momentum (L). Having this data we can find the position of cyclone after a particular interval and again on that predicted position we can find the force on cyclone and predict the location of the cyclone again. doing this we can get a series of points on the map of the world. This will enavle us to find the land on which cyclone will strike.

This technique will not give us very good results but our technique is self correcting because each time the cyclone changes position, the position of all points changes accordingly so as the cyclone will come closer to land we will get better results.

Learn how to use the JADE virtual machine to have a first look at JADE events and use analysis tools:

1. ["How do I start JADE software?"](#start)
2. ["What kind of JADE data will I work on?"](#data)
3. ["I have installed VirtualBox, downloaded JADE VM image and launched it. And now?"](#vbox)
4. ["What can I learn from this exercise?"](#learn)
5. ["How does the Event display exercise work?"](#eve)
6. ["How does the D<sup>0</sup> lifetime fitting exercise work?"](#fit)

## <a name="start">"How do I start JADE software?"</a>

JADE software comes via a virtual machine image. The only thing you need
 to install by yourself on you desktop is VirtualBox. Then you just need
  to download the JADE virtual machine image open it with VirtualBox and
   click on the LHCMasterclass icon on the desktop. (see instructions [here](../virtual-machines-jade/jade.md) )

## <a name="data">"What kind of JADE data will I work on?"</a>

The data samples you can download from this portal consists all events collected by the JADE. 



## <a name="vbox">"I have installed VirtualBox, downloaded JADE VM image and
 launched it. And now?"</a>

The JADEMasterclass exercise is divided into two parts: the Event Display and 
the D<sup>0</sup> lifetime fitting exercise, which should be executed in this order.

Once you click on the icon JADEMasterclass you will be asked to select a language, 
enter your details and select the sample you want to analyse.

After clicking on the `Save` button, you can start the Event Display. If you 
want to move directly to the second exercise, just click on Move on to D<sup>0</sup> exercise.


## <a name="learn">"What can I learn from this exercise?"</a>

You will be working on real collisions recorded by the JADE experiment 
during 2011 data taking, which contain both signal and background 
particles. This set of two exercises is designed to teach you how to

*   Use an event display of the proton-proton collisions inside the JADE detector 
*   Use an event display of the proton-proton collisions inside the JADE detector 


## <a name="eve">"How does the Event display exercise work?"</a>

The aim of the event display exercise is to locate displaced vertices belonging to
 D<sup>0</sup> particles in the vertex detector of the JADE experiment. When you 
 launch the exercise and load an event, you will see an image of the JADE detector
  and particle trajectories ("tracks") inside it. These tracks are colour coded, and a
   legend at the bottom of the GUI tells you which colour corresponds to which kind of particle.

In order to make identifying vertices easier, you can view an event in three different
 two-dimensional projections : `y-z`, `y-x` and `x-z`, show for one event the following pictures:

<img src="/static/docs/getting-started-with-jade/get_started_jade_1.png" width="70%">

<img src="/static/docs/getting-started-with-jade/get_started_jade_2.png" width="70%">

<img src="/static/docs/getting-started-with-jade/get_started_jade_3.png" width="70%">

Different events will be clearer in different projections, so feel free to experiment 
with all three! Displaced vertices appear as a pair of intersecting tracks, far away 
from the other tracks in the event. When you click on a particle, you will see its 
information, including mass and momentum, in the Particle Info box. A D<sup>0</sup> 
particle decays into a kaon and a pion, so you will need to find a displaced vertex 
where a kaon track intersects with a pion track. Once you find a track which you think 
is part of the displaced vertex, you can save it using the `Save Particle` button. 
Once you have saved two particles, you can compute their mass by clicking on the 
`Calculate` button. If you think this combination has a mass compatible with that 
of the D<sup>0</sup> particle, click on Add to save it : by saving a combination 
for each event, you will build up a histogram of the masses of the displaced vertices 
in the different events.

Remember that you are looking at real data so it contains both signal and background, 
and the detector has a finite resolution, so not all displaced vertices will have exactly 
the

## <a name="fit">"How does the D<sup>0</sup> lifetime fitting exercise work?"</a>

Before describing the fitting part of the exercise, it will be useful to list the 
variables involved in this exercise :


* * *

**Exercise 1** : fitting the mass distribution and obtaining signal variable 
distributions The object of this exercise is to fit the distribution of the 
D<sup>0</sup> mass variable, and extract the signal yield and purity.

*   Click on the `Plot` D<sup>0</sup> mass button to plot the overall mass 
distribution. 

**Exercise 2** : measuring the D<sup>0</sup> lifetime The object of this exercise 
is to use the signal sample which you obtained in the previous step to measure the 
lifetime of the D<sup>0</sup> particle. This is the same quantity as the half-life 
of a radioactive particle: the D<sup>0</sup> decays according to an exponential 
distribution, and if this exponential is fitted to a distribution of the D<sup>0</sup> 
decay times, the slope of this exponential is the lifetime of the D<sup>0</sup>.

*   Fit the lifetime of the D<sup>0</sup>.

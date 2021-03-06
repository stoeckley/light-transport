# Light Transport Sandbox

<p align="center">
  <img src="https://raw.githubusercontent.com/ddiakopoulos/light-transport/master/assets/1024_spp.png"/>
</p>

In the middle of building the rendering and composition stack for Intel's Project Alloy, I elected to take a brief vacation from working on a 11.11ms VR render budget to build this project, a toy Monte Carlo unidirectional path tracer. It features a multi-threaded render loop, tent-filtered jittered sampling scheme, and a variety of geometric primitives. Bugs are highly likely in this code!

# Attribution

Various projects were studied during the development of this, notably Benedikt Bitterli's Tungsten, Fabrizio Duroni's SCLT, and PBRTv3. Other educational sources are listed in the header of `main.cpp`. 


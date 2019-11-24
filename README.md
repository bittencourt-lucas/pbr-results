# Physically Based Rendering - Results
This repository will be used to post the results from my Physically Based Rendering class at Universidade Federal da Paraíba. My name is **Lucas Cafieiro Bittencourt Lima**, and I'm a Computer Science undergraduate.

# Activity 1: Use an existing renderer to create a scene

## Blender 2.81

This is a simple, kind of messy image. I'll study Blender a little further and research better materials (such as the gold in Suzanne, which is much better than the "gold" on the sphere) to create a more interesting, photorealistic scene, that I plan on using as the final project of the class.

![First Example](activity1/Example1.jpg)

This image was rendered using Cycles, with 1920x1080 pixels of resolution, and the path tracer was configured to use 1000 samples per pixel. The cups are using the default Glass BSDF as a material. The golden and the iron sphere were rendered using the default Glossy BSDF as a material. The pink sphere is using the default Diffuse BSDF as a material. The glowing sphere uses a Translucent BSDF as a material, with an Emission with 50.0 of strength. The Suzanne model uses a mix of two Glossy BSDFs as materials. Finally, the table and the floor both have a mix of a default Diffuse BSDF and a Glossy BSDF with a roughness value of 0.173. The light source outside the scene has a strenght of 1000.0.
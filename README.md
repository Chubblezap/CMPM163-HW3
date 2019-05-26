# CMPM163-HW3
Austin Wiley's Homework 3 for CMPM163.

An explosion particle system, which was my attempt at making something in ShaderLab. It uses a noise texture to distort a high-poly sphere, and color itself based on distance from its center. It also has a dissolve effect, which uses a different noise texture and a time variable. I wasn't able to make each particle have its own time variable since apparently Unity doesn't support per-particle data very well, at least not to any point where I could understand it.

Arrow keys control some size variables, with Up/Down controlling the overall size and Left/Right controlling the "spikiness", and by extension the overall coloration. 

The fire particle is more simple, being made entirely with a custom sprite I made and some particle configuration. The size of the particles changes based on the relative volume of the background music.

Background music is Crypt of the Necrodancer - Tombtorial.

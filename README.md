# PRO-C186-Code-Ref

for more examples refer:

https://github.com/subhrapattnaik/A-Frame-Examples




https://www.npmjs.com/package/aframe-spe-particles-component


The spe-particles component provides a wrapper around the Shader Particle Engine by SquareFeet, for generating GPU based particle systems in A-Frame. The system supports single textures and spritesheets, settings for position, velocity, acceleration, color, opacity, rotation, size, drag and wiggle.
----------------------------------------------------------
A particle system is a technique in game physics, motion graphics, and computer graphics that uses many
minute sprites, 3D models, or other graphic objects to simulate certain kinds of "fuzzy" phenomena,
which are otherwise very hard to reproduce with conventional rendering techniques


add the entity and attach the spe-particles component
There are many properties that can be set for this component, but we will set a few and test the output

● color: list of colors for the
particles;
● distribution: shape of particles
distribution;
● randomize-velocity: whether to
set the random velocity of the
particles or not;
● radius: radius of the shape of
the distribution;
● particle-count: number of
particles;
● velocity: velocity of the
particles;
● velocity-spread: how far the
velocity must be spread before
becoming zero;
● drag: to apply resistance on the
moving particles(between 0,no
resistance and 1, full
resistance);
● max-age: age of the particle
before reusing it;
● duration: duration (in seconds)
of emitting particles that how
long the particles will keep
emitting, to emit particles
continuously value has to be
less than 0;
● blending: how the particles
must blend in while created;
● active-multiplier: to increase
the rate of emission of particles;
● size: list of numbers(max 4 in
the list) to set the size of the
particles

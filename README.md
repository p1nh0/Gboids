Gboids
======

Granular synth driven by boids, an agent simulation algorithm.

This patch uses an implementation of Craig Reynolds' "boids" algorithm 
(available in Max Javascript Examples) to drive a granular synthesizer, 
where each agent represents a grain, scrubbing an audio sample 
as it moves in a two-dimensional space.
This brings a semantic change to the sound synthesis model, like position, 
grain size, etc. to semantics related to motion and collective behaviour, 
like inertia, alignment and separation.

System Requirements: 
- MaxMSP 5/6


For more info on boids/agent simulation check out Craig Reynolds' site: http://www.red3d.com/cwr/

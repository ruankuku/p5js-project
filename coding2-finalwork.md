

## FinalProject #

**Student Name (Id#):** Zhaoke Ruan（24010429）

**Sketch Link:** 

[[Chronos Unbound](https://editor.p5js.org/ruankuku188/sketches/1Kbr8elw5)]

[[My website](https://git.arts.ac.uk/pages/24010429/24010429.github.io/)]

**Project Video:** 

[[My video](https://ual.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=5bfe5b88-5232-4f2b-bf1e-b2a800607aa9)]

**Project Description**

The Work

"Chronos Unbound" is an interactive generative art installation that interrogates the fluidity and instability of temporal perception. By creating a virtual time system that flows backward and bends under user interaction, the project destabilizes the linear, clock-driven construct of time, inviting participants to question its presumed objectivity. Built with p5.js, the work combines dynamic grid deformations, audio manipulation, and procedural time distortion to craft an experience where users manipulate time’s “fabric” through mouse movements, warping both visual and auditory representations of temporal flow. The intended experience oscillates between disorientation and revelation—viewers confront time not as a fixed arrow but as a malleable field shaped by observation and interaction.

Production Methodology

The project leverages p5.js for real-time graphics and Web Audio API for sound synthesis. Key technical components include:

  Noise-driven Grid Deformation: Perlin noise algorithms distort a 2D grid (18x50 cells), simulating spacetime curvature. Vertex displacements are calculated using noise() functions with time-dependent seeds, mapped to sinusoidal wave patterns.

  Interactive Time Dilation: Mouse proximity triggers Lorentz transformation-inspired distortions. The mouseX position modulates both visual ripple effects (via wave equations) and audio playback speed, linking spatial interaction to temporal perception.

  Retrograde Chronometry: Time is inverted—seconds count backward from 59, minutes from 59, creating a mirrored clock. The mapTimeToGrid() function renders this via custom 8x5 pixel fonts, distorted using vertex displacement based on grid cell states.

  Audio-Time Entanglement: A looping clock sound (loaded via loadSound()) pitch-shifts dynamically using sound.rate(), its frequency tied to mouse distance from a focal point (650,200), producing Doppler-like effects.

External references include Daniel Shiffman’s generative art pedagogy (Nature of Code), Bergson’s durée philosophy and the chronophobic aesthetics of Ryoji Ikeda’s datascapes.

Motivation and Key Context

The project stems from a fascination with the dual role of time as a physical constant and a cultural construct. The project began when I noticed that the time on two cell phones was very different, with one being nearly five days slower than the other. This made me question the concept of time. Space-time, as the fourth dimension of the world, should be stable and uniform for this to be convincing, but seeing the time scale change on the two phones made my concept of time collapse. Therefore I wanted to simulate the notion of relative time using inverted clocks and variable grids as metaphors for the challenges of classical temporality, inviting users to visualize the instability of time and imagine temporality unfettered by algorithmic management.

In the lead up to this project, I also did some research on time. From the existential tension in Christian Marclay's The Clock, to the aesthetics of mutation in JODI's software art, from the inversion of time in the film Tenet, to the time travel in the film Interstellar, I realized that the exploration of this dimension of space-time never stops. If there is time to explore these types of projects in the future, I would like to represent the concepts in a more artistic and abstract way. I want to delve into how code can materialize abstract philosophical concepts and increase the depth and thickness of my exploration of the nature of things, which will also bring new breakthroughs to my code work.

**Project Images** 

![宇宙](https://git.arts.ac.uk/24010429/CCI-Course-Notebook-2/assets/1205/88d204aa-b719-40e9-86c0-bbc3a1f04b29)

<img width="794" alt="image" src="https://git.arts.ac.uk/24010429/CCI-Course-Notebook-2/assets/1205/b347f453-0b58-46bf-804e-d5aa3dbad26b">


**References:**

When I was working on the work, I wanted the grid to show a dynamic effect of changing length and width, so I referred to [[this work](https://openprocessing.org/sketch/2544024)].

I borrowed from [[this work](https://openprocessing.org/sketch/885665)] in terms of the style and expression of distortion. It gave me some ideas, such as the distortion of the grid.

Regarding time, I found the reference in p5.js.[[hours, minute, second](https://p5js.org/reference/p5/hour/)]

I also sought help from GPT in some aspects. For example, I didn’t know how to preset the font on the grid, and AI gave me a new idea.
<img width="772" alt="image" src="https://git.arts.ac.uk/24010429/CCI-Course-Notebook-2/assets/1205/2d59a51c-e7c6-4d99-b325-7201f90cc6f6">


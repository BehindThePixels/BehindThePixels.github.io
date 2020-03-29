---
permalink: /publications/
title: "Behind the Pixels"
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/Header1.jpg
  caption: 'Rendered with EDXRay'
excerpt: ''
---

---

### A Survey of Temporal Antialiasing Techniques

**Lei Yang, Shiqiu Liu, Marco Salvi**

_Eurographics 2020, State of the Art Report_

![](/assets/images/pages/TAA.jpg){: .align-left width="600px" }
Temporal Antialiasing (TAA), formally defined as temporally-amortized supersampling, is the most widely used antialiasing technique in today’s real-time renderers and game engines. This survey provides a systematic overview of this technique. We first review the history of TAA, its development path and related work. We then identify the two main sub-components of TAA, sample accumulation and history validation, and discuss algorithmic and implementation options. As temporal upsampling is becoming increasingly relevant to today’s game engines, we propose an extension of our TAA formulation to cover a variety of temporal upsampling techniques. Despite the popularity of TAA, there are still significant unresolved technical challenges that affect image quality in many scenarios. We provide an in-depth analysis of these challenges, and review existing techniques for improvements. Finally, we summarize popular algorithms and topics that are closely related to TAA. We believe the rapid advances in those areas may either benefit from or feedback into TAA research and development.

[Preprint](/assets/files/TemporalAA.pdf)

---

### Cinematic Rendering in UE4 with Real-Time Ray Tracing and Denoising

**Edward Liu, Ignacio Llamas, Juan Cañada, Patrick Kelly**

_Ray Tracing Gems_

![](/assets/images/pages/Reflections.jpg){: .align-left width="360px" }
We present cinematic quality real-time rendering by integrating ray tracing in Unreal Engine 4. We improve the state-of-the-art performance in GPU ray tracing by an order of magnitude through a combination of engineering work, new ray tracing hardware, hybrid rendering techniques, and novel denoising algorithms.


[Pdf](https://link.springer.com/content/pdf/10.1007%2F978-1-4842-4427-2_19.pdf)

---

### Spatiotemporal Variance-Guided Filtering: Real-Time Reconstruction for Path-Traced Global Illumination

**Christoph Schied, Anton Kaplanyan, Chris Wyman, Anjul Patney, Chakravarty R. Alla Chaitanya, John Burgess, Shiqiu Liu, Carsten Dachsbacher, Aaron Lefohn, Marco Salvi**

_High Performance Graphics 2017 (Best Paper Award)_

![](/assets/images/pages/SVGF.jpg){: .align-left width="600px" }
We introduce a reconstruction algorithm that generates a temporally stable sequence of images from one path-per-pixel global illumination. To handle such noisy input, we use temporal accumulation to increase the effective sample count and spatiotemporal luminance variance estimates to drive a hierarchical, image-space wavelet filter [Dammertz et al. 2010]. This hierarchy allows us to distinguish between noise and detail at multiple scales using local luminance variance.
Physically based light transport is a long-standing goal for realtime computer graphics. While modern games use limited forms of ray tracing, physically based Monte Carlo global illumination does not meet their 30 Hz minimal performance requirement. Looking ahead to fully dynamic real-time path tracing, we expect this to only be feasible using a small number of paths per pixel. As such, image reconstruction using low sample counts is key to bringing path tracing to real-time. When compared to prior interactive reconstruction filters, our work gives approximately 10× more temporally stable results, matches reference images 5–47% better (according to SSIM), and runs in just 10 ms (± 15%) on modern graphics hardware at 1920×1080 resolution.

[Preprint](/assets/files/hpg17_svgf.pdf)

---

### Computer Simulations Imply Forelimb-Dominated Underwater Flight in Plesiosaurs

**Shiqiu Liu, Adam S. Smith, Yuting Gu, Jie Tan, C. Karen Liu and Greg Turk**

_PLoS Computational Biology_

![](/assets/images/pages/Underwater Plesiosaur High Res.jpg){: .align-left width="400px" }

Plesiosaurians are an extinct group of highly derived Mesozoic marine reptiles with a global distribution that spans 135 million years from the Early Jurassic to the Late Cretaceous. During their long evolutionary history they maintained a unique body plan with two pairs of large wing-like flippers, but their locomotion has been a topic of debate for almost 200 years. Key areas of controversy have concerned the most efficient biologically possible limb stroke, i.e whether it consisted of rowing, underwater flight, or modified underwater flight; and how the four limbs moved in relation to each other: did they move in or out of phase? Previous studies have investigated plesiosaur swimming using a variety of methods, including skeletal analysis, human swimmers, and robotics. We adopt a novel approach using a digital, three-dimensional, articulated, free-swimming plesiosaur in a simulated fluid. We generated a large number of simulations under various joint degrees of freedom to investigate how the locomotory repertoire changes under different parameters. Within the biologically possible range of limb motion, the simulated plesiosaur swims primarily with its forelimbs using an unmodified underwater flight stroke, essentially the same as turtles and penguins. In contrast, the hindlimbs provide relatively weak thrust in all simulations. We conclude that plesiosaurs were forelimb-dominated swimmers that used their hind limbs mainly for maneuverability and stability.

Full paper at [PLoS Computational Biology](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004605).

Press Coverage:

1. [What Looks Like a Dinosaur But Swims Like a Penguin? It’s the Meyerasaurus.](http://www.usatoday.com/story/news/2015/12/17/meyerasaurus-dinosaur-swam-like-penguin/77507996/) _USA Today, 12/18/2015_
2. [Ancient Marine Reptiles Flew through the Water](http://www.livescience.com/53150-swimming-plesiosaurs.html) _Live Science, 12/18/2015_
3. [Plesiosaurs Literally Flew through Ocean](http://www.seeker.com/plesiosaurs-literally-flew-through-oceans-1770627747.html) _Discovery News, 12/17/2015_
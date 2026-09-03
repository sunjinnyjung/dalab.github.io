---
caption:
  title: "Synthesizing Character Animation with Smoothly Decomposed Motion Layers"
  subtitle: |
    Computer Graphics Forum (CGF) <br> Eurographics 2020
  thumbnail: assets/img/publications/2019_CGF_th.png


title: "Synthesizing Character Animation with Smoothly Decomposed Motion Layers"
authors: |
  Haegwang Eom\*, Byungkuk Choi\*, Kyungmin Cho, Sunjin Jung, Seokpyo Hong, Junyong Noh<br>
  <i>\* Equal contribution</i>
journal: "Computer Graphics Forum (CGF), Volume 39, Issue 1, February 2020"
conference: "Eurographics 2020"
paper_url: "https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.13893"

image: assets/img/publications/2019_CGF.png

abstract: |
  The processing of captured motion is an essential task for undertaking the synthesis of high-quality character animation. The motion decomposition techniques investigated in prior work extract meaningful motion primitives that help to facilitate this process. Carefully selected motion primitives can play a major role in various motion-synthesis tasks, such as interpolation, blending, warping, editing or the generation of new motions. Unfortunately, for a complex character motion, finding generic motion primitives by decomposition is an intractable problem due to the compound nature of the behaviours of such characters. Additionally, decomposed motion primitives tend to be too limited for the chosen model to cover a broad range of motion-synthesis tasks. To address these challenges, we propose a generative motion decomposition framework in which the decomposed motion primitives are applicable to a wide range of motion-synthesis tasks. Technically, the input motion is smoothly decomposed into three motion layers. These are base-level motion, a layer with controllable motion displacements and a layer with high-frequency residuals. The final motion can easily be synthesized simply by changing a single user parameter that is linked to the layer of controllable motion displacements or by imposing suitable temporal correspondences to the decomposition framework. Our experiments show that this decomposition provides a great deal of flexibility in several motion synthesis scenarios: denoising, style modulation, upsampling and time warping.
---

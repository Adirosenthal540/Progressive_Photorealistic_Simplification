# Progressive Photorealistic Abstraction

<p align="center">
<img src="./images/teaser4.png" width="800px"/>
</p>

#### Adi Rosenthal, Dana Berman, Ariel Shamir, Yedid Hoshen

Traditional image abstraction relies on Non-Photorealistic Rendering (NPR) to transform photographs into stylized sketches, cartoons, or paintings. While these techniques capture a scene’s semantic essence, they sacrifice photographic realism. We propose a new perspective on abstraction: preserving an image’s photorealistic nature while progressively simplifying its visual content. We introduce Subtractive Abstraction, a framework that iteratively reduces scene complexity. By detecting, ranking, removing, and inpainting elements, our system generates a sequence of intermediate results that remain plausible as natural photographs. This approach integrates automated semantic analysis with controlled simplification, leveraging modern Vision-Language Models (VLMs) and generative inpainting. We drive the process with an iterative Select-Remove-Verify algorithm, employing a VLM for object selection and removal alongside a dedicated classifier for plausibility verification. We subsequently distill this iterative pipeline into
an image-to-video generation model. Beyond synthesizing minimal compositions from complex scenes, our method facilitates practical applications including content-aware decluttering, layering, and aesthetic enhancement. Our work provides a first hint that realism and abstraction can coexist.


<a href=""><img src="https://img.shields.io/badge/arXiv-TODO-b31b1b.svg"></a>
<a href="https://Adirosenthal540.github.io/Progressive_Photorealistic_Abstraction/"><img src="https://img.shields.io/static/v1?label=Project&message=Website&color=red" height=20.5></a> 



## 🔥 NEWS
**`2026/XX/XX`**: Progressive Photorealistic Abstraction was accepted to SIGGRAPH 26!

**`2026/XX/XX`**: Paper is out!

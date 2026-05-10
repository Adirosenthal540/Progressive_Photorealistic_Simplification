# Progressive Photorealistic Simplification

<p align="center">
<img src="./images/teaser4.png" width="800px"/>
</p>

#### Adi Rosenthal, Dana Berman, Ariel Shamir, Yedid Hoshen

Existing image simplification techniques often rely on Non-Photorealistic Rendering (NPR), transforming photographs into stylized sketches, cartoons, or paintings. While effective at reducing visual complexity, such approaches typically sacrifice photographic realism. In this work, we explore a complementary direction: simplifying images while preserving their photorealistic appearance.

We introduce progressive semantic image simplification, a framework that iteratively reduces scene complexity by removing and inpainting elements in a controlled manner. At each step, the resulting image remains a plausible natural photograph. Our method combines semantic understanding with generative editing, leveraging Vision-Language Models (VLMs) to identify and prioritize elements for removal, and a learned verifier to ensure photorealism and coherence throughout the process. This is implemented via an iterative Select–Remove–Verify pipeline that produces high-quality simplification trajectories.
To improve efficiency, we further distill this process into an image-to-video generation model that directly predicts coherent simplification sequences from a single input image. Beyond generating cleaner and more focused compositions, our approach enables applications such as content-aware decluttering, semantic layer decomposition, and interactive editing.

More broadly, our work suggests that simplification through structured content removal can serve as a practical mechanism for guiding visual interpretation within the photorealistic domain, complementing traditional abstraction methods.


<a href=""><img src="https://img.shields.io/badge/arXiv-TODO-b31b1b.svg"></a>
<a href="https://Adirosenthal540.github.io/Progressive_Photorealistic_Simplification/"><img src="https://img.shields.io/static/v1?label=Project&message=Website&color=red" height=20.5></a> 



## 🔥 NEWS
**`2026/05`**: Progressive Photorealistic Simplification was accepted to SIGGRAPH 26!

**`2026/05`**: Paper is out!

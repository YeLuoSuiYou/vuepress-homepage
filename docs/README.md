---
pageClass: home-page
# some data for the components

name: Zilyu Ye
profile: /profile.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/YeLuoSuiYou

cv: /projects/resume.pdf
bio: Student majoring in Artificial Intelligence at South China University of Technology 
email: zilyuye@foxmail.com
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

Hi, I'm Zilyu, a third-year undergraduate student majoring in Artificial Intelligence at South China University of Technology. I'm currently working on my research project on AIGC supervised by [Prof. Qi Liu](https://drliuqi.github.io/) and [Prof. Guo-Jun Qi](http://maple-lab.net/about.html). I aspire to leave a lasting impact on the realms of Finance and AI.

<span style="color: red">Sincerely looking for and internships opportunities in for Summer 2025.</span>

### Research Interests

Computer Vision, Multimodal Learning, AIGC, Diffusion Model etc.

## News

- [Nov. 2024] We submitted two works to CVPR 2025, focusing on diffusion model and MLLM.
- [May 2024] OpenStory is selected as oral presentation by VDU@CVPR 2024.

## Education & Experiences

- **South China University of Technology (SCUT)**<br/>
  Undergraduate major in Artificial Intelligence, 2022.9 - 2026.6 (expected)<br/>
- **Multimodal Computing and Emotional Interaction Lab in SCUT**<br/>
  Research intern on AIGC supervised by [Prof. Qi Liu](https://drliuqi.github.io/), 2023.11 - present<br/>
- **Machine Perception and Learning (MAPLE) Lab in Westlake University**<br/>
  Research intern on AIGC supervised by [Prof. Guo-Jun Qi](http://maple-lab.net/about.html), 2024.3 - present<br/>
- **Undergraduate Student Robotic Lab (ROBOTIC) in SCUT**<br/>
  Member of machine vision team participating in ROBOCON competition, 2022.12 - 2023.6<br/>

## Papers and Projects

<ProjectCard image="/projects/TPDM.png" hideBorder=true>

  <span style="font-size:1.1em">**Schedule On the Fly: Diffusion Time Prediction for Faster and Better Image Generation**</span>

  Zilyu Ye, *et al*

  Diffusion and flow models have achieved remarkable successes in various applications such as text-to-image generation. However, these models typically rely on the same predetermined denoising schedules during inference for each prompt, which potentially limits the inference efficiency as well as the flexibility when handling different prompts. In this paper, we argue that the optimal noise schedule should adapt to each inference instance, and introduce the Time Prediction Diffusion Model (TPDM) to accomplish this. TPDM employs a plug-and-play Time Prediction Module (TPM) that predicts the next noise level based on current latent features at each denoising step. We train the TPM using reinforcement learning, aiming to maximize a reward that discounts the final image quality by the number of denoising steps. With such an adaptive scheduler, TPDM not only generates high-quality images that are aligned closely with human preferences but also adjusts the number of denoising steps and time on the fly, enhancing both performance and efficiency. We train TPDMs on multiple diffusion model benchmarks. With Stable Diffusion 3 Medium architecture, TPDM achieves an aesthetic score of 5.44 and a human preference score (HPS) of 29.59, while using around 50% fewer denoising steps to achieve better performance.

  arxiv 2024

  [[PDF](https://arxiv.org/pdf/2412.01243)]

</ProjectCard>

<ProjectCard image="/projects/openstory++.png" hideBorder=true>

  <span style="font-size:1.1em">**Openstory++: A Large-scale Dataset and Benchmark for Instance-aware Open-domain Visual Storytelling**</span>

  Zilyu Ye, *et al*

  Recent image generation models excel at creating high-quality images from brief captions. However, they fail to maintain consistency of multiple instances across images when encountering lengthy contexts. This inconsistency is largely due to in existing training datasets the absence of granular instance feature labeling in existing training datasets. To tackle these issues, we introduce Openstory++, a large-scale dataset combining additional instance-level annotations with both images and text. Furthermore, we develop a training methodology that emphasizes entity-centric image-text generation, ensuring that the models learn to effectively interweave visual and textual information. Specifically, Openstory++ streamlines the process of keyframe extraction from open-domain videos, employing vision-language models to generate captions that are then polished by a large language model for narrative continuity. It surpasses previous datasets by offering a more expansive open-domain resource, which incorporates automated captioning, high-resolution imagery tailored for instance count, and extensive frame sequences for temporal consistency. Additionally, we present Cohere-Bench, a pioneering benchmark framework for evaluating the image generation tasks when long multimodal context is provided, including the ability to keep the background, style, instances in the given context coherent. Compared to existing benchmarks, our work fills critical gaps in multi-modal generation, propelling the development of models that can adeptly generate and interpret complex narratives in open-domain environments. Experiments conducted within Cohere-Bench confirm the superiority of Openstory++ in nurturing high-quality visual storytelling models, enhancing their ability to address open-domain generation tasks.

  arxiv 2024

  [[PDF](https://arxiv.org/pdf/2408.03695)] [[huggingface](https://huggingface.co/datasets/MAPLE-WestLake-AIGC/OpenstoryPlusPlus)]

</ProjectCard>

<ProjectCard image="/projects/OpenStory.png" hideBorder=true>

  <span style="font-size:1.1em">**OpenStory: A Large-Scale Open-Domain Dataset for Subject-Driven Visual Storytelling**</span>

  Zilyu Ye, *et al*

  Recently, the advancement and evolution of genera-tive AI have been highly compelling. In this paper, wepresent OpenStory, a large-scale dataset tailored for train-ing subject-focused story visualization models to generatecoherent and contextually relevant visual narratives. Ad-dressing the challenges of maintaining subject continuityacross frames and capturing compelling narratives, We propose an innovative pipeline that automates the extraction ofkeyframes from open-domain videos. It ingeniously employsvision-language models to generate descriptive captions,which are then refined by a large language model to ensurenarrative flow and coherence. Furthermore, advanced sub-ject masking techniques are applied to isolate and segmentthe primary subjects. Derived from diverse video sources,including YouTube and existing datasets, OpenStory offersa comprehensive open-domain resource, surpassing priordatasets confined to specific scenarios. With automatedcaptioning instead of manual annotation, high-resolutionimagery optimized for subject count per frame, and exten-sive frame sequences ensuring consistent subjects for tem-poral modeling, OpenStory establishes itself as an invalu-able benchmark. It facilitates advancements in subject-focused story visualization, enabling the training of modelscapable of comprehending and generating intricate multi-modal narratives from extensive visual and textual inputs.

  VDU@CVPR 2024, oral

  [[PDF](https://openaccess.thecvf.com/content/CVPR2024W/VDU/papers/Ye_OpenStory_A_Large-Scale_Open-Domain_Dataset_for_Subject-Driven_Visual_Storytelling_CVPRW_2024_paper.pdf)]

</ProjectCard>

## Awards & Honors

- SCUT undergraduate scholoarship, 2023&2024 -- Third Prize
- The Mathematical Contest in Modeling -- Meritorious Winner(<10%)
- Asia and Pacific Mathematical Modeling Contest —Third Prize
- National College Student Robot Contest (ROBOCON) —Third Prize
- National Undergraduate Mathematical Modeling Contest In Guangdong Province — Second Prize
- SCUT Future Technology Institute "Alibaba Cloud Cup" Programming Competition — Third Prize


<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 3000px
        max-height 300px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>

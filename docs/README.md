---
pageClass: home-page
# some data for the components

name: Zilyu Ye
profile: /profile.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/YeLuoSuiYou

cv: https://en.wikipedia.org/wiki/Harry_Potter
bio: Student majoring in Artificial Intelligence at South China University of Technology 
email: zilyuye@foxmail.com
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

Hi, I'm Zilyu, a second-year undergraduate student majoring in Artificial Intelligence at South China University of Technology. I'm currently working on my research project on AIGC supervised by [Prof. Qi Liu](https://drliuqi.github.io/) and [Prof. Guo-Jun Qi](http://maple-lab.net/about.html).

<span style="color: red">Sincerely looking for Ph.D. positions for fall 2026 and internships opportunities in for Summer 2024.</span>

### Research Interests

Computer Vision, Multimodal Learning, AIGC, Diffusion Model etc.

## News

- [March 2024] Submit a paper focusing on the open-domain visual storytelling task to CVPR 2024 workshop.

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

<ProjectCard image="/projects/OpenStory.png" hideBorder=true>

  <span style="font-size:1.1em">**OpenStory: A Large-Scale Open-Domain Dataset for Subject-Driven Visual Storytelling**</span>

  Zilyu Ye*, Jinxiu Liu*, *et al*

  Recently, the advancement and evolution of genera-tive AI have been highly compelling. In this paper, wepresent OpenStory, a large-scale dataset tailored for train-ing subject-focused story visualization models to generatecoherent and contextually relevant visual narratives. Ad-dressing the challenges of maintaining subject continuityacross frames and capturing compelling narratives, We propose an innovative pipeline that automates the extraction ofkeyframes from open-domain videos. It ingeniously employsvision-language models to generate descriptive captions,which are then refined by a large language model to ensurenarrative flow and coherence. Furthermore, advanced sub-ject masking techniques are applied to isolate and segmentthe primary subjects. Derived from diverse video sources,including YouTube and existing datasets, OpenStory offersa comprehensive open-domain resource, surpassing priordatasets confined to specific scenarios. With automatedcaptioning instead of manual annotation, high-resolutionimagery optimized for subject count per frame, and exten-sive frame sequences ensuring consistent subjects for tem-poral modeling, OpenStory establishes itself as an invalu-able benchmark. It facilitates advancements in subject-focused story visualization, enabling the training of modelscapable of comprehending and generating intricate multi-modal narratives from extensive visual and textual inputs.

  CVPR 2024 workshop, under review

</ProjectCard>

## Awards & Honors

- SCUT undergraduate scholoarship, 2022 -- Third Prize
- Excellent Group Enterprise Scholarship, SCUT, 2023 -- Third Prize
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

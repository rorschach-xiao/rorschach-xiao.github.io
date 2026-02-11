---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Short Bio
Welcome to my personal webpage! My name is **Yang Xiao** (Chinese: 肖阳). I am currently a **Researcher** at **TikTok**. Prior to that, I earned my Master's degree in Computer Science from **Northeastern University**, where I was supervised by **Ryan Rad**. I also hold a Bachelor's degree from **Beihang University**.

My research interests mainly focus on 2D computer vision, including but not limited to image classification/detection/segmentation, semi-supervised learning, contrastive learning, human image generation, diffusion model, etc. 


## 📖 Educations
- *2023.01 - 2024.08*, Master, Khoury College, Northeastern University
- *2015.09 - 2019.07*, Undergraduate, ShenYuan Honors College, Beihang University

## 💻 Experience

- *2024.04 - now*, [TikTok](https://www.tiktok.com/), Vancouver, Canada
- *2020.07 - 2021.05*, [DiDi](https://www.didiglobal.com/), Beijing, China
- *2019.12 - 2020.07*, [4paradigm](https://www.4paradigm.com/), Beijing, China
- *2019.06 - 2019.09*, [Haier Uhome](https://www.haier.com/business/smarthome/product/?spm=cn.business_smarthome_pc.header_qwzn_20210512.3), Beijing, China
- *2018.09 - 2018.12*, [ZhenRobotics](http://zhenrobot.com/index_en.html), Beijing, China

## 📚 Research
- *2024.04 - 2025*: Research Assistant
  * **Northeastern University**, Vancouver, Canada
  * Directions: Fire Prediction, Diffusion Model, Remote Sensing, etc.
  * Supervisor: [Professor Ryan Rad](https://www.khoury.northeastern.edu/home/rrad/)

## 🎓 Publications

1. **Yang Xiao**. "A Comparative Study between SLMs and LLMs in Customer Review Analysis". *Artificial Intelligence Review*, 2025. [[Paper]](https://link.springer.com/epdf/10.1007/s10462-025-11308-5?sharing_token=e9ijr3vjgNmTHZzz6hOeu_e4RwlQNchNByi7wbcMAY4Zsb07NS6Bz2anhBBv2eKO8g1mesApQB5xm72tQNuQ1R3WGw63tkLSSiiq70KxV5DQbXTxYUqW9Js-sdDcxK4BSxkT-aQorGJWiDgiosOq2qypi2PgU8qgs31r1qoudfI%3D) [[Code]](https://github.com/rorschach-xiao/CS7980-Capstone)
   * Investigated and compared the performance and computational costs of SLMs and LLMs in sentiment polarity classification and correlation analysis.

## 📝 Teaching

- **Spring 2024: Teaching Assistant**
  * **Northeastern University**, Vancouver, Canada
  * Course: Foundation of AI
  * Supervisor: [Professor Richard Hoshino](https://www.richardhoshino.com)

- **Fall 2023: Teaching Assistant**
  * **Northeastern University**, Vancouver, Canada
  * Course: Programing Desgin Paradigm
  * Supervisor: [Professor Jack Thomas](https://drjackthomas.ca/)


## 🔧 Projects

### Pet Avatar Customized and Animated Generation via Diffusion Model
<div style="display: flex;">
  <div style="width: 75%;">
    <span style="color: grey">Apr. 2024</span><br />
    <span style="font-weight: bold">Master's capstone</span><br />
    <a href="https://github.com/rorschach-xiao/PetAvatar">code</a>
    <a href="https://rorschach-xiao.github.io/PetAvatar-Gallery/">page</a><br />
    <br />
    <div>
    Built a pipeline aiming at generating pet images and videos in a personalized and customized way. To better preserve the original pet features, we followed DreamBooth + LoRA paradigm; furthermore, we inserted the LoRA weight into AnimateDiff framework to animate the original pet.
    </div>
  </div>
  <div style="width: 25%;">
    <img src='images/pet-ori.jpg' height="60%" width="90%" >
    <img src='images/pet-1.gif' width="45%" style="float: left">
    <img src='images/pet-2.png' width="45%" style="float: left">
  </div>
</div>

### Real-time Interactive Online-Classroom
<div style="display: flex;">
  <div style="width: 75%;">
    <span style="color: grey">Nov. 2023</span><br />
    <span style="font-weight: bold">Course project</span><br />
    <a href="https://github.com/rorschach-xiao/CalcSheetPro">code</a><br />
    <br />
    <div>
    Built a online classroom where students and teachers can chat and draw some sketches in real-time. The tech stack is based on Typescript, Node.js, React and Redis. To ensure real-time and low-lantency, communication between front-end and back-end was implemented via websocket.
    </div>
  </div>
  <div style="width: 25%;">
    <img src='images/classroom.png' width="100%">
  </div>
</div>


### Lane Segementation Challenge on [ApolloScape Benchmark](https://apolloscape.auto/leader_board.html)
<div style="display: flex;">
  <div style="width: 75%;">
    <span style="color: grey">Dec. 2020</span><br />
    <span style="font-weight: bold">6/94 place on lane segementation track</span><br />
    <br />
    <div>
    Combined multiple augmentation strategies, class-balanced loss functions and a sementic segmention Network(HRNet+OCR) to parse real-world image.
    </div>
  </div>
  <div style="width: 25%;">
    <img src='images/lane-segmentation.gif' width="100%">
  </div>
</div>

### Chinese Artificial [Intelligence Competition](https://ai.xm.gov.cn/competition/project-detail.html?id=9ee396fad04a4d2eb88118a30c0d4a5d&competeId=0c8ce75d26e840b1b9ffd10633d6a9bf)
<div style="display: flex;">
  <div style="width: 75%;">
    <span style="color: grey">Aug. 2019</span><br />
    <span style="font-weight: bold">3rd place on same source image retrieval category</span><br />
    <br />
    <div>
    Used ImageNet-pretrained backbone to extract image feature and trained a MLP to obtained the image embedding with triple loss.
    </div>
  </div>
  <div style="width: 25%;">
    <img src='images/image-retrieval-system.png' width="100%">
  </div>
</div>

### 3D Reconstruction with an Two-stage Stereo Matching Approach
<div style="display: flex;">
  <div style="width: 75%;">
    <span style="color: grey">Jan. 2019</span><br />
    <span style="font-weight: bold">Bachelor's thesis</span><br />
    <br />
    <div>
    A Pytorch implementation of <a href='https://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w17/Pang_Cascade_Residual_Learning_ICCV_2017_paper.pdf'>CRL-Net</a> and disparity map denoising.
    </div>
  </div>
  <div style="width: 25%;">
    <img src='images/3Dreconstruction.jpeg' width="100%">
  </div>
</div>



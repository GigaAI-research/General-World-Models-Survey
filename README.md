

# [Is Sora a World Simulator? A Comprehensive Survey on General World Models and Beyond](https://arxiv.org/abs/TODO) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/TODO) 


<div style="text-align:center; font-size: 18px;">
    <p>
    <a href="https://scholar.google.com/citations?user=NmwjI0AAAAAJ&hl=en">Zheng Zhu*</a>, 
    <a href="https://scholar.google.com.hk/citations?user=5IJ0Yg4AAAAJ&hl=zh-CN">Xiaofeng Wang*</a>,
    <a href="https://scholar.google.co.jp/citations?user=aocj89kAAAAJ&hl=es">Wangbo Zhao*</a>,
    <a href="https://scholar.google.com/citations?user=pE9gTMQAAAAJ&hl=zh-CN">Chen Min*</a>,
    <a href="https://scholar.google.com/citations?user=AGPz8C4AAAAJ">Nianchen Deng*</a>,
    <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=w9fTWKQAAAAJ">Min Dou*</a>,
    <a href="https://scholar.google.com/citations?user=35UcX9sAAAAJ&hl=en">Yuqi Wang*</a>,
    <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=K0PpvLkAAAAJ">Botian Shi<sup>#</sup></a>,
    <a href="https://scholar.google.com/citations?user=i2II0XIAAAAJ&hl=en">Kai Wang<sup>#</sup</a>,
    <a href="https://scholar.google.com/citations?user=aTA2wL4AAAAJ&hl=en">Chi Zhang<sup>#</sup</a>,
    <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=jF4dPZwAAAAJ">Yang You<sup>#</sup</a>,
    <a href="https://scholar.google.com/citations?user=qxWfV6cAAAAJ&hl=en">Zhaoxiang Zhang<sup>#</sup</a>,
    <a href="">Dawei Zhao<sup>#</sup</a>,
    <a href="https://scholar.google.com/citations?user=hvxSnzoAAAAJ&hl=zh-CN">Liang Xiao<sup>#</sup</a>,
    <a href="https://scholar.google.com.sg/citations?hl=en&user=zdhRJCkAAAAJ&view_op=list_works&gmla=AJsN-F4PURIx5GMQHVpprJJBjTsNC62YCHjxGsKOwVhrkZ1aJsLgBiuKPBbAgbdcE5_KNw3OnLQgOVSjlqmS6gc-6ti0M2K5o-klHgoOywFCbdaaGnpis130zvgoZFJkVfmoNKpo8Krp">Jian Zhao<sup>#</sup</a>,
    <a href="https://scholar.google.com/citations?user=TN8uDQoAAAAJ&hl=en">Jiwen Lu<sup>#</sup</a>,
    <a href="">Guan Huang<sup>#</sup</a>
</div>

<div style="text-align:center; font-size: 18px;">
    <p>
    (* denotes equal contributions,  <sup>#</sup> denotes corresponding authors)
</div>





<p align="center">
<img src="asset/videogen.gif" width="320px"/>  
<img src="asset/videogen2.gif" width="320px"/>  
</p>


<p align="center">
<img src="asset/drivedreamer.gif" width="190px"/>
<img src="asset/drive-wm.gif" width="450px"/>
</p>



<p align="center">
<img src="asset/drive.gif" width="640px"/>
</p>

<p align="center">
<img src="asset/unisim.gif" width="240px"/>
<img src="asset/unipi.gif" width="245px"/>    
<img src="asset/robodreamer.gif" width="145px"/>    
</p>



<p align="center">
(Source:<a href="https://openai.com/sora">Sora</a>, <a href="https://drivedreamer.github.io/">DriveDreamer</a>, <a href="https://drivedreamer2.github.io/">DriveDreamer-2</a>, <a href="https://drive-wm.github.io/">Drive-WM</a>, <a href="https://universal-simulator.github.io/unisim/">UniSim</a>, <a href="https://universal-policy.github.io/unipi/">UniPi</a>, <a href="https://robovideo.github.io/">RoboDreamer</a>)
</p>


<!-- - [News] <span style="color:red;"> **We are planning to update the survey soon to encompass the latest work. If you have any suggestions, please feel free to contact us.**</span>
- [News] The Chinese translation is available on [Zhihu](https://zhuanlan.zhihu.com/p/661860981). Special thanks to [Dai-Wenxun](https://github.com/Dai-Wenxun) for this.
 -->


This is the official repository for the technical report: 

**Is Sora a World Simulator? A Comprehensive Survey on General World Models and Beyond**.


## 📌 Introduction

In our report, we present a holistic examination of recent advancements in world model research, encompassing profound philosophical perspectives and detailed discussions. Our analysis delves deeply into the literature surrounding world models for **video generation**, **autonomous driving**, and **autonomous agents**, uncovering their applications in media production, artistic expression, end-to-end driving, games, and robots. We assess the existing challenges and limitations of world models and delve into prospective avenues for future research, with the intention of steering and igniting further progress in world models.

![Framework](./asset/Framework.png "Framework of general world models")

## Papers and Toolboxes for Video Generation World Models 
![VideoGen](./asset/VideoGen.png "video generation world models")

| Methods | Task | Github|
|:-----:|:-----:|:-----:|
| [Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan/blob/main/docs/Report-v1.0.0.md)  | T2V Generation | [![Star](https://img.shields.io/github/stars/PKU-YuanGroup/Open-Sora-Plan.svg?style=social&label=Star)](https://github.com/PKU-YuanGroup/Open-Sora-Plan)|
| [Open-Sora](https://github.com/hpcaitech/Open-Sora/blob/main/docs/zh_CN/README.md)  | T2V Generation | [![Star](https://img.shields.io/github/stars/hpcaitech/Open-Sora.svg?style=social&label=Star)](https://github.com/hpcaitech/Open-Sora)|
| [Sora](https://openai.com/sora)  | T2V Generation & Editing | -|
| [IRC-GAN](https://www.ijcai.org/Proceedings/2019/0307.pdf) | T2V Generation | -|
| [TGANs-C](https://arxiv.org/pdf/1804.08264) | T2V Generation | -|
| [TFGANs](https://www.ijcai.org/Proceedings/2019/0276.pdf) | T2V Generation | -|
| [StoryGAN](https://openaccess.thecvf.com/content_CVPR_2019/papers/Li_StoryGAN_A_Sequential_Conditional_GAN_for_Story_Visualization_CVPR_2019_paper.pdf) | T2V Generation | [![Star](https://img.shields.io/github/stars/yitong91/StoryGAN.svg?style=social&label=Star)](https://github.com/yitong91/StoryGAN)|
| [TiVGAN](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9171240) | T2V Generation | -|
| [GODIVA](https://arxiv.org/pdf/2104.14806) | T2V Generation | [![Star](https://img.shields.io/github/stars/breadbread1984/GODIVA.svg?style=social&label=Star)](https://github.com/breadbread1984/GODIVA)|
| [VideoGPT](https://arxiv.org/abs/2104.10157) | C2V Generation | [![Star](https://img.shields.io/github/stars/wilson1yan/VideoGPT.svg?style=social&label=Star)](https://github.com/wilson1yan/VideoGPT)|
| [StoryDALL-E](https://link.springer.com/chapter/10.1007/978-3-031-19836-6_5) | C2V Generation | -|
| [CogVideo](https://arxiv.org/pdf/2205.15868) | T2V Generation | [![Star](https://img.shields.io/github/stars/THUDM/CogVideo.svg?style=social&label=Star)](https://github.com/THUDM/CogVideo)|
| [Imagen Video](https://arxiv.org/pdf/2210.02303) | T2V Generation | -|
| [MAGViT](https://openaccess.thecvf.com/content/CVPR2023/papers/Yu_MAGVIT_Masked_Generative_Video_Transformer_CVPR_2023_paper.pdf) | C2V Generation | [![Star](https://img.shields.io/github/stars/google-research/magvit.svg?style=social&label=Star)](https://github.com/google-research/magvit)|
| [MAGViT-V2](https://arxiv.org/abs/2310.05737) | C2V Generation | [![Star](https://img.shields.io/github/stars/lucidrains/magvit2-pytorch.svg?style=social&label=Star)](https://github.com/lucidrains/magvit2-pytorch)|
| [VideoPoet](https://arxiv.org/abs/2312.14125) | T2V Generation | -|
| [SVD](https://arxiv.org/abs/2311.15127) | T2V Generation | [![Star](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social&label=Star)](https://github.com/Stability-AI/generative-models)|
| [WorldDreamer](https://arxiv.org/abs/2401.09985) | T2V Generation | [![Star](https://img.shields.io/github/stars/JeffWang987/WorldDreamer.svg?style=social&label=Star)](https://github.com/JeffWang987/WorldDreamer)|
| [Latte](https://arxiv.org/abs/2401.09985) | T2V Generation | [![Star](https://img.shields.io/github/stars/Vchitect/Latte.svg?style=social&label=Star)](https://github.com/Vchitect/Latte)|
| [StreamingT2V](https://arxiv.org/abs/2403.14773) | T2V Generation | [![Star](https://img.shields.io/github/stars/Picsart-AI-Research/StreamingT2V.svg?style=social&label=Star)](https://github.com/Picsart-AI-Research/StreamingT2V)|


## Papers and Toolboxes for Autonomous Driving World Models 
![Drive](./asset/Drive.png "autonomous driving world models")

| Methods | Task | Github|
|:-----:|:-----:|:-----:|
| [Iso-Dream](https://proceedings.neurips.cc/paper_files/paper/2022/hash/9316769afaaeeaad42a9e3633b14e801-Abstract-Conference.html)  | End-to-end Driving|-|
| [MILE](https://proceedings.neurips.cc/paper_files/paper/2022/hash/827cb489449ea216e4a257c47e407d18-Abstract-Conference.html)  | End-to-end Driving|[![Star](https://img.shields.io/github/stars/wayveai/mile.svg?style=social&label=Star)](https://github.com/wayveai/mile)|
| [SEM2](https://arxiv.org/abs/2210.04017)  | End-to-end Driving|-|
| [TrafficBots](https://ieeexplore.ieee.org/abstract/document/10161243)  | End-to-end Driving|-|
| [Think2Drive](https://arxiv.org/abs/2402.16720)  | End-to-end Driving|-|
| [GAIA-1](https://arxiv.org/abs/2309.17080)  | Neural Driving Simulator (2D) |-|
| [Tesla](https://www.youtube.com/watch?v=6x-Xb_uT7ts) | Neural Driving Simulator|-|
| [DriveDreamer](https://drivedreamer.github.io/)  | Neural Driving Simulator (2D) | [![Star](https://img.shields.io/github/stars/JeffWang987/DriveDreamer.svg?style=social&label=Star)](https://github.com/JeffWang987/DriveDreamer)|
| [ADriver-I](https://arxiv.org/abs/2309.17080)  | Neural Driving Simulator (2D) | -|
| [DrivingDiffusion](https://arxiv.org/abs/2310.07771)  | Neural Driving Simulator (2D) |-|
| [Panacea](https://panacea-ad.github.io/)  | Neural Driving Simulator (2D) | [![Star](https://img.shields.io/github/stars/wenyuqing/panacea.svg?style=social&label=Star)](https://github.com/wenyuqing/panacea)|
| [Drive-WM](https://drive-wm.github.io/)  | Neural Driving Simulator (2D) & End-to-end Driving| [![Star](https://img.shields.io/github/stars/BraveGroup/Drive-WM.svg?style=social&label=Star)](https://github.com/BraveGroup/Drive-WM)|
| [WoVoGen](https://arxiv.org/abs/2312.02934)  | Neural Driving Simulator (2D) | -|
| [DriveDreamer-2](https://drivedreamer2.github.io/)  | Neural Driving Simulator (2D) | [![Star](https://img.shields.io/github/stars/f1yfisher/DriveDreamer2.svg?style=social&label=Star)](https://github.com/f1yfisher/DriveDreamer2)|
| [GenAD](https://arxiv.org/abs/2403.09630)  | Neural Driving Simulator (2D) | [![Star](https://img.shields.io/github/stars/OpenDriveLab/DriveAGI?tab=readme-ov-file.svg?style=social&label=Star)](https://github.com/OpenDriveLab/DriveAGI?tab=readme-ov-file)|
| [SubjectDrive](https://subjectdrive.github.io/)  | Neural Driving Simulator (2D) | -|
| [Copilot4D](https://arxiv.org/abs/2311.01017)  | Neural Driving Simulator (3D) | -|
| [OccWorld](https://arxiv.org/abs/2311.16038)  | Neural Driving Simulator (3D) | [![Star](https://img.shields.io/github/stars/wzzheng/OccWorld.svg?style=social&label=Star)](https://github.com/wzzheng/OccWorld)|
| [MUVO](https://arxiv.org/abs/2311.11762)  | Neural Driving Simulator (3D) | -|
| [LidarDM](https://www.zyrianov.org/lidardm/)  | Neural Driving Simulator (3D) | -|
| [UniWorld](https://arxiv.org/abs/2308.07234)  | Neural Driving Simulator (3D) & 4D Pre-training| -|
| [ViDAR](https://arxiv.org/abs/2312.17655)  | Neural Driving Simulator (3D) & 4D Pre-training| [![Star](https://img.shields.io/github/stars/OpenDriveLab/ViDAR.svg?style=social&label=Star)](https://github.com/OpenDriveLab/ViDAR)|
| [DriveWorld](XXX)  | Neural Driving Simulator (3D) & 4D Pre-training|-|



## Papers and Toolboxes for Autonomous Agents World Models 
![Agent](./asset/Agent.png "autonomous agents world models")

| Methods | Task | Github|
|:-----:|:-----:|:-----:|
| [PlaNet](https://planetrl.github.io/)  | Robotics | [![Star](https://img.shields.io/github/stars/google-research/planet.svg?style=social&label=Star)](https://github.com/google-research/planet) |
| [World Models](https://worldmodels.github.io/)  | Game Agent | [![Star](https://img.shields.io/github/stars/hardmaru/WorldModelsExperiments.svg?style=social&label=Star)](https://github.com/hardmaru/WorldModelsExperiments) |
| [RobotDreamPolicy](https://piergiaj.github.io/robot-dreaming-policy/)  | Robotics | - |
| [Plan2Explore](https://ramanans1.github.io/plan2explore/)  | Robotics | [![Star](https://img.shields.io/github/stars/ramanans1/plan2explore.svg?style=social&label=Star)](https://github.com/ramanans1/plan2explore) |
| [DreamerV1](https://danijar.com/project/dreamer/)  | Robotics | [![Star](https://img.shields.io/github/stars/danijar/dreamer.svg?style=social&label=Star)](https://github.com/danijar/dreamer) |
| [SimPLe](https://github.com/dhruvramani/model-based-atari/)  | Game Agent | [![Star](https://img.shields.io/github/stars/dhruvramani/model-based-atari.svg?style=social&label=Star)](https://github.com/dhruvramani/model-based-atari) |
| [Dreaming](https://arxiv.org/abs/2007.14535/)  | Robotics | - |
| [DreamerV2](https://danijar.com/project/dreamerv2/)  | Game Agent | [![Star](https://img.shields.io/github/stars/danijar/dreamerv2.svg?style=social&label=Star)](https://github.com/danijar/dreamerv2) |
| [LEXA](https://orybkin.github.io/lexa/)  | Robotics | [![Star](https://img.shields.io/github/stars/orybkin/lexa.svg?style=social&label=Star)](https://github.com/orybkin/lexa) |
| [PathDreamer](https://google-research.github.io/pathdreamer/)  | Indoor Navigation | [![Star](https://img.shields.io/github/stars/google-research/pathdreamer.svg?style=social&label=Star)](https://github.com/google-research/pathdreamer) |
| [DreamerPro](https://github.com/fdeng18/dreamer-pro/)  | Robotics | [![Star](https://img.shields.io/github/stars/fdeng18/dreamer-pro.svg?style=social&label=Star)](https://github.com/fdeng18/dreamer-pro) |
| [DreamingV2](https://arxiv.org/abs/2203.00494/)  | Robotics | - |
| [TransDreamer](https://github.com/changchencc/TransDreamer/)  | Game Agent & Robotics | [![Star](https://img.shields.io/github/stars/changchencc/TransDreamer.svg?style=social&label=Star)](https://github.com/changchencc/TransDreamer) |
| [IRIS](https://github.com/eloialonso/iris/)  | Game Agent | [![Star](https://img.shields.io/github/stars/eloialonso/iris.svg?style=social&label=Star)](https://github.com/eloialonso/iris) |
| [JEPA](https://openreview.net/forum?id=BZ5a1r-kVsf)  | Framework | - |
| [Dr.G](https://github.com/JeongsooHa/DrG/)  | Robotics | [![Star](https://img.shields.io/github/stars/JeongsooHa/DrG.svg?style=social&label=Star)](https://github.com/JeongsooHa/DrG) |
| [SWIM](https://human-world-model.github.io/)  | Robotics | - |
| [DreamerV3](https://danijar.com/project/dreamerv3/)  | Game Agent & Robotics | [![Star](https://img.shields.io/github/stars/danijar/dreamerv3.svg?style=social&label=Star)](https://github.com/danijar/dreamerv3) |
| [HarmonyDream](https://arxiv.org/abs/2310.00344/)  | Game Agent & Robotics | - |
| [DayDreamer](https://danijar.com/project/daydreamer/)  | Robotics | [![Star](https://img.shields.io/github/stars/danijar/daydreamer.svg?style=social&label=Star)](https://github.com/danijar/daydreamer) |
| [TWM](https://github.com/jrobine/twm/)  | Game Agent | [![Star](https://img.shields.io/github/stars/jrobine/twm.svg?style=social&label=Star)](https://github.com/jrobine/twm) |
| [STORM](https://github.com/weipu-zhang/storm/)  | Game Agent | [![Star](https://img.shields.io/github/stars/weipu-zhang/storm.svg?style=social&label=Star)](https://github.com/weipu-zhang/storm) |
| [MC-JEPA](https://arxiv.org/abs/2307.12698/)  | Optics Flow Prediction | - |
| [A-JEPA](https://arxiv.org/abs/2311.15830/)  | Audio Classification | - |
| [I_JEPA](https://github.com/facebookresearch/ijepa/)  | Image Semantics | [![Star](https://img.shields.io/github/stars/facebookresearch/ijepa.svg?style=social&label=Star)](https://github.com/facebookresearch/ijepa) |
| [SafeDreamer](https://sites.google.com/view/safedreamer/)  | Robotics | [![Star](https://img.shields.io/github/stars/PKU-Alignment/SafeDreamer.svg?style=social&label=Star)](https://github.com/PKU-Alignment/SafeDreamer) |
| [Genie](https://sites.google.com/view/genie-2024/home/)  | Generative Interactive Environment | - |
| [V-JEPA](https://github.com/facebookresearch/jepa/)  | Video Prediction | [![Star](https://img.shields.io/github/stars/facebookresearch/jepa.svg?style=social&label=Star)](https://github.com/facebookresearch/jepa) |
| [RoboDreamer](https://robovideo.github.io/)  | Robotics | - |
| [UniSim](https://universal-simulator.github.io/unisim/)  | Generative Interactive Environment | - |


## Contact
If you find our survey is useful in your research or applications, please consider giving us a star 🌟 and citing it by the following BibTeX entry.

```
@article{generalworldmodelsurvey,
  title={Is Sora a World Simulator? A Comprehensive Survey on General World Models and Beyond},
  author={Zheng Zhu and Xiaofeng Wang and Wangbo Zhao and Chen Min and Nianchen Deng and Min Dou and Yuqi Wang and Botian Shi and Kai Wang and Chi Zhang and Yang You and Zhaoxiang Zhang and Dawei Zhao and Liang Xiao and Jian Zhao and Jiwen Lu and Guan Huang}, 
  journal={arXiv preprint arXiv:TODO},
  year={2024}
}
```

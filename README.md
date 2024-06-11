# Awesome-3D-Multimodal-Maps

Here we demonstrate neural network methods for 3D multimodal map reconstruction and their usage for object retrieval, robot navigation and control.

Example of a 3D multimodal map with a scene graph representation. We can make text queries to it for 3D object retrieval:

![Taxonomy](https://github.com/yuddim/awesome-3d-multimodal-maps/blob/main/assets/mmap_example.png)

We propose following taxonomy of 3D multimodal map reconstruction methods:

![Taxonomy](https://github.com/yuddim/awesome-3d-multimodal-maps/blob/main/assets/mm-taxonomy.png)

# Dense multimodal map reconstruction methods

## Point-based

(2023) **OpenMask3D: Open-Vocabulary 3D Instance Segmentation.** arXiv preprint arXiv:2306.13631. NeurIPS 2023. Takmaz, A., Fedele, E., Sumner, R. W., Pollefeys, M., Tombari, F., & Engelmann, F. (ETH Zurich, ETH AI Center, Google Zurich )  [(paper)](https://arxiv.org/abs/2306.13631) | [(code)](https://github.com/OpenMask3D/openmask3d) | [(project)](https://openmask3d.github.io/) 

(2023) **Openscene: 3d scene understanding with open vocabularies.** Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023. Peng, Songyou, et al. (Google Research, ETH Zurich, MPI for Intelligent Systems, Waymo LLC, Simon Fraser University) [(paper)](https://arxiv.org/abs/2211.15654) | [(code)](https://github.com/pengsongyou/openscene) | [(project)](https://pengsongyou.github.io/openscene) | [(video)](https://youtu.be/jZxCLHyDJf8)

(2023) **PLA: Language-Driven Open-Vocabulary 3D Scene Understanding.** Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023. Ding, Runyu, et al. (The University of Hong Kong, ByteDance) [(paper)](https://arxiv.org/abs/2211.16312) | [(code)](https://github.com/CVMI-Lab/PLA) | [(project)](https://dingry.github.io/projects/PLA) 

(2023) **Audio visual language maps for robot navigation.** arXiv preprint arXiv:2303.07522, 2023. Huang, Chenguang, et al. (Freiburg University, Google Research, University of Technology Nuremberg). ISER 2023 [(paper)](https://arxiv.org/pdf/2303.07522.pdf) | [(code)](https://github.com/avlmaps/AVLMaps) | [(project)](https://avlmaps.github.io/) | [(colab)](https://colab.research.google.com/drive/1gdtLvg_Fbl16N3ITp5FsU9ZAG6HmspVb?usp=sharing) | [(video)](https://avlmaps.github.io/)

(2023) **Conceptfusion: Open-set multimodal 3d mapping.** arXiv preprint arXiv:2302.07241, 2023. Jatavallabhula, Krishna Murthy, et al. (MIT, Universite de Montreal, University of Toronto, IIIT Hyderabad, CMU, Amazon, Matician, DEVCOM Army Research Laboratory) [(paper)](https://arxiv.org/abs/2302.07241) | [(code)](https://github.com/concept-fusion/concept-fusion) | [(project)](https://concept-fusion.github.io/) | [(video)](https://www.youtube.com/watch?v=rkXgws8fiDs)

(2022) **Language-grounded indoor 3d semantic segmentation in the wild.** In ECCV (pp. 125-141). Rozenberszki, D., Litany, O., & Dai, A. (Technical University of Munich, NVIDIA). [(paper)](https://arxiv.org/abs/2204.07761) | [(code)](https://github.com/RozDavid/LanguageGroundedSemseg) | [(project)](https://rozdavid.github.io/scannet200) | [(benchmark)](http://kaldir.vc.in.tum.de/scannet_benchmark/) | [(video)](https://www.youtube.com/watch?v=Cu-zW1oXrvU)

## Voxel-based

(2024) **Scene-LLM: Extending Language Model for 3D Visual Understanding and Reasoning.** arXiv preprint arXiv:2403.11401. Fu, R., Liu, J., Chen, X., Nie, Y., & Xiong, W. (Brown University, ETH Zurich, Meta AI)  [(paper)](https://arxiv.org/abs/2403.11401) | [(code)](https://github.com/vlmaps/vlmaps.git) | [(project)](https://vlmaps.github.io/) | [(colab)](https://colab.research.google.com/drive/1xsH9Gr_O36sBZaoPNq1SmqgOOF12spV0?usp=sharing) | [(video)](https://vlmaps.github.io/)

(2023) **Visual language maps for robot navigation.** 2023 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2023. Huang, Chenguang, et al. (Freiburg University, Google Research, University of Technology Nuremberg) [(paper)](https://arxiv.org/pdf/2210.05714.pdf) | [(code)](https://github.com/vlmaps/vlmaps.git) | [(project)](https://vlmaps.github.io/) | [(colab)](https://colab.research.google.com/drive/1xsH9Gr_O36sBZaoPNq1SmqgOOF12spV0?usp=sharing) | [(video)](https://vlmaps.github.io/)

## NeRF-based

(2024) **Llm-grounder: Open-vocabulary 3d visual grounding with large language model as an agent.** arXiv preprint arXiv:2309.12311. ICRA 2024. Yang, J., Chen, X., Qian, S., Madaan, N., Iyengar, M., Fouhey, D. F., & Chai, J. (University of Michigan, New York University) [(paper)](https://arxiv.org/abs/2309.12311) | [(code)](https://github.com/sled-group/chat-with-nerf) | [(project)](https://chat-with-nerf.github.io) | [(live demo)](http://sled-whistler.eecs.umich.edu:7777/) | [(video)](https://youtu.be/eO-Vaf-1R1s)

(2023). **3d-llm: Injecting the 3d world into large language models.** Advances in Neural Information Processing Systems, 36, 20482-20494. Hong, Y., Zhen, H., Chen, P., Zheng, S., Du, Y., Chen, Z., & Gan, C. (UCLA, SJTU, SCUT, UIUC, MIT, MIT-IBM Watson AI Lab, Umass Amherst) [(paper)](https://arxiv.org/abs/2307.12981) | [(code)](https://github.com/UMass-Foundation-Model/3D-LLM) | [(project)](https://vis-www.cs.umass.edu/3dllm/) 

(2023) **Lerf: Language embedded radiance fields.** In Proceedings of the IEEE/CVF International Conference on Computer Vision (pp. 19729-19739). Kerr, J., Kim, C. M., Goldberg, K., Kanazawa, A., & Tancik, M. (UC Berkeley)[(paper)](https://arxiv.org/abs/2303.09553) | [(code)](https://github.com/kerrj/lerf) | [(project)](https://www.lerf.io/) | [(dataset)](https://drive.google.com/drive/folders/1vh0mSl7v29yaGsxleadcj-LCZOE_WEWB?usp=sharing) 

(2023) **Weakly Supervised 3D Open-vocabulary Segmentation.** arXiv preprint arXiv:2305.14093. NeurIPS 2023. Liu, K., Zhan, F., Zhang, J., Xu, M., Yu, Y., Saddik, A. E., ... & Lu, S. (Nanyang Technological University, Max Planck Institute for Informatics, University of Ottawa, Carnegie Mellon University, MBZUAI) [(paper)](https://arxiv.org/abs/2305.14093) | [(code)](https://github.com/Kunhao-Liu/3D-OVS) | [(dataset)](https://drive.google.com/drive/folders/1kdV14Gu5nZX6WOPbccG7t7obP_aXkOuC?usp=sharing) 

## SDF-based

(2024) **Open-Fusion: Real-time Open-Vocabulary 3D Mapping and Queryable Scene Representation.** arXiv preprint arXiv:2310.03923. ICRA 2024. Yamazaki, Kashu, et al. (University of Arkansas, West Virginia University, University of Liverpool) [(paper)](https://arxiv.org/abs/2310.03923) | [(code)](https://github.com/UARK-AICV/OpenFusion) | [(project)](https://uark-aicv.github.io/OpenFusion/) 

## Gaussian Splatting-based

(2024) **OpenGaussian: Towards Point-Level 3D Gaussian-based Open Vocabulary Understanding**. arXiv preprint arXiv:2406.02058. Wu, Y., Meng, J., Li, H., Wu, C., Shi, Y., Cheng, X., Zhao, C., Feng, H., Ding, E., Wang, J. and Zhang, J. (Peking University, Baidu VIS, Beihang University) [(paper)](https://arxiv.org/abs/2406.02058) | code (Coming soon) | [(project)](https://3d-aigc.github.io/OpenGaussian) 

(2023) **LangSplat: 3D Language Gaussian Splatting.** arXiv preprint arXiv:2312.16084. CVPR2024 Highlight. Qin, M., Li, W., Zhou, J., Wang, H. and Pfister, H. (Tsinghua University, Harvard University) [(paper)](https://arxiv.org/pdf/2312.16084.pdf) | [(code)](https://github.com/minghanqin/LangSplat) | [(project)](https://langsplat.github.io) | [(video)](https://youtu.be/XMlyjsei-Es?si=3KceyF_89BXnfGyM)

# Sparse multimodal map reconstruction methods

## Object-based

(2024) **Mapping the Unseen: Unified Promptable Panoptic Mapping with Dynamic Labeling using Foundation Models.** arXiv preprint arXiv:2405.02162. Mdfaa, M.A., Salameh, R., Zagoruyko, S. and Ferrer, G. (ScolTech) [(paper)](https://arxiv.org/abs/2405.02162) | [(code is coming soon)]() | [(project)](https://unified-promptable-panoptic-mapping.github.io)  

(2024) **SUGAR: Pre-training 3D Visual Representations for Robotics.** arXiv preprint arXiv:2404.01491. S Chen, R Garcia, I Laptev, C Schmid  [(paper)](https://arxiv.org/abs/2404.01491) | [(code is coming soon)]() | [(project)](https://cshizhe.github.io/projects/robot_sugar.html) 

(2023) **Unsupervised 3D Perception with 2D Vision-Language Distillation for Autonomous Driving.** Proceedings of the IEEE/CVF International Conference on Computer Vision. 2023. Najibi, Mahyar, et al. (Waymo LLC) [(paper)](https://arxiv.org/abs/2309.14491) 

## Object-based with relations (knowledge graphs)

(2024) **SpatialRGPT: Grounded Spatial Reasoning in Vision Language Model.** arXiv preprint arXiv:2406.01584. Cheng, A.C., Yin, H., Fu, Y., Guo, Q., Yang, R., Kautz, J., Wang, X. and Liu, S. (UC San Diego, The University of Hong Kong, NVIDIA) [(paper)](https://arxiv.org/abs/2406.01584) | [(code and dataset are coming soon)]() | [(project)](https://www.anjiecheng.me/SpatialRGPT) 

(2024) **Open3DSG: Open-Vocabulary 3D Scene Graphs from Point Clouds with Queryable Objects and Open-Set Relationships.** arXiv preprint arXiv:2402.12259. CVPR 2024. Koch, S., Vaskevicius, N., Colosi, M., Hermosilla, P., & Ropinski, T. (Bosch Center for Artificial Intelligence, Robert Bosch Corporate Research, University of Ulm, TU Vienna) [(paper)](https://arxiv.org/abs/2402.12259) | [(code is coming soon)]() | [(project)](https://kochsebastian.com/open3dsg) 

(2024) **EmbodiedScan: A Holistic Multi-Modal 3D Perception Suite Towards Embodied AI.** arXiv preprint arXiv:2312.16170. CVPR 2024. Wang, T., Mao, X., Zhu, C., Xu, R., Lyu, R., Li, P., ... & Pang, J. (Shanghai AI Laboratory, Shanghai Jiao Tong University, The University of Hong Kong, The Chinese University of Hong Kong, Tsinghua University) [(paper)](https://arxiv.org/abs/2312.16170) | [(code and dataset)](https://github.com/OpenRobotLab/EmbodiedScan) | [(project)](https://tai-wang.github.io/embodiedscan/) 

(2023) **ConceptGraphs: Open-Vocabulary 3D Scene Graphs for Perception and Planning.** arXiv preprint arXiv:2309.16650, 2023. Gu, Qiao, et al. (MIT, Universite de Montreal, University of Toronto, IIIT Hyderabad, JHU APL, JHU, UMass Amherst, DEVCOM Army Research Laboratory). [(paper)](http://arxiv.org/abs/2309.16650) | [(code)](https://github.com/concept-graphs/concept-graphs) | [(project)](https://concept-graphs.github.io/) | [(video)](https://youtu.be/mRhNkQwRYnc)

(2023) **VL-SAT: Visual-Linguistic Semantics Assisted Training for 3D Semantic Scene Graph Prediction in Point Cloud.** In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (School of Software, Beihang University, The University of Hong Kong, East China University of Science and Technology). Wang, Z., Cheng, B., Zhao, L., Xu, D., Tang, Y., & Sheng, L. [(paper)](https://arxiv.org/pdf/2303.14408.pdf) | [(code)](https://github.com/wz7in/CVPR2023-VLSAT) | [(model checkpoint)](https://drive.google.com/file/d/1_C-LXRlSobupApb-JsajKG5oxKnfKgdx/view?usp=sharing) 

(2023) **Context-aware entity grounding with open-vocabulary 3d scene graphs.** arXiv preprint arXiv:2309.15940. CoRL '23. Chang, H., Boyalakuntla, K., Lu, S., Cai, S., Jing, E., Keskar, S., ... & Boularias, A. (Rutgers University-New Brunswick, Drexel University) [(paper)](https://arxiv.org/abs/2309.15940) | [(code)](https://github.com/changhaonan/OVSG) | [(project)](https://ovsg-l.github.io/) | [(dataset)](https://doi.org/10.6084/m9.figshare.24307072.v1) 

(2023) **3d vsg: Long-term semantic scene change prediction through 3d variable scene graphs.** In 2023 IEEE International Conference on Robotics and Automation (ICRA) (pp. 8179-8186). IEEE. Looper, S., Rodriguez-Puigvert, J., Siegwart, R., Cadena, C., Schmid, L. (ETH Zurich, Universidad de Zaragoza, Massachusetts Institute of Technology) [(paper)](https://arxiv.org/abs/2209.07896) | [(code)](https://github.com/ethz-asl/3d_vsg) 

(2022) **Language conditioned spatial relation reasoning for 3d object grounding.** Advances in neural information processing systems 35, 20522-20535, 2022. S Chen, PL Guhur, M Tapaswi, C Schmid, I Laptev (Rutgers University-New Brunswick, Drexel University) [(paper)](https://arxiv.org/abs/2211.09646) | [(code)](https://github.com/cshizhe/vil3dref) | [(project)](https://cshizhe.github.io/projects/vil3dref.html) 

## Object-based with hierarchy

(2024) **Language-Grounded Dynamic Scene Graphs for Interactive Object Search with Mobile Manipulation.** arXiv preprint arXiv:2403.08605. Honerkamp, D., Buchner, M., Despinoy, F., Welschehold, T., & Valada, A. (University of Freiburg, Toyota Motor Europe (TME)).  [(paper)](https://arxiv.org/abs/2403.08605) | [(code)](https://github.com/robot-learning-freiburg/MoMa-LLM) | [(project)](http://moma-llm.cs.uni-freiburg.de) 

(2024) **Hierarchical Open-Vocabulary 3D Scene Graphs for Language-Grounded Robot Navigation.** arXiv preprint arXiv:2403.17846. Werby, A., Huang, C., Büchner, M., Valada, A., & Burgard, W.  (University of Freiburg, University of Technology Nuremberg) [(paper)](https://arxiv.org/abs/2403.17846) | [(project)](https://hovsg.github.io/) 

(2023) **Foundations of Spatial Perception for Robotics: Hierarchical Representations and Real-time Systems.** arXiv preprint arXiv:2305.07154. Hughes, N., Chang, Y., Hu, S., Talak, R., Abdulhai, R., Strader, J., & Carlone, L. (Massachusetts Institute of Technology) [(paper)](https://arxiv.org/abs/2305.07154) | [(code)](https://github.com/MIT-SPARK/Hydra) 

## Ontology-based

(2023) **Indoor and Outdoor 3D Scene Graph Generation via Language-Enabled Spatial Ontologies.** arXiv preprint arXiv:2312.11713. Strader, J., Hughes, N., Chen, W., Speranzon, A., & Carlone, L. (Massachusetts Institute of Technology, University of California, Lockheed Martin) [(paper)](https://arxiv.org/abs/2312.11713) 

(2023) **3d scene graph prediction on point clouds using knowledge graphs.** In 2023 IEEE 19th International Conference on Automation Science and Engineering (CASE) (pp. 1-7). IEEE. Qiu, Y., & Christensen, H. I. (University of California San Diego) [(paper)](https://arxiv.org/abs/2308.06719) 

(2021) **Knowledge-inspired 3d scene graph prediction in point cloud.** Advances in Neural Information Processing Systems, 34, 18620-18632. Zhang, S., Hao, A., & Qin, H. (Beihang University, Peng Cheng Laboratory, Stony Brook University (SUNY)) [(paper)](https://proceedings.neurips.cc/paper/2021/hash/9a555403384fc12f931656dea910e334-Abstract.html)





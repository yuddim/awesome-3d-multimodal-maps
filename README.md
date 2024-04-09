# Awesome-3D-Multimodal-Maps

Here we demonstrate neural network methods for 3D multimodal map reconstruction and their usage for robot navigation and control

We propose following taxonomy of 3D multimodal map reconstruction methods:

![Taxonomy](https://github.com/yuddim/awesome-3d-multimodal-maps/blob/main/assets/mm-taxonomy.png)

# Dense multimodal map reconstruction methods

## Point-based

(2022). **Language-grounded indoor 3d semantic segmentation in the wild.** In ECCV (pp. 125-141). Rozenberszki, D., Litany, O., & Dai, A. (Technical University of Munich, NVIDIA). [(paper)](https://arxiv.org/abs/2204.07761) | [(code)](https://github.com/RozDavid/LanguageGroundedSemseg) | [(project)](https://rozdavid.github.io/scannet200) | [(benchmark)](http://kaldir.vc.in.tum.de/scannet_benchmark/) | [(video)](https://www.youtube.com/watch?v=Cu-zW1oXrvU)

(2023). **OpenMask3D: Open-Vocabulary 3D Instance Segmentation.** arXiv preprint arXiv:2306.13631. NeurIPS 2023. Takmaz, A., Fedele, E., Sumner, R. W., Pollefeys, M., Tombari, F., & Engelmann, F. (ETH Zurich, ETH AI Center, Google Zurich )  [(paper)](https://arxiv.org/abs/2306.13631) | [(code)](https://github.com/OpenMask3D/openmask3d) | [(project)](https://openmask3d.github.io/) 

(2023) **Openscene: 3d scene understanding with open vocabularies.** Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023. Peng, Songyou, et al. (Google Research, ETH Zurich, MPI for Intelligent Systems, Waymo LLC, Simon Fraser University) [(paper)](https://arxiv.org/abs/2211.15654) | [(code)](https://github.com/pengsongyou/openscene) | [(project)](https://pengsongyou.github.io/openscene) | [(video)](https://youtu.be/jZxCLHyDJf8)

(2023) **PLA: Language-Driven Open-Vocabulary 3D Scene Understanding.** Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023. Ding, Runyu, et al. (The University of Hong Kong, ByteDance) [(paper)](https://arxiv.org/abs/2211.16312) | [(code)](https://github.com/CVMI-Lab/PLA) | [(project)](https://dingry.github.io/projects/PLA) 

(2023) **Audio visual language maps for robot navigation.** arXiv preprint arXiv:2303.07522, 2023. Huang, Chenguang, et al. (Freiburg University, Google Research, University of Technology Nuremberg). ISER 2023 [(paper)](https://arxiv.org/pdf/2303.07522.pdf) | [(code)](https://github.com/avlmaps/AVLMaps) | [(project)](https://avlmaps.github.io/) | [(colab)](https://colab.research.google.com/drive/1gdtLvg_Fbl16N3ITp5FsU9ZAG6HmspVb?usp=sharing) | [(video)](https://avlmaps.github.io/)

(2023) **Conceptfusion: Open-set multimodal 3d mapping.** arXiv preprint arXiv:2302.07241, 2023. Jatavallabhula, Krishna Murthy, et al. (MIT, Universite de Montreal, University of Toronto, IIIT Hyderabad, CMU, Amazon, Matician, DEVCOM Army Research Laboratory) [(paper)](https://arxiv.org/abs/2302.07241) | [(code)](https://github.com/concept-fusion/concept-fusion) | [(project)](https://concept-fusion.github.io/) | [(video)](https://www.youtube.com/watch?v=rkXgws8fiDs)

## Voxel-based

**Visual language maps for robot navigation.** 2023 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2023. Huang, Chenguang, et al. (Freiburg University, Google Research, University of Technology Nuremberg) [(paper)](https://arxiv.org/pdf/2210.05714.pdf) | [(code)](https://github.com/vlmaps/vlmaps.git) | [(project)](https://vlmaps.github.io/) | [(colab)](https://colab.research.google.com/drive/1xsH9Gr_O36sBZaoPNq1SmqgOOF12spV0?usp=sharing) | [(video)](https://vlmaps.github.io/)

## NeRF-based

(2023) **Lerf: Language embedded radiance fields.** In Proceedings of the IEEE/CVF International Conference on Computer Vision (pp. 19729-19739). Kerr, J., Kim, C. M., Goldberg, K., Kanazawa, A., & Tancik, M. (UC Berkeley)[(paper)](https://arxiv.org/abs/2303.09553) | [(code)](https://github.com/kerrj/lerf) | [(project)](https://www.lerf.io/) | [(dataset)](https://drive.google.com/drive/folders/1vh0mSl7v29yaGsxleadcj-LCZOE_WEWB?usp=sharing) 

(2023) **Weakly Supervised 3D Open-vocabulary Segmentation.** arXiv preprint arXiv:2305.14093. NeurIPS 2023. Liu, K., Zhan, F., Zhang, J., Xu, M., Yu, Y., Saddik, A. E., ... & Lu, S. (Nanyang Technological University, Max Planck Institute for Informatics, University of Ottawa, Carnegie Mellon University, MBZUAI) [(paper)](https://arxiv.org/abs/2305.14093) | [(code)](https://github.com/Kunhao-Liu/3D-OVS) | [(dataset)](https://drive.google.com/drive/folders/1kdV14Gu5nZX6WOPbccG7t7obP_aXkOuC?usp=sharing) 

## SDF-based

(2024) **Open-Fusion: Real-time Open-Vocabulary 3D Mapping and Queryable Scene Representation.** arXiv preprint arXiv:2310.03923 (2023). ICRA 2024. Yamazaki, Kashu, et al. (University of Arkansas, West Virginia University, University of Liverpool) [(paper)](https://arxiv.org/abs/2310.03923) | [(code)](https://github.com/UARK-AICV/OpenFusion) | [(project)](https://uark-aicv.github.io/OpenFusion/) 

# Sparse multimodal map reconstruction methods

## Object-based

(2023) **Unsupervised 3D Perception with 2D Vision-Language Distillation for Autonomous Driving.** Proceedings of the IEEE/CVF International Conference on Computer Vision. 2023. Najibi, Mahyar, et al. (Waymo LLC) [(paper)](https://arxiv.org/abs/2309.14491) 

## Object-based with relations (knowledge graphs)

(2023) **ConceptGraphs: Open-Vocabulary 3D Scene Graphs for Perception and Planning.** arXiv preprint arXiv:2309.16650, 2023. Gu, Qiao, et al. (MIT, Universite de Montreal, University of Toronto, IIIT Hyderabad, JHU APL, JHU, UMass Amherst, DEVCOM Army Research Laboratory). [(paper)](http://arxiv.org/abs/2309.16650) | [(code)](https://github.com/concept-graphs/concept-graphs) | [(project)](https://concept-graphs.github.io/) | [(video)](https://youtu.be/mRhNkQwRYnc)

(2023) **VL-SAT: Visual-Linguistic Semantics Assisted Training for 3D Semantic Scene Graph Prediction in Point Cloud.** In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (School of Software, Beihang University, The University of Hong Kong, East China University of Science and Technology). Wang, Z., Cheng, B., Zhao, L., Xu, D., Tang, Y., & Sheng, L. [(paper)](https://arxiv.org/pdf/2303.14408.pdf) | [(code)](https://github.com/wz7in/CVPR2023-VLSAT) | [(model checkpoint)](https://drive.google.com/file/d/1_C-LXRlSobupApb-JsajKG5oxKnfKgdx/view?usp=sharing) 

(2023) **Context-aware entity grounding with open-vocabulary 3d scene graphs.** arXiv preprint arXiv:2309.15940. CoRL '23. Chang, H., Boyalakuntla, K., Lu, S., Cai, S., Jing, E., Keskar, S., ... & Boularias, A. (Rutgers University-New Brunswick, Drexel University) [(paper)](https://arxiv.org/abs/2309.15940) | [(code)](https://github.com/changhaonan/OVSG) | [(project)](https://ovsg-l.github.io/) | [(dataset)](https://doi.org/10.6084/m9.figshare.24307072.v1) 

(2023) **3d vsg: Long-term semantic scene change prediction through 3d variable scene graphs.** In 2023 IEEE International Conference on Robotics and Automation (ICRA) (pp. 8179-8186). IEEE. Looper, S., Rodriguez-Puigvert, J., Siegwart, R., Cadena, C., Schmid, L. (ETH Zurich, Universidad de Zaragoza, Massachusetts Institute of Technology) [(paper)](https://arxiv.org/abs/2209.07896) | [(code)](https://github.com/ethz-asl/3d_vsg) 

## Object-based with hierarchy

(2024) **Hierarchical Open-Vocabulary 3D Scene Graphs for Language-Grounded Robot Navigation.** arXiv preprint arXiv:2403.17846. Werby, A., Huang, C., Büchner, M., Valada, A., & Burgard, W.  (University of Freiburg, University of Technology Nuremberg) [(paper)](https://arxiv.org/abs/2403.17846) | [(project)](https://hovsg.github.io/) 

(2023) **Foundations of Spatial Perception for Robotics: Hierarchical Representations and Real-time Systems.** arXiv preprint arXiv:2305.07154. Hughes, N., Chang, Y., Hu, S., Talak, R., Abdulhai, R., Strader, J., & Carlone, L. (Massachusetts Institute of Technology) [(paper)](https://arxiv.org/abs/2305.07154) | [(code)](https://github.com/MIT-SPARK/Hydra) 

## Ontology-based

(2023) **Indoor and Outdoor 3D Scene Graph Generation via Language-Enabled Spatial Ontologies.** arXiv preprint arXiv:2312.11713. Strader, J., Hughes, N., Chen, W., Speranzon, A., & Carlone, L. (Massachusetts Institute of Technology, University of California, Lockheed Martin) [(paper)](https://arxiv.org/abs/2312.11713) 

(2023) **3d scene graph prediction on point clouds using knowledge graphs.** In 2023 IEEE 19th International Conference on Automation Science and Engineering (CASE) (pp. 1-7). IEEE. Qiu, Y., & Christensen, H. I. (University of California San Diego) [(paper)](https://arxiv.org/abs/2308.06719) 

(2021) **Knowledge-inspired 3d scene graph prediction in point cloud.** Advances in Neural Information Processing Systems, 34, 18620-18632. Zhang, S., Hao, A., & Qin, H. (Beihang University, Peng Cheng Laboratory, Stony Brook University (SUNY)) [(paper)](https://proceedings.neurips.cc/paper/2021/hash/9a555403384fc12f931656dea910e334-Abstract.html)





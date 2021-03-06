---
title: "valeo.ai"
permalink: /valeoai/
author_profile: true
redirect_from:
  - /resume
---

An international team based in Paris, which conducts AI research for [Valeo](http://valeo.com) automotive applications, in collaboraton with world-class academics. Our main research is towards *better*, *clearer* & *safer* automotive AI. See our [papers](https://ptrckprz.github.io/vaipub), [projects](https://valeoai.github.io/blog/projects), [codes](https://github.com/valeoai), [posts](https://valeoai.github.io/blog) and [tweets](https://twitter.com/valeoai). 

###  Team
![](../images/vai-team.jpg)  
**Florent Bartoccioni**, PhD student  
**Hédi Ben-younes**, research scientist | [scholar](https://scholar.google.fr/citations?user=IFLcfvUAAAAJ&hl=en) | [twitter](https://twitter.com/labegne)  
**Alexandre Boulch**, research scientist | [page](http://www.boulch.eu/) | [scholar](https://scholar.google.com/citations?user=iJ3qFGAAAAAJ&hl=fr&oi=ao)| [github](https://github.com/aboulch) | [twitter](https://twitter.com/AlexandreBoulch)  
**Andrei Bursuc**, research scientist | [page](https://abursuc.github.io/) | [scholar](https://scholar.google.com/citations?user=HTfERCsAAAAJ&hl=en) | [github](https://github.com/abursuc/) | [twitter](https://twitter.com/abursuc)  
**Laura Calem**, PhD student | [github](https://github.com/lcalem) | [twitter](https://twitter.com/lauracalem)  
**Mickaël Chen**, research scientist | [page](https://sites.google.com/view/mickaelchen/home) | [scholar](https://scholar.google.fr/citations?user=QnRpMJAAAAAJ&hl=en) | [github](https://github.com/mickaelChen/)  
**Charles Corbière**, PhD student | [page](https://chcorbi.github.io/) | [scholar](https://scholar.google.fr/citations?user=UcnFUZ8AAAAJ&hl=en) | [github](https://github.com/chcorbi) | [twitter](https://twitter.com/CharlesCorbiere)  
**Matthieu Cord**, principal scientist | [page](http://www-poleia.lip6.fr/~cord/) | [scholar](https://scholar.google.fr/citations?user=SpAotDcAAAAJ&hl=en) | [twitter](https://twitter.com/quobbe)   
**Spyros Gidaris**, research scientist | [scholar](https://scholar.google.fr/citations?user=7atfg7EAAAAJ&hl=en) | [github](https://github.com/gidariss)   
**David Hurych**, research scientist | [scholar](https://scholar.google.cz/citations?user=XY1PVwYAAAAJ&hl=en)  
**Himalaya Jain**, research scientist | [page](https://himalayajain.github.io/) | [scholar](https://scholar.google.fr/citations?user=Xl7SNlsAAAAJ&hl=en) | [github](https://github.com/himalayajain)   
**Renaud Marlet**, principal scientist | [page](http://imagine.enpc.fr/~marletr/) | [scholar](https://scholar.google.fr/citations?user=2rclwh4AAAAJ&hl=en)  
**Arthur Ouaknine**, PhD student | [page](https://arthurouaknine.github.io/) | [scholar](https://scholar.google.com/citations?user=OCT3E9wAAAAJ) | [twitter](https://twitter.com/ArthurOuaknine)  
**Patrick Pérez**, scientific director | [page](https://ptrckprz.github.io/) | [scholar](https://scholar.google.fr/citations?user=8Cph5uQAAAAJ&hl=en)  
**Gilles Puy**, research scientist | [page](https://sites.google.com/site/puygilles/home) | [scholar](https://scholar.google.com/citations?user=enaORE8AAAAJ&hl=en)  
**Julien Rebut**, research scientist | [scholar](https://scholar.google.com/citations?hl=fr&user=BJcQNcoAAAAJ)  
**Simon Roburin**, PhD student | [page](http://imagine.enpc.fr/~roburins/)  
**Antoine Saporta**, PhD student | [scholar](https://scholar.google.com/citations?user=jSwfIU4AAAAJ&hl=en)   
**Tristan Schultz**, research engineer  
**Oriane Siméoni**, research scientist | [page](https://osimeoni.github.io/) | [scholar](https://scholar.google.com/citations?user=PC7ELtEAAAAJ&hl=en) | [github](https://github.com/osimeoni)  
**Huy Van Vo**, PhD student | [scholar](https://scholar.google.fr/citations?user=gIf5VqUAAAAJ&hl=en) | [github](https://github.com/huyvvo)  
**Tuan-Hung Vu**, research scientist | [page](https://tuanhungvu.github.io/) | [scholar](https://scholar.google.fr/citations?user=QIHrPZQAAAAJ&hl=en) | [github](https://github.com/tuanhungvu) | [twitter](https://twitter.com/tuanhungvu89)  
**Eloi Zablocki**, research scientist | [scholar](https://scholar.google.fr/citations?hl=en&user=dOkbUmEAAAAJ) | [twitter](https://twitter.com/EloiZablocki)  
**Léon Zheng**, PhD student 

**Human Resource Partner**: [Pascal Le Hérissé](mailto:pascal.le-herisse@valeo.com)  
**Assistant**: [Ouardia Moussouni](mailto:ouardia.moussouni@valeo.com)  
**Location**: [15 rue de La Baume](https://goo.gl/maps/5pNxVCeACzyDPi4d8), Paris  

### Some projects

*Multi-sensor perception* — Automated driving relies first on a variety of sensors, like Valeo's [fish-eye cameras](https://www.valeo.com/en/360-vue/), [LiDARs](https://www.valeo.com/en/valeo-scala/), radars and [ultrasonics](https://www.valeo.com/en/ultrasonic-parking-sensors/). Exploiting at best the outputs of each of these sensors at any instant is fundamental to understand the complex environment of the vehicle and gain robustness. To this end, we explore various machine learning approaches where sensors are considered either in isolation (as radar in [Carrada](https://arxiv.org/abs/2005.01456) at ICPR'20) or collectively (as in [xMUDA](https://valeoai.github.io/blog/publications/xmuda/) at CVPR'20).  

*3D perception* — Each sensor delivers information about the 3D world around the vehicle. Making sense of this information in terms of drivable space and important objects (road users, curb, obstacles, street furnitures) in 3D is required for the driving system to plan and act in the safest and most comfortable way. This encompasses several challenging tasks, in particular detection and segmentation of objects in point clouds as in [FKAConv](https://valeoai.github.io/blog/publications/fkaconv/) at ACCV'20.  

*Frugal learning* — Collecting diverse enough data, and annotating it precisely, is complex, costly and time-consuming. To reduce dramatically these needs, we explore various alternatives to fully-supervised learning, e.g, training that is unsupervised (as [rOSD](https://valeoai.github.io/blog/publications/rosd/) at ECCCV'20), self-supervised (as [BoWNet](https://valeoai.github.io/blog/publications/bownet/) at CVPR'20 and [OBoW](https://arxiv.org/abs/2012.11552) at CVPR'21), semi-supervised, active, zero-shot (as [ZS3](https://valeoai.github.io/blog/publications/zs3/) at NeurIPS'19) or few-shot. We also investigate training with fully-synthetic data (in combination with unsupervised domain adaptation) and with GAN-augmented data (as with Semantic Palette at CVPR'21 and [DummyNet](https://arxiv.org/abs/2012.08274) at AAAI'21).  

*Domain adaptation* — Deep learning and reinforcement learning are key technologies for autonomous driving. One of the challenges they face is to adapt to conditions which differ from those met during training. To improve systems' performance in such situations, we explore so-called "domain adaptation" techniques, as in [AdvEnt](https://valeoai.github.io/blog/publications/advent/) at CVPR'19 and [DADA](https://valeoai.github.io/blog/publications/dada/) its extension at ICCV'19.  

*Reliability* — When the unexpected happens, when the weather badly degrades, when a sensor gets blocked, the embarked perception system should continue working or, at least, diagnose the situation to react accordingly, e.g., by calling an alternative system or the human driver. With this in mind, we investigate ways to improve the robustness of neural nets to input variations, including to adversarial attacks, and to predict automatically the performance and the confidence of their predictions as in [ConfidNet](https://valeoai.github.io/blog/publications/confidnet) at NeurIPS'19. 

*Driving in action* — Getting from sensory inputs to car control goes either through a modular stack (perception > localization > forecast > planning > actuation) or, more radically, through a single end-to-end model. We work on both strategies, more specifically on action forecasting, automatic interpretation of decisions taken by a driving system, and reinforcement / imitation learning for end-to-end systems (as in [RL work](https://openaccess.thecvf.com/content_CVPR_2020/html/Toromanoff_End-to-End_Model-Free_Reinforcement_Learning_for_Urban_Driving_Using_Implicit_Affordances_CVPR_2020_paper.html) at CVPR'20).    

*Core Deep Learning* — Deep learning being now a key component of AD systems, it is important to get a better understanding of its inner workings, in particular the link between the specifics of the learning optimization and the key properties (performance, regularity, robustness, generalization) of the trained models. Among other things, we investigate the impact of popular batch normalization on standard learning procedures and the ability to learn through unsupervised distillation.      

### Code and data
* [Attributes with Fields](https://github.com/vita-epfl/detection-attributes-fields): Detecting 32 pedestrian attributes with composite fields (preprint'20 with EPFL)
* [OBoW](https://github.com/valeoai/obow): Online BoW generation for unsupervised representation learning (CVPR'21)  
* [DummyNet](https://github.com/vobecant/DummyNet): Artificial Dummies for Urban Dataset Augmentation (AAAI'21)
* [CARRADA](https://github.com/valeoai/carrada_dataset) ([dataset](http://download.tsi.telecom-paristech.fr/Carrada/Carrada.tar.gz)): Camera and Automotive Radar with Range-Angle-Doppler Annotations dataset (ICPR'20)
* [ESL](https://github.com/valeoai/ESL): Entropy-guided Self-supervised Learning for Domain Adaptation in Semantic Segmentation (workshop CVPR'20)
* [FLOT](https://github.com/valeoai/FLOT): Scene flow on point clouds guided by optimal transport (ECCV'20)
* [AdamSRT](https://github.com/ymontmarin/adamsrt): Adam exploiting BN-induced pherical invariance of CNN (arXiv 2020)
* [LightConvPoint](https://github.com/valeoai/LightConvPoint): Convolution for points (ACCV'20)
* [xMUDA](https://github.com/valeoai/xmuda): Cross-modal UDA for 3D semantic segmentation (CVPR'20)
* [LearningByCheating](https://github.com/valeoai/LearningByCheating): End-to-End driving using implicit affordances (CVPR'20)  
* [rOSD](https://github.com/huyvvo/rOSD): Unsupervised object discovery at scale (ECCV'20)  
* [ConvPoint](https://github.com/aboulch/ConvPoint): Convolutions for unstructured point clouds (Computer \& Graphics 2020)  
* [BEEF](https://github.com/valeoai/BEEF): Driving behavior explanation with multi-level fusion (workshop NeurIPS'20) 
* [Woodscape](https://woodscape.valeo.com/): Driving fisheye multi-task dataset (ICCV'19)
* [ZS3](https://github.com/valeoai/ZS3): Zero-Shot Semantic Segmentation (NeurIPS'19)
* [BF3S](https://github.com/valeoai/BF3S): Boosting few-shot visual learning with self-supervision (ICCV'19)
* [ConfidNet](https://github.com/valeoai/ConfidNet): Addressing failure prediction by learning model confidence (NeurIPS'19)
* [Rainbow-IQN Ape-X](https://github.com/valeoai/rainbow-iqn-apex): effective RL combination for Atari games
* [DADA](https://github.com/valeoai/DADA): Depth-aware Domain Adaptation in Semantic Segmentation (ICCV'19)
* [AdvEnt](https://github.com/valeoai/ADVENT): Adversarial Entropy minimization for domain adaptation in semantic segmentation (CVPR'19)
* [OSD](https://github.com/huyvvo/OSD): Unsupervised object discovery as optimization (CVPR'19)  

###  Academic partners
CNAM ([Nicolas Thome](http://cedric.cnam.fr/~thomen/))  
CTU Prague ([Josef Sivic](https://www.di.ens.fr/~josef/))  
EPFL ([Alexandre Alahi](https://people.epfl.ch/alexandre.alahi))  
ENS Lyon ([Rémi Gribonval](https://scholar.google.com/citations?user=EcqbX1QAAAAJ))  
INRIA ([Jean Ponce](https://www.di.ens.fr/~ponce/), [Karteek Alahari](https://lear.inrialpes.fr/people/alahari/))  
MPI ([Christian Theobalt](https://people.mpi-inf.mpg.de/~theobalt/))  
Ponts ([Mathieu Aubry](http://imagine.enpc.fr/~aubrym/))  
Sorbonne ([Matthieu Cord](http://www-poleia.lip6.fr/~cord/))  
Télécom ([Florence Tupin](https://perso.telecom-paristech.fr/tupin/), [Alasdair Newson](https://sites.google.com/site/alasdairnewson/), [Florence d'Alché-Buc](https://scholar.google.com/citations?user=-qbL7z0AAAAJ))

### News
* 06/2020: Spyros Gidaris to serve as Area Chair for CVPR 2022
* 06/2020: Reanud Marlet to serve as Meta-reviewer for BMVC 2021
* 06/2020: Valeo.ai participates to CVPR'21 presenting three papers, co-organizing a [tutorial on self-supervised learning](https://gidariss.github.io/self-supervised-learning-cvpr2021/) and the [OmniCV workshop](https://sites.google.com/view/omnicv2021) and delivering keynotes at [SAIAD](https://sites.google.com/view/saiad2021) and [Vision4AllSeason](https://vision4allseason.net/) workshops.
* 06/2020: Matthieu Cord serves as Area Chair for NeurIPS 2021
* 05/2020 Alexandre Boulch, Andrei Bursuc, Matthieu Cord, Renaud Marlet, Spyros Gidaris and Tuan-Hung Vu among the [Outstanding Reviewers of CVPR'21](http://cvpr2021.thecvf.com/node/184)
* 05/2021: Paper on [Confidence estimation via auxiliary models](https://arxiv.org/abs/2012.06508) accepted in IEEE T-PAMI
* 04/2021: [Woodscape Challenge](https://sites.google.com/view/omnicv2021/woodscape-challenge) on fisheye semantic scene segmentation in conjunctin with CVPR'21 OmniCV workshop
* 03/2021: Marin Toromanoff defends his PhD at MinesParis, committee: O. Pietquin, Th. Chateau, P.-Y. Oudeyer, R. Munos, Ch. Gagne, F. Moutarde, X. Perrotton
* 03/2021: Three [papers](https://ptrckprz.github.io/vaipub) accepted at [CVPR'21](http://cvpr2021.thecvf.com/) (23.7% acceptance rate)
* 02/2021: Matthieu Cord delivers keynote at [Machine Learning Prague](https://www.mlprague.com/)
* 02/2021: Blog [post](https://valeoai.github.io/blog/2021/02/18/explainable-driving.html) on the explainability of neural driving models 
* 01/2021: Preprint on [Cross-modal learning for domain adaptation in 3D semantic segmentation](https://arxiv.org/abs/2101.07253)
* 01/2021: Preprint on the [Explainability of vision-based autonomous driving systems](https://arxiv.org/abs/2101.05307)
* 12/2020: Preprint on [Online BoW prediction for unsupervised representation learning](https://arxiv.org/abs/2012.11552) with [code](https://github.com/valeoai/obow).  
* 12/2020: Preprint on project with EPFL: [Detecting 32 pedestrian attributes for autonomous vehicles](https://arxiv.org/abs/2012.02647) with [code](https://github.com/vita-epfl/detection-attributes-fields)
* 12/2020: Valeo participates with keynote and posters to [ML4AD](https://ml4ad.github.io/) virtual workshop at NeurIPS'20
* 12/2020: One [paper](https://ptrckprz.github.io/vaipub) in collaboration with CTU Prague accepted at [AAAI'21](https://aaai.org/Conferences/AAAI-21/).
* 11/2020: IV2020 workshop on 3D Deep Learning for Autonomous Driving ([3D-DLAD](https://sites.google.com/view/3d-dlad-v2-iv2020))
* 10/2020: Dataset for our ICPR'20 paper "CARRADA Dataset: Camera and Automotive Radar with Range-Angle-Doppler Annotations" ([CARRADA](https://github.com/valeoai/carrada_dataset))
* 10/2020: Four team members (Andrei, Matthieu, Patrick and Spyros) acknowledged as Outstanding Reviewers at NeurIPS'20
* 07/2020: Code for our ECCV'20 paper "FLOT: Scene flow on point clouds guided by optimal transport" ([FLOT](https://github.com/valeoai/FLOT)).
* 06/2020: Seven [papers](https://ptrckprz.github.io/vaipub) accepted at [ECCV'20](https://eccv2020.eu/) (27% acceptance rate)
* 06/2020: Four team members (Alexandre, Andrei, Matthieu and Renaud) acknowledged as Outstanding Reviewers at CVPR'20
* 06/2020: Valeo.ai participates to (virtual) CVPR'20, presenting 5 papers in main conference, delivering tutorials on [annotation-efficient learning](https://annotation-efficient-learning.github.io/), co-organizing the [OmniCV](https://sites.google.com/view/omnicv-cvpr2020/) workshop and presenting keynote at the [SAIAD](https://sites.google.com/view/saiad2020/) workshop.
* 06/2020: Maximilian Jaritz defends his PhD at Inria Paris on “2D-3D Scene Understanding for Autonomous Driving” (reviewers: V. Lepetit and G. Brostow, external examiners: A. Dai and F. Jurie).
* 06/2020: Code for our CVPR'20 paper "xMUDA: Cross-Modal Unsupervised Domain Adaptation for 3D Semantic Segmentation" ([xMUDA](https://github.com/valeoai/xmuda)).
* 04/2020: Eloi Zablocki receives the [Second Best Thesis Prize from the French Association for AI](https://afia.asso.fr/breves-davril-2020/).
* 02/2020: Code for our NeurIPS'19 paper "Zero-Shot Semantic Segmentation" ([ZS3](https://github.com/valeoai/ZS3)).
* 02/2020: Five [papers](https://ptrckprz.github.io/vaipub) accepted at [CVPR'20](http://cvpr2020.thecvf.com/) (22% acceptance rate), inc. one oral.
* 01/2020: Spyros Gidaris, Andrei Bursuc and Karteek Alahari (Inria) to deliver a [tutorial](https://annotation-efficient-learning.github.io/) on Few-Shot, Self-Supervised, and Incremental Learning at CVPR'20. 
* 01/2020: Pedestrian monitoring demo at CES, Las Vegas.
* 12/2019: Medium post: [Is deep Reinforcement Learning really superhuman on Atari?](https://medium.com/@valeo.ai/is-deep-reinforcement-learning-really-superhuman-on-atari-2e34f8ae1eed)
* 12/2019: Code for our ICCV'19 paper "Boosting few-shot visual learning with self-supervision" ([BF3S](https://github.com/valeoai/BF3S)).
* 12/2019: Code for our ICCV'19 paper "DADA: Depth-Aware Domain Adaptation in semantic segmentation" ([DADA](https://github.com/valeoai/DADA)).
* 11/2019: Spyros Gidaris receives the Thesis Prize from [Université Paris Est](https://www.univ-paris-est.fr/evenements/evenement/9ca2fa43ca68cce620d7ba8dfc59f7d0/?tx_news_pi1%5Bnews%5D=773&tx_news_pi1%5Bcontroller%5D=News&tx_news_pi1%5Baction%5D=detail&tx_news_pi1%5Bday%5D=5&tx_news_pi1%5Bmonth%5D=11&tx_news_pi1%5Byear%5D=2019).
* 10/2019: Valeo.ai researchers present 5 papers at [ICCV'19](http://iccv2019.thecvf.com/) in Seoul, Korea, and Valeo participates to associated workshops on [Autonomous Driving](https://adworkshop.org/) and on [Autonomous Navigation in Unconstrained Environments](https://cvit.iiit.ac.in/autonue2019/program-s.html). 
* 10/2019: [PRAIRIE](https://prairie-institute.fr/) research institute is officially launched, with a nice day of talks and pannels (inc. one on future mobility, [program](https://prairie-institute.fr/wp-content/uploads/2019/10/PROGRAMME-VF-HD-.pdf) in French). Followed by PRAIRIE AI Summer School ([PAISS](https://project.inria.fr/paiss/)), where Patrick Pérez delivered a lecture ([slides](https://project.inria.fr/paiss/files/2019/10/2019_10_paiss_perez_noanim.pdf)).    
* 09/2019: Code of our NeurIPS'19 paper "Addressing failure prediction by learning model confidence" ([ConfidNet](https://github.com/valeoai/ConfidNet)). 
* 09/2019: Work of Marin Toromanoff *et al.* discussed by Andrew Ng in [The Batch](https://info.deeplearning.ai/the-batch-autonomous-nuclear-weapons-fighting-deepfakes-recognizing-chimps-automating-fast-food-2) (deeplearning.ai newsletter).
* 09/2019: Two [papers](https://ptrckprz.github.io/vaipub) accepted at [NeurIPS'19](https://nips.cc/) (21% acceptance rate). 
* 09/2019: Matthieu Cord among NeurIPS'19 top [contributors](https://medium.com/@dcharrezt/neurips-2019-stats-c91346d31c8f).
* 07/2029: Medium post: [ADVENT: Adversarial entropy minimization for domain adaptation in semantic segmentation](https://medium.com/@valeo.ai/advent-adversarial-entropy-minimization-for-domain-adaptation-in-semantic-segmentation-dba21934430b).
* 07/2019: Three [papers](https://ptrckprz.github.io/vaipub) accepted at [ICCV'19](http://iccv2019.thecvf.com/) (24% acceptance rate), including one oral (4.6% acceptance rate).
* 07/2019: Code of our CVPR'19 paper "AdvEnt: Adversarial Entropy Minimization for Domain Adaptation in Semantic Segmentation" is available on [valeo.ai github](https://github.com/valeoai/ADVENT). 
* 07/2019: Marin Toromanoff (PhD student with Mines ParisTech, Valeo DAR and Valeo.ai) ranks 1st on Track 2 of [Carla Challenge 2019](https://carlachallenge.org/results-challenge-2019/), and 2nd on Track 1.   
* 06/2019: Spyros Gidaris receives the [Best Thesis Prize from Ponts Foundation](https://www.fondationdesponts.fr/spyros-gidaris-laureat-ex-aequo-du-prix-de-la-meilleure-these-2019/). 
* 06/2019: Valeo.ai researchers present 8 papers (25% acceptance rate), including 4 orals (5.6% acceptance rate), at [CVPR'19](http://cvpr2019.thecvf.com/). Patrick Pérez delivers keynote on "Sustainable supervision with application to autonomous driving" at the Safe AI for Automated Driving ([SAIAD](https://sites.google.com/view/saiad-wscvpr19)) CVPR'19 Workshop. 
* 05/2019: Hedi Ben-younes defends his PhD at Sorbonne Université, committee: M. Cord, V. Ferrari, Y. LeCun, P. Pérez, L. Soulier, N. Thome, J. Verbeek, Ch. Wolf.
* 05/2019: Himalaya Jain receives the [Best Thesis Prize from Rennes 1 Foundation](https://www.irisa.fr/en/actus/congratulations-himalaya-jain-his-thesis-prize-rennes-1-foundation). 
* 05/2019: Valeo is proud to be part of [Prairie](https://www.inria.fr/en/news/news-from-inria/launch-of-the-prairie-institute), the new Paris Interdisciplinary Artificial Intelligence Institute. Stay tuned.

### Commnunication

* With seven other France’s global industry players, Valeo signs a [Manifesto on AI for Industry](https://www.valeo.com/en/ai-for-humanity-french-industry-engages-on-artificial-intelligence/).   
* Jacques Aschenbroich (Chairman and CEO of Valeo) on [AI and valeo.ai](https://www.linkedin.com/pulse/valeo-our-order-intake-already-includes-ai-jacques-aschenbroich/).  
* Valeo Drive4u automated car [in Paris center, a world premiere](https://www.valeo.com/en/valeo-drive4u-the-first-autonomous-car-to-be-demonstrated-on-the-streets-of-paris/)!  
* Patrick Pérez on the [start of Valeo.ai](https://www.youtube.com/watch?time_continue=2&v=B5QWcDTTBrQ).  
* Valeo Cruise4u automated car, [24h on Parisian ringroad](https://www.youtube.com/watch?v=XRKXBKPgYI4).

### Alumni

**Marin Toromanoff**, PhD student ([scholar](https://scholar.google.com/citations?user=Yu47MFYAAAAJ&hl=en)), now at Valeo Driving Assistance Research  
**Maxime Bucher**, research scientist ([page](https://maximebucher.github.io/),[scholar](https://scholar.google.fr/citations?user=NbYEOpMAAAAJ&hl=en)), now at Augustus Intelligence   
**Maximilian Jaritz**, PhD student ([page](https://team.inria.fr/rits/membres/maximilian-jaritz/), [scholar](https://scholar.google.com/citations?user=yt2IsdAAAAAJ)), now at Amazon  
**Gabriel de Marmiesse**, research engineer ([github](https://github.com/gabrieldemarmiesse)), now at EarthCube  
**Emilie Wirbel**, research scientist ([scholar](https://scholar.google.com/citations?hl=en)), now at NVidia  


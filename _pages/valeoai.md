---
title: "valeo.ai"
permalink: /valeoai/
author_profile: true
redirect_from:
  - /resume
---

An international team based in Paris, which conducts AI research for [Valeo](http://valeo.com) automotive applications, in collaboraton with world-class academics. Our main research is towards *better*, *clearer* & *safer* automotive AI. See our [papers](https://ptrckprz.github.io/vaipub), [codes](https://github.com/valeoai), [posts](https://medium.com/@valeo.ai) and [tweets](https://twitter.com/valeoai). 

###  Team
![](../images/vai-team.jpg)  
  
**Hedi Ben-younes**, research scientist | [scholar](https://scholar.google.fr/citations?user=IFLcfvUAAAAJ&hl=en) | [twitter](https://twitter.com/labegne)  
**Florent Bartoccioni**, PhD student  
**Alexandre Boulch**, research scientist | [page](http://www.boulch.eu/) | [scholar](https://scholar.google.com/citations?user=iJ3qFGAAAAAJ&hl=fr&oi=ao) | [twitter](https://twitter.com/AlexandreBoulch)  
**Maxime Bucher**, research scientist | [page](https://maximebucher.github.io/) | [scholar](https://scholar.google.fr/citations?user=NbYEOpMAAAAJ&hl=en)  
**Andrei Bursuc**, research scientist | [page](https://abursuc.github.io/) | [scholar](https://scholar.google.com/citations?user=HTfERCsAAAAJ&hl=en) | [twitter](https://twitter.com/abursuc)  
**Charles Corbière**, PhD student | [page](https://chcorbi.github.io/) | [scholar](https://scholar.google.fr/citations?user=UcnFUZ8AAAAJ&hl=en) | [twitter](https://twitter.com/CharlesCorbiere)  
**Matthieu Cord**, principal scientist | [page](http://www-poleia.lip6.fr/~cord/) | [scholar](https://scholar.google.fr/citations?user=SpAotDcAAAAJ&hl=en) | [twitter](https://twitter.com/quobbe)   
**Spyros Gidaris**, research scientist | [scholar](https://scholar.google.fr/citations?user=7atfg7EAAAAJ&hl=en)  
**David Hurych**, research scientist | [scholar](https://scholar.google.cz/citations?user=XY1PVwYAAAAJ&hl=en)  
**Himalaya Jain**, research scientist | [page](https://himalayajain.github.io/) | [scholar](https://scholar.google.fr/citations?user=Xl7SNlsAAAAJ&hl=en)   
**Renaud Marlet**, principal scientist | [page](http://imagine.enpc.fr/~marletr/) | [scholar](https://scholar.google.fr/citations?user=2rclwh4AAAAJ&hl=en)  
**Arthur Ouaknine**, PhD student | [twitter](https://twitter.com/ArthurOuaknine)  
**Patrick Pérez**, scientific director | [page](https://ptrckprz.github.io/) | [scholar](https://scholar.google.fr/citations?user=8Cph5uQAAAAJ&hl=en)  
**Gilles Puy**, research scientist | [page](https://sites.google.com/site/puygilles/home) | [scholar](https://scholar.google.com/citations?user=enaORE8AAAAJ&hl=en)  
**Julien Rebut**, research scientist  
**Simon Roburin**, PhD student | [page](http://imagine.enpc.fr/~roburins/)  
**Antoine Saporta**, PhD student | [scholar](https://scholar.google.com/citations?user=jSwfIU4AAAAJ&hl=en)   
**Marin Toromanoff**, PhD student | [scholar](https://scholar.google.com/citations?user=Yu47MFYAAAAJ&hl=en)  
**Huy Van Vo**, PhD student | [scholar](https://scholar.google.fr/citations?user=gIf5VqUAAAAJ&hl=en)  
**Tuan-Hung Vu**, research scientist | [page](https://tuanhungvu.github.io/) | [scholar](https://scholar.google.fr/citations?user=QIHrPZQAAAAJ&hl=en) | [twitter](https://twitter.com/tuanhungvu89)  
**Emilie Wirbel**, research scientist | [scholar](https://scholar.google.com/citations?hl=en&user=Z7wRy_cAAAAJ)  
**Eloi Zablocki**, research scientist | [scholar](https://scholar.google.fr/citations?hl=en&user=dOkbUmEAAAAJ) | [twitter](https://twitter.com/EloiZablocki)  

### Some projects

*Multi-sensor perception* — Automated driving relies first on a diverse range of sensors, like Valeo's [fish-eye cameras](https://www.valeo.com/en/360-vue/), [LiDARs](https://www.valeo.com/en/valeo-scala/), radars and ultrasonics. Exploiting at best the outputs of each of these sensors at any instant is fundamental to understand the complex environment of the vehicle. To this end, we explore various deep learning approaches where sensors are considered both in isolation and collectively.  

*3D dynamic perception* — Each sensor delivers information about the 3D world around the vehicle and its temporal evolution. Dectecting, segmenting and tracking important objects (road users, obstacles, street furnitures, etc.) in 3D, as well as forecasting their possible futures, is required for the driving system to plan and act in the safest and most confortable way. This encompasses a wide range of challenging tasks that our research tackles.   

*Domain adaptation* — Deep learning and reinforcement learning are key technologies for autonomous driving. One of the challenges they face is to adapt to conditions which differ from those met during training. To improve systems' performance in such situations, we explore so-called "domain adaptation" techniques, as in [AdvEnt](https://github.com/valeoai/ADVENT), our project presented at CVPR'19 and [DADA](https://github.com/valeoai/DADA) its extension presented at ICCV'19.  

*Uncertainty estimation and performance prediction* — When the unexpected happens, when the weather badly degrades, when a sensor gets blocked, the embarked perception system should diagnose the situation and react accordingly, e.g., by calling an alternative system or the human driver. With this in mind, we investigate automatic ways to assess the uncertainty of a system and to predict its performance, as in [ConfidNet](https://github.com/valeoai/ConfidNet), our project presented at NeurIPS'19.

### Code (PyTorch)

* [AdamSRT](https://github.com/ymontmarin/adamsrt): Adam exploiting BN-induced pherical invariance of CNN (arXiv 2020)
* [LightConvPoint](https://github.com/valeoai/LightConvPoint): Convolution for points (arXiv 2020)
* [xMUDA](https://github.com/valeoai/xmuda): Cross-modal UDA for 3D semantic segmentation (CVPR'20)
* [LearningByCheating](https://github.com/valeoai/LearningByCheating): End-to-End driving using implicit affordances (CVPR'20)
* [ZS3](https://github.com/valeoai/ZS3): Zero-Shot Semantic Segmentation (NeurIPS'19)
* [BF3S](https://github.com/valeoai/BF3S): Boosting few-shot visual learning with self-supervision (ICCV'19)
* [ConfidNet](https://github.com/valeoai/ConfidNet): Addressing failure prediction by learning model confidence (NeurIPS'19)
* [Rainbow-IQN Ape-X](https://github.com/valeoai/rainbow-iqn-apex): effective RL combination for Atari games
* [DADA](https://github.com/valeoai/DADA): Depth-aware Domain Adaptation in Semantic Segmentation (ICCV'19)
* [AdvEnt](https://github.com/valeoai/ADVENT): Adversarial Entropy minimization for domain adaptation in semantic segmentation (CVPR'19)

###  Academic partners

CNAM ([Nicolas Thome](http://cedric.cnam.fr/~thomen/))  
CTU Prague ([Josef Sivic](https://www.di.ens.fr/~josef/))  
EPFL ([Alexandre Alahi](https://people.epfl.ch/alexandre.alahi))  
INRIA ([Jean Ponce](https://www.di.ens.fr/~ponce/), [Karteek Alahari](https://lear.inrialpes.fr/people/alahari/))  
MPI ([Christian Theobalt](https://people.mpi-inf.mpg.de/~theobalt/))  
Ponts ([Mathieu Aubry](http://imagine.enpc.fr/~aubrym/))  
Sorbonne ([Matthieu Cord](http://www-poleia.lip6.fr/~cord/))  
Télécom ([Florence Tupin](https://perso.telecom-paristech.fr/tupin/), [Alasdair Newson](https://sites.google.com/site/alasdairnewson/), [Florence d'Alché-Buc](https://scholar.google.com/citations?user=-qbL7z0AAAAJ))

### News
* 06/2020: Seven [papers](https://ptrckprz.github.io/vaipub) accepted at [ECCV'20](http://cvpr2020.thecvf.com/) (27% acceptance rate)
* 06/2020: Valeo.ai participates to (virtual) CVPR'20, presenting 5 papers in main conference, delivering tutorials on [annotation-efficient learning](https://annotation-efficient-learning.github.io/), co-organizing the [OmniCV](https://sites.google.com/view/omnicv-cvpr2020/) workshop and presenting keynote at the [SAIAD](https://sites.google.com/view/saiad2020/) workshop.
* 06/2020: Maximilian Jaritz defends his PhD at Inria Paris on “2D-3D Scene Understanding for Autonomous Driving” (reviewers: V. Lepetit and G. Brostow, external examiners: A. Dai and F. Jurie).
* 06/2020:  Code for our CVPR'20 paper "xMUDA: Cross-Modal Unsupervised Domain Adaptation for 3D Semantic Segmentation" ([xMUDA](https://github.com/valeoai/xmuda)).
* 02/2020:  Code for our NeurIPS'19 paper "Zero-Shot Semantic Segmentation" ([ZS3](https://github.com/valeoai/ZS3)).
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
* 09/2019: Matthieu Cord among NeurIPS'19 top [cont](https://medium.com/@dcharrezt/neurips-2019-stats-c91346d31c8f).
* 07/2029: Medium post: [ADVENT: Adversarial entropy minimization for domain adaptation in semantic segmentation](https://medium.com/@valeo.ai/advent-adversarial-entropy-minimization-for-domain-adaptation-in-semantic-segmentation-dba21934430b).
* 07/2019: Three [papers](https://ptrckprz.github.io/vaipub) accepted at [ICCV'19](http://iccv2019.thecvf.com/) (24% acceptance rate), including one oral (4.6% acceptance rate).
* 07/2019: Code of our CVPR'19 paper "AdvEnt: Adversarial Entropy Minimization for Domain Adaptation in Semantic Segmentation" is available on [valeo.ai github](https://github.com/valeoai/ADVENT). 
* 07/2019: Marin Toromanoff (PhD student with Mines ParisTech, Valeo DAR and Valeo.ai) ranks 1st on Track 2 of [Carla Challenge 2019](https://carlachallenge.org/results-challenge-2019/), and 2nd on Track 1.   
* 06/2019: Spyros Gidaris receives the [Best Thesis Prize from Ponts Foundation](https://www.fondationdesponts.fr/spyros-gidaris-laureat-ex-aequo-du-prix-de-la-meilleure-these-2019/). 
* 06/2019: Valeo.ai researchers present 8 papers (25% acceptance rate), including 4 orals (5.6% acceptance rate), at [CVPR'19](http://cvpr2019.thecvf.com/). Patrick Pérez delivers keynote on "Sustainable supervision with application to autonomous driving" at the Safe AI for Automated Driving ([SAIAD](https://sites.google.com/view/saiad-wscvpr19)) CVPR'19 Workhsop. 
* 05/2019: Hedi Ben-younes defends his PhD at Sorbonne Université, committee: M. Cord, V. Ferrari, Y. LeCun, P. Pérez, L. Soulier, N. Thome, J. Verbeek, Ch. Wolf.
* 05/2019: Himalaya Jain receives the [Best Thesis Prize from Rennes 1 Foundation](https://www.irisa.fr/en/actus/congratulations-himalaya-jain-his-thesis-prize-rennes-1-foundation). 
* 05/2019: Valeo is proud to be part of [Prairie](https://www.inria.fr/en/news/news-from-inria/launch-of-the-prairie-institute), the new Paris Interdisciplinary Artificial Intelligence Institute. Stay tuned.

### Commnunication

* With seven other France’s global industry players, Valeo signs a [Manifesto on AI for Industry](https://www.valeo.com/en/ai-for-humanity-french-industry-engages-on-artificial-intelligence/).   
* Jacques Aschenbroich (Chairman and CEO of Valeo) on [AI and valeo.ai](https://www.linkedin.com/pulse/valeo-our-order-intake-already-includes-ai-jacques-aschenbroich/).  
* Valeo Drive4u automated car [in Paris center, a world premiere](https://www.valeo.com/en/valeo-drive4u-the-first-autonomous-car-to-be-demonstrated-on-the-streets-of-paris/)!  
* Patrick Pérez on the [start of Valeo.ai](https://www.youtube.com/watch?time_continue=2&v=B5QWcDTTBrQ).  
* Valeo Cruise4u automated car, [24h on Parisian ringroad](https://www.youtube.com/watch?v=XRKXBKPgYI4).


**Human Resource Partner**: [Pascal Le Herisse](mailto:pascal.le-herisse@valeo.com)  
**Assistant**: [Ouardia Moussouni](mailto:ouardia.moussouni@valeo.com)  
**Location**: [15 rue de La Baume](https://goo.gl/maps/5pNxVCeACzyDPi4d8), Paris  

### Alumni

**Maximilian Jaritz**, PhD student ([page](https://team.inria.fr/rits/membres/maximilian-jaritz/), [scholar](https://scholar.google.com/citations?user=yt2IsdAAAAAJ)), now at Amazon  
**Gabriel de Marmiesse**, research engineer ([github](https://github.com/gabrieldemarmiesse)), now at Hearthcube  

---
title: "valeo2.ai"
permalink: /valeoai2/
author_profile: true
redirect_from:
  - /resume
---

**We are** an open, international, research lab based in Paris  

**We aim**
* to conduct cutting-edge AI research for automotive applications (see our [papers](https://ptrckprz.github.io/vaipub) and [codes](https://github.com/valeoai))
* to nurture collaborations with world-class academic teams
* to irrigate [Valeo](http://valeo.com)’s R&D    

**We work** towards *better*, *lighter*, *clearer* & *safer* automotive AI 

## The team
![](../images/vai-team.jpg)  
  
Hedi Ben-younes (research scientist) [scholar](https://scholar.google.fr/citations?user=IFLcfvUAAAAJ&hl=en)  
[Alexandre Boulch](http://www.boulch.eu/) (research scientist) [scholar](https://scholar.google.com/citations?user=iJ3qFGAAAAAJ&hl=fr&oi=ao)  
[Maxime Bucher](https://maximebucher.github.io/) (research scientist) [scholar](https://scholar.google.fr/citations?user=NbYEOpMAAAAJ&hl=en)  
[Andrei Bursuc](https://abursuc.github.io/) (research scientist) [scholar](https://scholar.google.com/citations?user=HTfERCsAAAAJ&hl=en)  
[Charles Corbière](https://chcorbi.github.io/) (PhD student) [scholar](https://scholar.google.fr/citations?user=UcnFUZ8AAAAJ&hl=en)  
[Matthieu Cord](http://www-poleia.lip6.fr/~cord/) (principal scientist) [scholar](https://scholar.google.fr/citations?user=SpAotDcAAAAJ&hl=en)   
Spyros Gidaris (research scientist) [scholar](https://scholar.google.fr/citations?user=7atfg7EAAAAJ&hl=en)  
David Hurych (research scientist) [scholar](https://scholar.google.cz/citations?user=XY1PVwYAAAAJ&hl=en)  
[Himalaya Jain](https://himalayajain.github.io/) (research scientist) [scholar](https://scholar.google.fr/citations?user=Xl7SNlsAAAAJ&hl=en)  
[Maximilian Jaritz](https://team.inria.fr/rits/membres/maximilian-jaritz/) (PhD student) [scholar](https://scholar.google.com/citations?user=yt2IsdAAAAAJ&hl=en)  
[Renaud Marlet](http://imagine.enpc.fr/~marletr/) (principal scientist) [scholar](https://scholar.google.fr/citations?user=2rclwh4AAAAJ&hl=en)  
Gabriel de Marmiesse (research engineer)  
Arthur Ouaknine (PhD student)  
[Patrick Pérez](https://ptrckprz.github.io/) (scientific director) [scholar](https://scholar.google.fr/citations?user=8Cph5uQAAAAJ&hl=en)  
[Gilles Puy](https://sites.google.com/site/puygilles/home) (research scientist) [scholar](https://scholar.google.com/citations?user=enaORE8AAAAJ&hl=en)  
Julien Rebut (research scientist)  
Simon Roburin (PhD student)  
Antoine Saporta (PhD student)  
Marin Toromanoff (PhD student) [scholar](https://scholar.google.com/citations?user=Yu47MFYAAAAJ&hl=en)  
Huy Van Vo (PhD student) [scholar](https://scholar.google.fr/citations?user=gIf5VqUAAAAJ&hl=en)  
[Tuan-Hung Vu](https://tuanhungvu.github.io/) (research scientist) [scholar](https://scholar.google.fr/citations?user=QIHrPZQAAAAJ&hl=en)  
Eloi Zablocki (research scientist) [scholar](https://scholar.google.fr/citations?hl=en&user=dOkbUmEAAAAJ)

## Openings
- High profile research scientists in machine learning or in 3D scene understanding  
- AI research engineer  

*Please contact me*

## Some projects
(for not too technical updates, follow us on [Medium](https://medium.com/@valeo.ai) and [Twitter](https://twitter.com/valeoai))

*Multi-sensor perception* — Automated driving relies first on a variety of sensors, like Valeo's [fish-eye cameras](https://www.valeo.com/en/360-vue/), [LiDARs](https://www.valeo.com/en/valeo-scala/), radars and [ultrasonics](https://www.valeo.com/en/ultrasonic-parking-sensors/). Exploiting at best the outputs of each of these sensors at any instant is fundamental to understand the complex environment of the vehicle and gain robustness. To this end, we explore various machine learning approaches where sensors are considered either in isolation (as radar in [Carrada](https://arxiv.org/abs/2005.01456) at ICPR'20) or collectively (as in [xMUDA](https://valeoai.github.io/blog/publications/xmuda/) at CVPR'20).  

*3D perception* — Each sensor delivers information about the 3D world around the vehicle. Making sense of this information in terms of drivable space and important objects (road users, curb, obstacles, street furnitures) in 3D is required for the driving system to plan and act in the safest and most comfortable way. This encompasses several challenging tasks, in particular detection and segmentation of objects in point clouds as in [FKAConv](https://valeoai.github.io/blog/publications/fkaconv/) at ACCV'20.  

*Frugal learning* — Collecting diverse enough data, and annotating it precisely, is complex, costly and time-consuming. To reduce dramatically these needs, we explore various alternatives to fully-supervised learning, e.g, training that is unsupervised (as [rOSD](https://valeoai.github.io/blog/publications/rosd/) at ECCCV'20), self-supervised (as [BoWNet](https://valeoai.github.io/blog/publications/bownet/) at CVPR'20 and [OBoW](https://arxiv.org/abs/2012.11552) at CVPR'21), semi-supervised, active, zero-shot (as [ZS3](https://valeoai.github.io/blog/publications/zs3/) at NeurIPS'19) or few-shot. We also investigate training with fully-synthetic data (in combination with unsupervised domain adaptation) and with GAN-augmented data (as with Semantic Palette at CVPR'21 and [DummyNet](https://arxiv.org/abs/2012.08274) at AAAI'21).  

*Domain adaptation* — Deep learning and reinforcement learning are key technologies for autonomous driving. One of the challenges they face is to adapt to conditions which differ from those met during training. To improve systems' performance in such situations, we explore so-called "domain adaptation" techniques, as in [AdvEnt](https://valeoai.github.io/blog/publications/advent/) at CVPR'19 and [DADA](https://valeoai.github.io/blog/publications/dada/) its extension at ICCV'19.  

*Reliability* — When the unexpected happens, when the weather badly degrades, when a sensor gets blocked, the embarked perception system should continue working or, at least, diagnose the situation to react accordingly, e.g., by calling an alternative system or the human driver. With this in mind, we investigate ways to improve the robustness of neural nets to input variations, including to adversarial attacks, and to predict automatically the performance and the confidence of their predictions as in [ConfidNet](https://valeoai.github.io/blog/publications/confidnet) at NeurIPS'19. 

*Driving in action* — Getting from sensory inputs to car control goes either through a modular stack (perception > localization > forecast > planning > actuation) or, more radically, through a single end-to-end model. We work on both strategies, more specifically on action forecasting, automatic interpretation of decisions taken by a driving system, and reinforcement / imitation learning for end-to-end systems (as in [RL work](https://openaccess.thecvf.com/content_CVPR_2020/html/Toromanoff_End-to-End_Model-Free_Reinforcement_Learning_for_Urban_Driving_Using_Implicit_Affordances_CVPR_2020_paper.html) at CVPR'20).    

*Core Deep Learning* — Deep learning being now a key component of AD systems, it is important to get a better understanding of its inner workings, in particular the link between the specifics of the learning optimization and the key properties (performance, regularity, robustness, generalization) of the trained models. Among other things, we investigate the impact of popular batch normalization on standard learning procedures and the ability to learn through unsupervised distillation.      

## Code, data and posts

On our [github](https://github.com/valeoai):  
* [BF3S](https://github.com/valeoai/BF3S): Boosting few-shot visual learning with self-supervision (ICCV'19) - PyTorch
* [ConfidNet](https://github.com/valeoai/ConfidNet): Addressing failure prediction by learning model confidence (NeurIPS'19) - PyTorch
* [Rainbow-IQN Ape-X](https://github.com/valeoai/rainbow-iqn-apex): effective RL combination for Atari games - PyTorch
* [DADA](https://github.com/valeoai/DADA): Depth-aware Domain Adaptation in Semantic Segmentation (ICCV'19) - PyTorch
* [AdvEnt](https://github.com/valeoai/ADVENT): Adversarial Entropy minimization for domain adaptation in semantic segmentation (CVPR'19) - PyTorch

## Our academic partners

Czech Technical University in Prague ([Josef Sivic](https://www.di.ens.fr/~josef/))  
EPFL ([Alexandre Alahi](https://people.epfl.ch/alexandre.alahi))  
INRIA ([Jean Ponce](https://www.di.ens.fr/~ponce/), Inria Paris and [Karteek Alahari](https://lear.inrialpes.fr/people/alahari/), Inria Grenoble)  
le CNAM ([Nicolas Thome](http://cedric.cnam.fr/~thomen/) and [Avner Bar-hen](https://ab-h.github.io/index.html))  
Max Planck Institute ([Christian Theobalt](https://people.mpi-inf.mpg.de/~theobalt/))  
Ponts ParisTech ([Mathieu Aubry](http://imagine.enpc.fr/~aubrym/))  
Sorbonne Université ([Matthieu Cord](http://www-poleia.lip6.fr/~cord/))  
Telecom ParisTech ([Florence Tupin](https://perso.telecom-paristech.fr/tupin/) and [Alasdair Newson](https://sites.google.com/site/alasdairnewson/))

## Recent news
* 02/2020: Five papers accepted at [CVPR'20](http://cvpr2020.thecvf.com/) (22% acceptance rate), inc. one oral, see [there](https://ptrckprz.github.io/vaipub).
* 01/2020: Spyros Gidaris, Andrei Bursuc and Karteek Alahari (Inria) to deliver a tutorial on Few-Shot, Self-Supervised, and Incremental Learning at CVPR'20. 
* 01/2020: Pedestrian monitoring demo at CES, Las Vegas.
* 12/2019: Medium post: [Is deep Reinforcement Learning really superhuman on Atari?](https://medium.com/@valeo.ai/is-deep-reinforcement-learning-really-superhuman-on-atari-2e34f8ae1eed)
* 12/2019: Codes for our ICCV'19 papers "Boosting few-shot visual learning with self-supervision" and "DADA: Depth-Aware Domain Adaptation in semantic segmentation" available on our github ([BF3S](https://github.com/valeoai/BF3S) and [DADA](https://github.com/valeoai/DADA)).
* 11/2019: Spyros Gidaris receives the Thesis Prize from [Université Paris Est](https://www.univ-paris-est.fr/evenements/evenement/9ca2fa43ca68cce620d7ba8dfc59f7d0/?tx_news_pi1%5Bnews%5D=773&tx_news_pi1%5Bcontroller%5D=News&tx_news_pi1%5Baction%5D=detail&tx_news_pi1%5Bday%5D=5&tx_news_pi1%5Bmonth%5D=11&tx_news_pi1%5Byear%5D=2019).
* 10/2019: Valeo.ai researchers present 5 papers at [ICCV](http://iccv2019.thecvf.com/) in Seoul, Korea, and Valeo participates to associated workshops on [Autonomous Driving](https://adworkshop.org/) and on [Autonomous Navigation in Unconstrained Environments](https://cvit.iiit.ac.in/autonue2019/program-s.html). 
* 10/2019: [PRAIRIE](https://prairie-institute.fr/) research institute is officially launched, with a nice day of talks and pannels (inc. one on future mobility, [program](https://prairie-institute.fr/wp-content/uploads/2019/10/PROGRAMME-VF-HD-.pdf) in French). Followed by PRAIRIE AI Summer School ([PAISS](https://project.inria.fr/paiss/)), where Patrick Pérez delivered a lecture ([slides](https://project.inria.fr/paiss/files/2019/10/2019_10_paiss_perez_noanim.pdf)).    
* 09/2019: Code of our NeurIPS'19 paper "Addressing failure prediction by learning model confidence" is available on [valeo.ai github](https://github.com/valeoai/ConfidNet). 
* 09/2019: Work of Marin Toromanoff *et al.* discussed by Andrew Ng in [The Batch](https://info.deeplearning.ai/the-batch-autonomous-nuclear-weapons-fighting-deepfakes-recognizing-chimps-automating-fast-food-2) (deeplearning.ai newsletter).
* 09/2019: Two papers accepted at [NeurIPS](https://nips.cc/) (21% acceptance rate), including one on new problem of zero shot semantic segmentation ("[Z3S](https://arxiv.org/abs/1906.00817)"). Matthieu Cord among the top contributors according to [conference stats](https://medium.com/@dcharrezt/neurips-2019-stats-c91346d31c8f).
* 07/2029: Medium post: [ADVENT: Adversarial entropy minimization for domain adaptation in semantic segmentation](https://medium.com/@valeo.ai/advent-adversarial-entropy-minimization-for-domain-adaptation-in-semantic-segmentation-dba21934430b).
* 07/2019: Three papers accepted at [ICCV19](http://iccv2019.thecvf.com/) (24% acceptance rate), including one oral (4.6% acceptance rate), see [there](https://ptrckprz.github.io/vaipub).
* 07/2019: Code of our CVPR'19 paper "AdvEnt: Adversarial Entropy Minimization for Domain Adaptation in Semantic Segmentation" is available on [valeo.ai github](https://github.com/valeoai/ADVENT). 
* 07/2019: Marin Toromanoff (PhD student with Mines ParisTech, Valeo DAR and Valeo.ai) ranks 1st on Track 2 of [Carla Challenge 2019](https://carlachallenge.org/results-challenge-2019/), and 2nd on Track 1.   
* 06/2019: Spyros Gidaris receives the [Best Thesis Prize from Ponts Foundation](https://www.fondationdesponts.fr/spyros-gidaris-laureat-ex-aequo-du-prix-de-la-meilleure-these-2019/). 
* 06/2019: Valeo.ai researchers present 8 papers (25% acceptance rate), including 4 orals (5.6% acceptance rate), at [CVPR](http://cvpr2019.thecvf.com/). Patrick Pérez delivers keynote on "Sustainable supervision with application to autonomous driving" at the Safe AI for Automated Driving ([SAIAD](https://sites.google.com/view/saiad-wscvpr19)) CVPR'19 workhsop. 
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



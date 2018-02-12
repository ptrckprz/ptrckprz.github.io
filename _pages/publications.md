---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



	1. N. Keriven, A. Bourrier, R. Gribonval, P. Pérez. Sketching for large scale learning of mixture models. Information & Inference, 2017
	2. G. Puy and P. Pérez. Structured sampling and fast reconstruction of smooth graph signals. Information & Inference, 2017
	3. A Newson, A Almansa, Y Gousseau, P Pérez. Non-local patch-based image inpainting. Image Processing On Line 7, 373-385, 2017 [online demo]
	4. T. Crivelli, P. Pérez, L. Oisel. Visual object trapping. Computer Vision and Image Understanding, 153:3-15, 2016
	5. J.M. Pérez-Rua, T. Crivelli, P. Pérez. Object-guided motion estimation. Computer Vision and Image Understanding, 153:88-99, 2016
	6. P. Garrido, M. Zolhöfer, C. Wu, D. Bradley, P. Pérez, Th. Beeler, Ch. Theobalt. Corrective 3D reconstruction of lips from monocular video. ACM Trans. on Gragphics, 35(6), 2016 [page, video]
	7. P. Garrido, M. Zollhoefer, D. Casas, L. Valgaerts, K. Varanasi, P. Perez, Ch. Theobalt. Reconstruction of personalized 3D face rigs from monocular video. ACM Trans. on Graphics, 35(3), 2016 [page, video]
	8. A. Djelouah, J.S. Franco, F. Le Clerc, P. Pérez and E. Boyer. Sparse multi-view consistency for object segmentation. IEEE Trans. Pattern Anal. Machine Intell. , 37(9):1890-190, 2015
	9. A. Bourrier, F. Perronnin, R. Gribonval, P.Pérez and H. Jégou. Nearest neighbor search for arbitrary kernels with explicit embeddings. J. Mathematical Imaging and Vision, 52(3):459-468, 2015.
	10. T. Crivelli, M. Fradet, P.-H. Conze, Ph. Robert, P. Pérez. Robust optical flow integration. IEEE Trans. Image Processing, 24(1):484-498, 2015
	11. A. Bourrier, M. Davis, T. Peleg, P. Pérez, R. Gribonval. Fundamental performance limits for ideal decoders in high-dimensional linear inverse problems. IEEE Trans. Information Theory, 60(12):7928-7946, 2014
	12. A. Newson, A. Almansa, M. Fradet, Y. Gousseau, P. Pérez. Video inpainting of complex scenes. SIAM Journal on Imaging Sciences, 7(4):1993-2019, 2014 [project]
	13. Ch. Avenel, E. Mémin, P. Pérez. Stochastic level set dynamics to track closed curves through image data. J. Mathematical Imaging and Vision, 49(2): 296-316, 2014
	14. Ch. Thériault, N. Thome, M. Cord and P. Pérez. Perceptual principles for video classification with Slow Feature Analysis. IEEE J. Selec. Topics Signal Proc., 8(3): 428 - 437, 2014
	15. A. Newson, A. Almansa, Y. Gousseau, P. Pérez. Robust automatic line scratch detection in films. IEEE Trans. Image Processing, 23(3): 1240 - 1254, 2014
	16. S. Chérigui, Ch. Guillemot, D. Thoreau, Ph. Guillotel, and P. Pérez. Correspondence map-aided neighbor embedding for image intra prediction. IEEE Trans. Image Processing, 23(2):1161-1174, 2013
	17. H. Jégou, F. Perronnin, M. Douze, J. Sánchez, P. Pérez, C. Schmid. Aggregating local image descriptors into compact codes. IEEE Trans. Pattern Anal. Machine Intell., 34(9), 2012 [code]
	18. F. Cao, Y. Gousseau, S. Masnou and P. Pérez. Geometrically guided exemplar-based inpainting. SIAM J. Imaging Sciences, 4(4): 1143–1179, 2011
	19. Ch. Kervrann , J. Boulanger , Th. Pécot, P. Pérez and J. Salamero. Multiscale neighborhood-wise decision fusion for redundancy detection in image pairs . SIAM J. Multiscale Modeling and Simulation, 9(4): 1829-1865, 2011
	20. I. Junejo, E. Dexter, I. Laptev, P. Pérez. View-independent action recognition from temporal self-similarities. IEEE Trans. Pattern Anal. Machine Intell. 33(1):172-185, 2011
	21. A. Criminisi, T. Sharp, C. Rother, P. Pérez. Geodesic image and video editing. ACM Trans. Graphics, 29(5), 2010 - Presented at Siggraph 2011
	22. A. Bugeau, P. Pérez. Detection and segmentation of moving objects in complex scenes. Computer Vision and Image Understanding, 13(4):459-476, 2009
	23. A. Bugeau, P. Pérez. Track and Cut: simultaneous tracking and segmentation of multiple objects with graph cuts. EURASIP Journal on Image and Video Processing, 2008(317278):1-14, 2008
	24. R. Venkatesh Babu, P. Pérez, P. Bouthemy. Robust tracking with motion estimation and local kernel-based color modeling. Image and Vision Computing, 25(8):1205-1216, 2007
	25. C. Hue, J.-P. Le Cadre, P. Pérez. Posterior Cramer-Rao bounds for multi-target tracking. IEEE Trans. on Aerospace and Electronic Systems, 42(1):37-49, 2006
	26. J. Vermaak, S. Godsill, P. Pérez. Monte Carlo filtering for multi-target tracking and data association. IEEE Trans. on Aerospace and Electronic Systems, 41(1):309-332, 2005
	27. P. Pérez, J. Vermaak, A. Blake. Data fusion for visual tracking with particles. Proc. IEEE, 92(3):495-513, 2004
	28. A. Criminisi, P. Pérez, K. Toyama. Region filling and object removal by exemplar-based inpainting. IEEE Trans. Image Processing, 13(9):1200-1212, 2004
	29. J.-N. Provost, C. Collet, P. Rostaing, P. Pérez, P. Bouthemy. Hierarchical Markovian segmentation of multispectral images for the reconstruction of water depth maps. Computer Vision and Image Understanding, 93(2):155-174, 2004
	30. P. Pérez, M. Gangnet, A. Blake. Poisson image editing. ACM Trans. Graphics (SIGGRAPH'03), 22(3):313-318, 2003
	31. T. Corpetti, E. Mémin, P. Pérez. Extraction of singular points from dense motion fields: an analytic approach. Journal of Mathematical Imaging and Vision, 19(3):175-198, 2003
	32. E. Mémin, P. Pérez. Hierarchical estimation and segmentation of dense motion fields. Int. Journal of Computer Vision, 46(2):129-155, 2002
	33. T. Corpetti, E. Mémin, P. Pérez. Dense estimation of fluid flows. IEEE Trans. Pattern Anal. Machine Intell., 24(3):365-380, 2002
	34. R. Fablet, P. Bouthemy, P. Pérez. Non-parametric motion characterization using causal probabilistic models for video indexing and retrieval. IEEE Trans. on Image Processing, 11(4):393-407, 2002
	35. C. Hue, J.-P. Le Cadre, P. Pérez. Sequential Monte Carlo methods for multiple target tracking and data fusion. IEEE Trans. on Signal Processing, 50(2):309-325, 2002
	36. C. Hue, J.-P. Le Cadre, P. Pérez. Tracking multiple objects with particle filtering. IEEE Trans. on Aerospace and Electronic Systems, 38(3):791-812, 2002
	37. P. Hellier, C. Barillot, E. Mémin, P. Pérez. Hierarchical estimation of a dense deformation field for 3D robust registration. IEEE Trans. Medical Imaging, 20(5):388-402, 2001
	38. L. Hubert-Moy, A. Cotonnec, L. Le Du, A. Chardin, P. Pérez. A comparison of parametric classification procedures of remotly sensed data applied on different landscape units. Remote Sensing of Environment, 75(2):174-187, 2001
	39. M. Mignotte, C. Collet, P. Pérez, P. Bouthemy. Hybrid genetic optimization and statistical model-based approach for the classification of shadow shapes in sonar imagery. IEEE Trans. Pattern Anal. Machine Intell., 22(2):129-141, 2000
	40. M. Mignotte, C. Collet, P. Pérez, P. Bouthemy. Markov random field and fuzzy logic modeling in sonar imagery: application to the classification of underwater floor. Computer Vision and Image Understanding, 79(1):4-24, 2000
	41. M. Mignotte, C. Collet, P. Pérez, P. Bouthemy. Sonar image segmentation using a hierarchical MRF model. IEEE Trans. Image Proc., 9(7):1216-1231, 2000
	42. J.-M. Laferté, P. Pérez, F. Heitz. Discrete Markov modeling and inference on the quad-tree. IEEE Trans. Image Proc., 9(3):390-404, 2000
	43. P. Pérez, A. Chardin, J.-M. Laferté. Noniterative manipulation of discrete energy-based models for image analysis. Pattern Recognition, 33(4):573-586, 2000
	44. M. Mignotte, C. Collet, P. Pérez, P. Bouthemy. Three-class Markovian segmentation of high resolution sonar images. Computer Vision and Image Understanding, 76(3):191-204, 1999
	45. C. Kervrann, F. Davoine, P. Pérez, H. Li, R. Forcheimer, C. Labit. Generalized likelihood ratio-based face detection and extraction of mouth features. Pattern Recognition Letters, 18(9):899-912, 1998
	46. P. Pérez. Markov random fields and images. CWI Quarterly, 11(4):413-437, 1998
	47. E. Mémin, P. Pérez. Dense optical flow estimation and object-based segmentation with robust techniques. IEEE Trans. on Image Processing, 7(5):703-719, 1998
	48. P. Pérez, F. Heitz. Restriction of a Markov random field on a graph and multiresolution statistical image modeling. IEEE Trans. on Information Theory, 42(1):180-190, 1996
	49. F. Heitz, P. Pérez, P. Bouthemy. Multiscale minimization of global energy functions in some visual recovery problems. CVGIP : Image Understanding, 59(1):125-134, 1994


---
title: 'SLAM-based dense surface reconstruction in monocular minimally invasive surgery and its application to augmented reality'
authors:
  - admin
  - Wen Tang
  - Nigel W John
  - Tao Ruan Wan
  - Jian Jun Zhang
date: '2018-01-01'
doi: ''
publishDate: '2018-01-01'
publication_types: ['journal']
publication: In *Computer Methods and Programs in Biomedicine*
volume: '158'
pages: '135–146'
publisher: 'Elsevier'
abstract: 'Background and objective: While Minimally Invasive Surgery (MIS) offers considerable benefits to patients, it also imposes big challenges on a surgeon’s performance due to well-known issues and restrictions associated with the field of view (FOV), hand-eye misalignment and disorientation, as well as the lack of stereoscopic depth perception in monocular endoscopy. Augmented Reality (AR) technology can help to overcome these limitations by augmenting the real scene with annotations, labels, tumour measurements or even a 3D reconstruction of anatomy structures at the target surgical locations. However, previous research attempts of using AR technology in monocular MIS surgical scenes have been mainly focused on the information overlay without addressing correct spatial calibrations, which could lead to incorrect localization of annotations and labels, and inaccurate depth cues and tumour measurements. In this paper, we present a novel intra-operative dense surface reconstruction framework that is capable of providing geometry information from only monocular MIS videos for geometry-aware AR applications such as site measurements and depth cues. We address a number of compelling issues in augmenting a scene for a monocular MIS environment, such as drifting and inaccurate planar mapping.

Methods: A state-of-the-art Simultaneous Localization And Mapping (SLAM) algorithm used in robotics has been extended to deal with monocular MIS surgical scenes for reliable endoscopic camera tracking and salient point mapping. A robust global 3D surface reconstruction framework has been developed for building a dense surface using only unorganized sparse point clouds extracted from the SLAM. The 3D surface reconstruction framework employs the Moving Least Squares (MLS) smoothing algorithm and the Poisson surface reconstruction framework for real time processing of the point clouds data set. Finally, the 3D geometric information of the surgical scene allows better understanding and accurate placement AR augmentations based on a robust 3D calibration.

Results: We demonstrate the clinical relevance of our proposed system through two examples: (a) measurement of the surface; (b) depth cues in monocular endoscopy. The performance and accuracy evaluations of the proposed framework consist of two steps. First, we have created a computer-generated endoscopy simulation video to quantify the accuracy of the camera tracking by comparing the results of the video camera tracking with the recorded ground-truth camera trajectories. The accuracy of the surface reconstruction is assessed by evaluating the Root Mean Square Distance (RMSD) of surface vertices of the reconstructed mesh with that of the ground truth 3D models. An error of 1.24 mm for the camera trajectories has been obtained and the RMSD for surface reconstruction is 2.54 mm, which compare favourably with previous approaches. Second, in vivo laparoscopic videos are used to examine the quality of accurate AR based annotation and measurement, and the creation of depth cues. These results show the potential promise of our geometry-aware AR technology to be used in MIS surgical scenes.

Conclusions: The results show that the new framework is robust and accurate in dealing with challenging situations such as the rapid endoscopy camera movements in monocular MIS scenes. Both camera tracking and surface reconstruction based on a sparse point cloud are effective and operated in real-time. This demonstrates the potential of our algorithm for accurate AR localization and depth augmentation with geometric cues and correct surface measurements in MIS with monocular endoscopes.'
url_pdf: 'https://eprints.bournemouth.ac.uk/30321/1/CMPB-final.pdf'
url_code: ''
url_dataset: ''
url_video: ''
image:
  caption: ''
  focal_point: ''
  preview_only: false
tags: [featured]
---

---
title: <font color="blue"> Pedestrian Feature Generation in Fish-eye Images via Adversary </font>
collection: publications
permalink: /publications/Pedestrian Feature Generation in Fish-eye Images via Adversary
venue: "International Conference on Robotics and Automation (ICRA 2018)"
date: 2018-1-12
excerpt: '<b>Yeqiang Qian</b>, Ming Yang*, Chunxiang Wang and Bing Wang. <i>International Conference on Robotics and Automation</i>. <b>ICRA 2018</b>.'
---


### Abstract
Pedestrian detection in fish-eye images is always an important problem in advanced driver assistance systems (ADAS). In conventional methods, pedestrian detectors will be trained using fish-eye images. But it is hard to collect and label enough fish-eye images manually. Therefore, a new strategy for training fish-eye pedestrian detectors using images from normal pedestrian datasets is proposed in this work. Concretely, Fish-eye Spatial Transformer Network (FSTN) is designed to generate pedestrian features in fish-eye images. FSTN aims to simulate distorted pedestrian features on the feature maps. Then the entire network is trained via adversary. FSTN is trained to generate examples which are difficult for pedestrian detectors to classify. So that the detectors are more robust to the deformation. FSTN can be embedded into state-of-the-art detectors easily. And the entire pedestrian detector, where the FSTN embedded, can be trained end to end via adversary. Moreover, experiments on ETH and KITTI pedestrian datasets show the slight accuracy improvement of pedestrian detection in fish-eye images using adversarial network compared with conventional methods.

[[PDF]](http://qianyeqiang.github.io/files/Pedestrian Feature Generation in Fish-eye Images via Adversary.pdf)

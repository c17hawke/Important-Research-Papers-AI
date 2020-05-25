# Object Detection

Folowing are the important papers related to Object Detection-

## Microsoft COCO: Common Objects in Context[^1]

??? Abstract
    We present a new dataset with the goal of advancing the state-of-the-art in object recognition by placing the question of
    object recognition in the context of the broader question of scene understanding. This is achieved by gathering images of complex
    everyday scenes containing common objects in their natural context. Objects are labeled using per-instance segmentations to aid in
    precise object localization. Our dataset contains photos of 91 objects types that would be easily recognizable by a 4 year old. With a
    total of 2.5 million labeled instances in 328k images, the creation of our dataset drew upon extensive crowd worker involvement via
    novel user interfaces for category detection, instance spotting and instance segmentation. We present a detailed statistical analysis of
    the dataset in comparison to PASCAL, ImageNet, and SUN. Finally, we provide baseline performance analysis for bounding box and
    segmentation detection results using a Deformable Parts Model.

* <a target="_blank" href="https://arxiv.org/abs/1405.0312">
Arxiv Site Link.
</a>
* <a target="_blank" href="https://arxiv.org/pdf/1405.0312.pdf">
Open PDF</a> in new tab.
* alternative <a target="_blank" href="https://github.com/c17hawke/Important-Research-Papers-AI/raw/master/researchPapers/ObjectDetection/1405.0312.pdf"> PDF source </a> from this repository.



---

## Rich feature hierarchies for accurate object detection and semantic segmentation Tech report (v5)[^2]

??? Abstract
    Object detection performance, as measured on the
    canonical PASCAL VOC dataset, has plateaued in the last
    few years. The best-performing methods are complex ensemble systems that typically combine multiple low-level
    image features with high-level context. In this paper, we
    propose a simple and scalable detection algorithm that improves mean average precision (mAP) by more than 30%
    relative to the previous best result on VOC 2012—achieving
    a mAP of 53.3%. Our approach combines two key insights:
    (1) one can apply high-capacity convolutional neural networks (CNNs) to bottom-up region proposals in order to
    localize and segment objects and (2) when labeled training
    data is scarce, supervised pre-training for an auxiliary task,
    followed by domain-specific fine-tuning, yields a significant
    performance boost. Since we combine region proposals
    with CNNs, we call our method R-CNN: Regions with CNN
    features. We also compare R-CNN to OverFeat, a recently
    proposed sliding-window detector based on a similar CNN
    architecture. We find that R-CNN outperforms OverFeat
    by a large margin on the 200-class ILSVRC2013 detection
    dataset. Source code for the complete system is available at
    [http://www.cs.berkeley.edu/˜rbg/rcnn](http://www.cs.berkeley.edu/˜rbg/rcnn).

* <a target="_blank" href="https://arxiv.org/abs/1311.2524">
Arxiv Site Link.
</a>
* <a target="_blank" href="https://arxiv.org/pdf/1311.2524.pdf">
Open PDF</a> in new tab.
* alternative <a target="_blank" href="https://github.com/c17hawke/Important-Research-Papers-AI/raw/master/researchPapers/ObjectDetection/1311.2524.pdf"> PDF source </a> from this repository.



[^1]: 
    Tsung-Yi Lin, Michael Maire, Serge Belongie, Lubomir Bourdev, Ross Girshick, James Hays, Pietro Perona, Deva Ramanan, C. Lawrence Zitnick, Piotr Dollár,
    "Microsoft COCO: Common Objects in Context"

[^2]:
    Ross Girshick, Jeff Donahue, Trevor Darrell, Jitendra Malik, UC Berkeley,
    "Rich feature hierarchies for accurate object detection and semantic segmentation 
    Tech report (v5)"

# Object Detection

Following are the important papers related to Object Detection-

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


---

## You Only Look Once: Unified, Real-Time Object Detectio[^3]

??? Abstract
    We present YOLO, a new approach to object detection.
    Prior work on object detection repurposes classifiers to perform detection. Instead, we frame object detection as a regression problem to spatially separated bounding boxes and
    associated class probabilities. A single neural network predicts bounding boxes and class probabilities directly from
    full images in one evaluation. Since the whole detection
    pipeline is a single network, it can be optimized end-to-end
    directly on detection performance.
    Our unified architecture is extremely fast. Our base
    YOLO model processes images in real-time at 45 frames
    per second. A smaller version of the network, Fast YOLO,
    processes an astounding 155 frames per second while
    still achieving double the mAP of other real-time detectors. Compared to state-of-the-art detection systems, YOLO
    makes more localization errors but is less likely to predict
    false positives on background. Finally, YOLO learns very
    general representations of objects. It outperforms other detection methods, including DPM and R-CNN, when generalizing from natural images to other domains like artwork.

* <a target="_blank" href="https://arxiv.org/abs/1311.2524">
Arxiv Site Link.
</a>
* <a target="_blank" href="https://arxiv.org/pdf/1506.02640.pdf">
Open PDF</a> in new tab.
* alternative <a target="_blank" href="https://github.com/c17hawke/Important-Research-Papers-AI/raw/master/researchPapers/ObjectDetection/1506.02640.pdf"> PDF source </a> from this repository.

[^1]: 
    Tsung-Yi Lin, Michael Maire, Serge Belongie, Lubomir Bourdev, Ross Girshick, James Hays, Pietro Perona, Deva Ramanan, C. Lawrence Zitnick, Piotr Dollár,
    "Microsoft COCO: Common Objects in Context"

[^2]:
    Ross Girshick, Jeff Donahue, Trevor Darrell, Jitendra Malik, UC Berkeley,
    "Rich feature hierarchies for accurate object detection and semantic segmentation 
    Tech report (v5)"

[^3]:
    Joseph Redmon, Santosh Divvala, Ross Girshick, Ali Farhadi,
    "You Only Look Once: Unified, Real-Time Object Detectio)"

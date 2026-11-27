<div align="center">

<h1> ☁️ On the Capabilities and Limitations of Zero-Shot Open-Vocabulary Cloud Segmentation</h1>

<h3></h3>

<div>
    <strong>Training-free OVSS benchmark of binary and multi-class cloud segmentation</strong>
</div>

<div>
    <a href='https://scholar.google.com/citations?user=R6rtktIAAAAJ&hl=en' target='_blank'>Jose Sosa</a>&emsp;
    <a> Thomas Gillet </a>&emsp;
    <a> Rim Sleimi </a>&emsp;
    <a> Albert Abello </a>&emsp;
</div>
<div>
    Hydrosat, Luxembourg &emsp;
</div>

<div>
    <h4 align="center">
        <a href="https://arxiv.org/abs/2611.32625" target='_blank'>[arXiv]</a> 
    </h4>
</div>

<img src="teaser.png" width="100%"/>
Overview of zero-shot open-vocabulary semantic segmentation (OVSS) capabilities for cloud detection in Earth Observation imagery. Left: Representative satellite images with overlaid cloud and cloud-shadow segmentation predictions, illustrating diverse cloud conditions and scene characteristics. Right: Comparison of 12 OVSS models across six cloud detection datasets using cumulative Intersection-over-Union (cIoU) for binary cloud segmentation. The results highlight variability in segmentation performance across models and datasets.

</div>

## Abstract
> *Recent advances in vision-language foundation models have enabled open-vocabulary semantic segmentation (OVSS) without task-specific training, offering new opportunities for Earth Observation (EO) applications. However, their capabilities for cloud detection remain insufficiently explored. In this work, we evaluate twelve OVSS approaches across six publicly available EO datasets in a zero-shot setting, i.e., without fine-tuning or adaptation to the target data. We investigate both binary cloud detection and multiclass segmentation, distinguishing between thick clouds, thin clouds, cloud shadows, and background. Our results show differences in performance across models and datasets, with SegEarth-OV3 achieving the highest binary cloud detection performance on four of the six datasets. While several approaches demonstrate promising performance in binary cloud detection, multiclass segmentation remains more challenging, particularly when distinguishing between fine-grained cloud categories. Furthermore, our controlled prompt sensitivity analysis reveals model-dependent responses to alternative textual descriptions, with appearance-oriented prompts benefiting certain approaches while degrading the performance of others. Overall, our findings demonstrate both the potential and current limitations of zero-shot OVSS for cloud detection, establishing a comparative benchmark for future research on generalisable cloud segmentation.*

## Code
Coming soon...

## Citation

```
@misc{sosa2026capabilitieslimitationszeroshotopenvocabulary,
      title={On the Capabilities and Limitations of Zero-Shot Open-Vocabulary Cloud Segmentation}, 
      author={Jose Sosa and Thomas Gillet and Rim Sleimi and Albert Abello},
      year={2026},
      eprint={2611.32625},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2611.32625}, 
}
```

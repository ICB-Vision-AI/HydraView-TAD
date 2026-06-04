# HydraView-TAD

<div align="center">
<img src='./static/images/overview.png' align="center" width="1280"/> <br>
Overview of our temporal action detection method with multiple viewpoints. For each input video viewpoint, an untrimmed sequence is encoded with a spatio-temporal encoder to generate features with improved view invariance. These features are then refined by our multi-view and multi-scale temporal encoder (HydraView) for localizing each action over time. <br><br>
</div>

## Introduction

This is the source code for the [website](https://icb-vision-ai.github.io/HydraView-TAD/) of the paper "Improving Viewpoint-Invariance and Temporal Consistency for Action Detection".

The paper is accepted to ICIP 2026.

**Abstract**:
> Viewpoint change invariance and action temporal consistency are critical aspects for the effective deployment of human action detection of untrimmed videos. Existing appearance-based video detection methods often struggle with limited viewpoint diversity during training, while motion-based detection approaches frequently fail to model fine-grained temporal relationships across consecutive motion windows. This paper introduces a novel two-stage action detection approach designed to improve both view-invariance and global temporal coherence properties. In the first stage, we extract motion features from augmented virtual viewpoints, solely used at training. Then, the second stage introduces a new view-invariant, multi-scale temporal encoder based on selective state-space sequence modelling to aggregate information across viewpoints and time scales. Experiments on PKU-MMD and BABEL benchmarks demonstrate that this approach significantly outperforms state-of-the-art methods in all considered splits.

## Code

The source code of the method described in the paper is [here](https://github.com/yanik-porto/HydraView-TAD.git).

## Citation
If you find this code useful for your research, please cite the paper:

```bibtex
@article{porto2026vitad,
  title={Improving Viewpoint-Invariance and Temporal Consistency for Action Detection},
  author={Porto, Martins and Chalumeau, Demonceaux},
  journal={ICIP},
  year={2026}
}
```

## Acknowledgements
This work was partially supported by grants from projects ANER MOVIS from ``Conseil Regional de Bourgogne-Franche-Comte'' and ANR MANYVIS (ANR-23-CE23-0003-01), to whom we are grateful.

**ICB:** [Laboratoire Interdisciplinaire Carnot de Bourgogne](https://icb.u-bourgogne.fr/)

# Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

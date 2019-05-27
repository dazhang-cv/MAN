# MAN: Moment Alignment Network for Natural Language Moment Retrieval via Iterative Graph Adjustment

TensorFlow implementation of the single shot activity detection model described in our [CVPR 2019](http://cvpr2019.thecvf.com/) paper [MAN: Moment Alignment Network for Natural Language Moment Retrieval via Iterative Graph Adjustment](https://arxiv.org/pdf/1812.00087.pdf).

In this work, we present a novel framework that unifies the candidate moment encoding and temporal structural reasoning in a single-shot feed-forward network. Our network naturally assigns candidate moment representations aligned with language semantics and explicitly model moment-wise temporal relations as a structured graph to jointly learn the best structure in an end-to-end manner. We achieved state-of-the-art performance on two public benchmarks Charades-STA and DiDeMo. For more details, please check the latest version of the paper.

## Network architecture

<p align="center"><img width="90%" src="man.png" />
  
## Prerequisites 
- Python 3.6.8
- TensorFlow 1.12.0

## Resources
We are still working on it and will release the codes after the CVPR conference.

## Reference
If you find our work useful, please use the following bibtex to cite our work:
```
@inproceedings{zhang2018man,
  title={MAN: Moment Alignment Network for Natural Language Moment Retrieval via Iterative Graph Adjustment},
  author={Zhang, Da and Dai, Xiyang and Wang, Xin and Wang, Yuan-Fang and Davis, Larry S},
  booktitle={The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2019}
}
```

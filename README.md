# Fastformer

## Notes from the authors

Pytorch/Keras implementation of Fastformer. The pytorch version is written in a huggingface transformers style. The jupyter notebooks contain the quickstart codes for text classification on AG's News (without pretrained word embeddings for simplicity), which can be directly run.  We noticed that in our experiments, NOT all tasks need FFNN, residual connection, layer normalization and even position embedding. For example, we find that in news recommendation, it is better to directly use Fastformer without layer normalization and position embedding. However, in Ad CVR prediction, both position embedding and layer normalization are needed.

Keras version: 2.2.4 (may not be compatible with higher versions)

TF version: from 1.12 to 1.15 (may be compatible with lower versions)

Pytorch version: 1.6.0 (may be compatible with higher/lower versions)

## Citation
```
@article{wu2021fastformer,
  title={Fastformer: Additive Attention Can Be All You Need},
  author={Wu, Chuhan and Wu, Fangzhao and Qi, Tao and Huang, Yongfeng},
  journal={arXiv preprint arXiv:2108.09084},
  year={2021}
}
```

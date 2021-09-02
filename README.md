# Fastformer

## Notes from the authors

This is a pytorch implementation of Fastformer. Our original codes are written in Keras with an old-version TF backend, and we highly appreciate the effort from other researchers who have implemented other versions of Fastformer via pytorch. However, we find some versions may not perform so well. Thus, to help other researchers try Fastformer in their research projects, we rewrite a pytorch version in a huggingface transformers style. We provide a jupyter notebook that contains the quickstart codes for text classification on AG's News (without pretrained word embeddings for simplicity), which can be directly run.  We noticed that in our experiments, NOT all tasks need FFNN, residual connection, layer normalization and even position embedding. For example, we find that in news recommendation, it is better to directly use Fastformer without layer normalization and position embedding. 

## Citation
```
@article{wu2021fastformer,
  title={Fastformer: Additive Attention Can Be All You Need},
  author={Wu, Chuhan and Wu, Fangzhao and Qi, Tao and Huang, Yongfeng},
  journal={arXiv preprint arXiv:2108.09084},
  year={2021}
}
```

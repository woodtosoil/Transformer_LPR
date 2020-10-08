# Transformer-based License Plate Recognition (Transformer-LPR)

PyTorch implementation of my new method for License Plate Recognition based on [Transformer](https://arxiv.org/abs/1706.03762).

I adapted the four-stage STR framework devised by [deep-text-recognition-benchmark](https://arxiv.org/abs/1904.01906), and replaced the `Pred.` stage with **Transformer**.



### Training
Please configure your `data_dir` in `config.py` file, then run:

```python
python tools/train.py
```


### References
> [deep-text-recognition-benchmark](https://arxiv.org/abs/1904.01906)  
> https://github.com/opconty/Transformer_STR


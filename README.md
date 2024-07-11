# softmax1

This repo accompanies the [Is Attention really off by one?](https://medium.com/@diagnosta/is-attention-really-off-by-one-d244df57558e) blog post, which has been inspired by the [Attention Is Off By One](https://www.evanmiller.org/attention-is-off-by-one.html) blog post.

In order to run the code, you first need to clone https://github.com/karpathy/build-nanogpt and then put the `train_gpt2_softmax1.py` script in there.

There's a couple of switches to manipulate in the script:
```
softmax1 = True        # this one is self-explanatory
save_outliers = True   # only set to True during inference to enable outlier counting
checkpoint_path = ''   # set to the checkpoint file name if you want to do inference; otherwise the script will train
```

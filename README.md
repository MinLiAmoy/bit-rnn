# Bit-RNN

Source code for paper: [Effective Quantization Methods for Recurrent Neural Networks](https://arxiv.org/abs/1611.10176).

The implementation of PTB language model is modified from examples in [tensorflow](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/models/rnn/ptb).

## Requirments

Currently tested and run on [TensorFlow](https://www.tensorflow.org) 0.9 and Python 3.5. Other version is supported but no gurrantee.
You may download the data from [http://www.fit.vutbr.cz/imikolov/rnnlm/simple-examples.tgz](http://www.fit.vutbr.cz/imikolov/rnnlm/simple-examples.tgz).

## Run
```
python train.py --config=config.gru --data_path=YOUR_DATA_PATH
```

Currently default is 2-bit weights and activations. You may edit the config file in config folder to change configuration.

## Support
Submit issue for problem relate to the code itself. Send email to the author for general question about the paper.

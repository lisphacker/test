<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.contrib.recurrent.functional_rnn" />
<meta itemprop="path" content="Stable" />
</div>

# tf.contrib.recurrent.functional_rnn

``` python
tf.contrib.recurrent.functional_rnn(
    cell,
    inputs,
    sequence_length=None,
    initial_state=None,
    dtype=None,
    time_major=False,
    scope=None,
    use_tpu=False,
    reverse=False
)
```

Same interface as `tf.compat.v1.nn.dynamic_rnn`.
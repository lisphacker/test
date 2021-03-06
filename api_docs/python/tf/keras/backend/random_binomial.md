<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.backend.random_binomial" />
<meta itemprop="path" content="Stable" />
</div>

# tf.keras.backend.random_binomial

``` python
tf.keras.backend.random_binomial(
    shape,
    p=0.0,
    dtype=None,
    seed=None
)
```

Returns a tensor with random binomial distribution of values.

The binomial distribution with parameters `n` and `p` is the probability
distribution of the number of successful Bernoulli process. Only supports
`n` = 1 for now.

#### Arguments:

* <b>`shape`</b>: A tuple of integers, the shape of tensor to create.
* <b>`p`</b>: A float, `0. <= p <= 1`, probability of binomial distribution.
* <b>`dtype`</b>: String, dtype of returned tensor.
* <b>`seed`</b>: Integer, random seed.


#### Returns:

A tensor.
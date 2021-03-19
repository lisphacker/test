<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.random.experimental.create_rng_state" />
<meta itemprop="path" content="Stable" />
</div>

# tf.random.experimental.create_rng_state

``` python
tf.random.experimental.create_rng_state(
    seed,
    algorithm
)
```

Creates a RNG state.

#### Args:

* <b>`seed`</b>: an integer or 1-D tensor.
* <b>`algorithm`</b>: an integer representing the RNG algorithm.


#### Returns:

a 1-D tensor whose size depends on the algorithm.
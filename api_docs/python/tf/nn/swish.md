<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.nn.swish" />
<meta itemprop="path" content="Stable" />
</div>

# tf.nn.swish

``` python
tf.nn.swish(features)
```

Computes the Swish activation function: `x * sigmoid(x)`.

Source: "Searching for Activation Functions" (Ramachandran et al. 2017)
https://arxiv.org/abs/1710.05941

#### Args:

* <b>`features`</b>: A `Tensor` representing preactivation values.
* <b>`name`</b>: A name for the operation (optional).


#### Returns:

The activation value.
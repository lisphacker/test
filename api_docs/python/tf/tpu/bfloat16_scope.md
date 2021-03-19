<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.tpu.bfloat16_scope" />
<meta itemprop="path" content="Stable" />
</div>

# tf.tpu.bfloat16_scope

### Aliases:

* `tf.contrib.tpu.bfloat16_scope`
* `tf.tpu.bfloat16_scope`

``` python
tf.tpu.bfloat16_scope()
```

Scope class for bfloat16 variables so that the model uses custom getter.

This enables variables to be read as bfloat16 type when using get_variable.
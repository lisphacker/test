<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.enable_v2_behavior" />
<meta itemprop="path" content="Stable" />
</div>

# tf.enable_v2_behavior

``` python
tf.enable_v2_behavior()
```

Enables TensorFlow 2.x behaviors.

This function can be called at the beginning of the program (before `Tensors`,
`Graphs` or other structures have been created, and before devices have been
initialized. It switches all global behaviors that are different between
TensorFlow 1.x and 2.x to behave as intended for 2.x.

This function is called in the main TensorFlow `__init__.py` file, user should
not need to call it, except during complex migrations.
<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.enable_tensor_equality" />
<meta itemprop="path" content="Stable" />
</div>

# tf.enable_tensor_equality

``` python
tf.enable_tensor_equality()
```

Compare Tensors with element-wise comparison and thus be unhashable.

Comparing tensors with element-wise allows comparisons such as
tf.Variable(1.0) == 1.0. Element-wise equality implies that tensors are
unhashable. Thus tensors can no longer be directly used in sets or as a key in
a dictionary.
<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tfdbg.has_inf_or_nan" />
<meta itemprop="path" content="Stable" />
</div>

# tfdbg.has_inf_or_nan

``` python
tfdbg.has_inf_or_nan(
    datum,
    tensor
)
```

A predicate for whether a tensor consists of any bad numerical values.

This predicate is common enough to merit definition in this module.
Bad numerical values include `nan`s and `inf`s.
The signature of this function follows the requirement of the method
`DebugDumpDir.find()`.

#### Args:

* <b>`datum`</b>: (`DebugTensorDatum`) Datum metadata.
* <b>`tensor`</b>: (`numpy.ndarray` or None) Value of the tensor. None represents
    an uninitialized tensor.


#### Returns:

(`bool`) True if and only if tensor consists of any nan or inf values.
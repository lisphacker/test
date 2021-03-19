<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.io.tf_record_iterator" />
<meta itemprop="path" content="Stable" />
</div>

# tf.io.tf_record_iterator

### Aliases:

* `tf.io.tf_record_iterator`
* `tf.python_io.tf_record_iterator`

``` python
tf.io.tf_record_iterator(
    path,
    options=None
)
```

An iterator that read the records from a TFRecords file. (deprecated)

Warning: THIS FUNCTION IS DEPRECATED. It will be removed in a future version.
Instructions for updating:
Use eager execution and: 
`tf.data.TFRecordDataset(path)`

#### Args:

* <b>`path`</b>: The path to the TFRecords file.
* <b>`options`</b>: (optional) A TFRecordOptions object.


#### Yields:

Strings.


#### Raises:

* <b>`IOError`</b>: If `path` cannot be opened for reading.
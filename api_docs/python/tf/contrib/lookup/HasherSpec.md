<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.contrib.lookup.HasherSpec" />
<meta itemprop="path" content="Stable" />
<meta itemprop="property" content="hasher"/>
<meta itemprop="property" content="key"/>
<meta itemprop="property" content="__new__"/>
</div>

# tf.contrib.lookup.HasherSpec

## Class `HasherSpec`



A structure for the spec of the hashing function to use for hash buckets.

`hasher` is the name of the hashing function to use (eg. "fasthash",
"stronghash").
`key` is optional and specify the key to use for the hash function if
supported, currently only used by a strong hash.

#### Fields:

* <b>`hasher`</b>: The hasher name to use.
* <b>`key`</b>: The key to be used by the hashing function, if required.

<h2 id="__new__"><code>__new__</code></h2>

``` python
__new__(
    _cls,
    hasher,
    key
)
```

Create new instance of HasherSpec(hasher, key)



## Properties

<h3 id="hasher"><code>hasher</code></h3>



<h3 id="key"><code>key</code></h3>






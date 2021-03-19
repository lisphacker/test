<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.contrib.eager.ExecutionCallback" />
<meta itemprop="path" content="Stable" />
<meta itemprop="property" content="IGNORE"/>
<meta itemprop="property" content="PRINT"/>
<meta itemprop="property" content="RAISE"/>
<meta itemprop="property" content="WARN"/>
<meta itemprop="property" content="__members__"/>
</div>

# tf.contrib.eager.ExecutionCallback

## Class `ExecutionCallback`



Valid callback actions.

These can be passed to `seterr` or `errstate` to create callbacks when
specific events occur (e.g. an operation produces `NaN`s).

IGNORE: take no action.
PRINT:  print a warning to `stdout`.
RAISE:  raise an error (e.g. `InfOrNanError`).
WARN:   print a warning using `tf.compat.v1.logging.warn`.

## Class Members

<h3 id="IGNORE"><code>IGNORE</code></h3>

<h3 id="PRINT"><code>PRINT</code></h3>

<h3 id="RAISE"><code>RAISE</code></h3>

<h3 id="WARN"><code>WARN</code></h3>

<h3 id="__members__"><code>__members__</code></h3>


<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.contrib.autograph" />
<meta itemprop="path" content="Stable" />
<meta itemprop="property" content="absolute_import"/>
<meta itemprop="property" content="division"/>
<meta itemprop="property" content="print_function"/>
</div>

# Module: tf.contrib.autograph

This is the legacy module for AutoGraph, kept for backward compatibility.

New users should instead use `tensorflow.python.autograph`.

## Classes

[`class AutoGraphError`](../../tf/contrib/autograph/AutoGraphError.md): Base class for all AutoGraph exceptions.

[`class ConversionOptions`](../../tf/contrib/autograph/ConversionOptions.md): Immutable container for global conversion flags.

[`class Feature`](../../tf/autograph/experimental/Feature.md): This enumeration represents optional conversion options.

[`class StackTraceMapper`](../../tf/contrib/autograph/StackTraceMapper.md): Remaps generated code to code it originated from.

## Functions

[`convert(...)`](../../tf/contrib/autograph/convert.md): Decorator that compiles a function to use TensorFlow ops.

[`converted_call(...)`](../../tf/contrib/autograph/converted_call.md): Compiles a function call inline.

[`do_not_convert(...)`](../../tf/autograph/experimental/do_not_convert.md): Decorator that suppresses the conversion of a function.

[`set_element_type(...)`](../../tf/contrib/autograph/set_element_type.md): Indicates that the entity is expected hold items of specified type/shape.

[`stack(...)`](../../tf/contrib/autograph/stack.md): Stacks the input, if it admits the notion of stacking.

[`to_code(...)`](../../tf/contrib/autograph/to_code.md): Similar to `to_graph`, but returns Python source code as a string.

[`to_graph(...)`](../../tf/contrib/autograph/to_graph.md): Converts a Python entity into a TensorFlow graph.

## Other Members

<h3 id="absolute_import"><code>absolute_import</code></h3>

<h3 id="division"><code>division</code></h3>

<h3 id="print_function"><code>print_function</code></h3>


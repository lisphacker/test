<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.backend.ctc_batch_cost" />
<meta itemprop="path" content="Stable" />
</div>

# tf.keras.backend.ctc_batch_cost

``` python
tf.keras.backend.ctc_batch_cost(
    y_true,
    y_pred,
    input_length,
    label_length
)
```

Runs CTC loss algorithm on each batch element.

#### Arguments:

* <b>`y_true`</b>: tensor `(samples, max_string_length)`
        containing the truth labels.
* <b>`y_pred`</b>: tensor `(samples, time_steps, num_categories)`
        containing the prediction, or output of the softmax.
* <b>`input_length`</b>: tensor `(samples, 1)` containing the sequence length for
        each batch item in `y_pred`.
* <b>`label_length`</b>: tensor `(samples, 1)` containing the sequence length for
        each batch item in `y_true`.


#### Returns:

Tensor with shape (samples,1) containing the
    CTC loss of each element.
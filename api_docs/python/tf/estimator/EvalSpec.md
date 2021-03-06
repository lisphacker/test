<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.estimator.EvalSpec" />
<meta itemprop="path" content="Stable" />
<meta itemprop="property" content="input_fn"/>
<meta itemprop="property" content="steps"/>
<meta itemprop="property" content="name"/>
<meta itemprop="property" content="hooks"/>
<meta itemprop="property" content="exporters"/>
<meta itemprop="property" content="start_delay_secs"/>
<meta itemprop="property" content="throttle_secs"/>
<meta itemprop="property" content="__new__"/>
</div>

# tf.estimator.EvalSpec

## Class `EvalSpec`



Configuration for the "eval" part for the `train_and_evaluate` call.

`EvalSpec` combines details of evaluation of the trained model as well as its
export. Evaluation consists of computing metrics to judge the performance of
the trained model.  Export writes out the trained model on to external
storage.

<h2 id="__new__"><code>__new__</code></h2>

``` python
@staticmethod
__new__(
    cls,
    input_fn,
    steps=100,
    name=None,
    hooks=None,
    exporters=None,
    start_delay_secs=120,
    throttle_secs=600
)
```

Creates a validated `EvalSpec` instance.

#### Args:

* <b>`input_fn`</b>: A function that constructs the input data for evaluation.
    See [Premade Estimators](
    https://tensorflow.org/guide/premade_estimators#create_input_functions)
    for more information. The function should construct and return one of
    the following:
      * A 'tf.data.Dataset' object: Outputs of `Dataset` object must be a
        tuple (features, labels) with same constraints as below.
      * A tuple (features, labels): Where features is a `Tensor` or a
        dictionary of string feature name to `Tensor` and labels is a
        `Tensor` or a dictionary of string label name to `Tensor`.

* <b>`steps`</b>: Int. Positive number of steps for which to evaluate model. If
    `None`, evaluates until `input_fn` raises an end-of-input exception.
    See `Estimator.evaluate` for details.
* <b>`name`</b>: String. Name of the evaluation if user needs to run multiple
    evaluations on different data sets. Metrics for different evaluations
    are saved in separate folders, and appear separately in tensorboard.
* <b>`hooks`</b>: Iterable of <a href="../../tf/train/SessionRunHook.md"><code>tf.train.SessionRunHook</code></a> objects to run
    during evaluation.
* <b>`exporters`</b>: Iterable of `Exporter`s, or a single one, or `None`.
    `exporters` will be invoked after each evaluation.
* <b>`start_delay_secs`</b>: Int. Start evaluating after waiting for this many
    seconds.
* <b>`throttle_secs`</b>: Int. Do not re-evaluate unless the last evaluation was
    started at least this many seconds ago. Of course, evaluation does not
    occur if no new checkpoints are available, hence, this is the minimum.


#### Returns:

A validated `EvalSpec` object.


#### Raises:

* <b>`ValueError`</b>: If any of the input arguments is invalid.
* <b>`TypeError`</b>: If any of the arguments is not of the expected type.



## Properties

<h3 id="input_fn"><code>input_fn</code></h3>



<h3 id="steps"><code>steps</code></h3>



<h3 id="name"><code>name</code></h3>



<h3 id="hooks"><code>hooks</code></h3>



<h3 id="exporters"><code>exporters</code></h3>



<h3 id="start_delay_secs"><code>start_delay_secs</code></h3>



<h3 id="throttle_secs"><code>throttle_secs</code></h3>






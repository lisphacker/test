<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.keras.callbacks" />
<meta itemprop="path" content="Stable" />
<meta itemprop="property" content="__all__"/>
</div>

# Module: tf.keras.callbacks

Callbacks: utilities called at certain points during model training.

## Classes

[`class BaseLogger`](../../tf/keras/callbacks/BaseLogger.md): Callback that accumulates epoch averages of metrics.

[`class CSVLogger`](../../tf/keras/callbacks/CSVLogger.md): Callback that streams epoch results to a csv file.

[`class Callback`](../../tf/keras/callbacks/Callback.md): Abstract base class used to build new callbacks.

[`class EarlyStopping`](../../tf/keras/callbacks/EarlyStopping.md): Stop training when a monitored quantity has stopped improving.

[`class History`](../../tf/keras/callbacks/History.md): Callback that records events into a `History` object.

[`class LambdaCallback`](../../tf/keras/callbacks/LambdaCallback.md): Callback for creating simple, custom callbacks on-the-fly.

[`class LearningRateScheduler`](../../tf/keras/callbacks/LearningRateScheduler.md): Learning rate scheduler.

[`class ModelCheckpoint`](../../tf/keras/callbacks/ModelCheckpoint.md): Save the model after every epoch.

[`class ProgbarLogger`](../../tf/keras/callbacks/ProgbarLogger.md): Callback that prints metrics to stdout.

[`class ReduceLROnPlateau`](../../tf/keras/callbacks/ReduceLROnPlateau.md): Reduce learning rate when a metric has stopped improving.

[`class RemoteMonitor`](../../tf/keras/callbacks/RemoteMonitor.md): Callback used to stream events to a server.

[`class TensorBoard`](../../tf/keras/callbacks/TensorBoard.md): Enable visualizations for TensorBoard.

[`class TerminateOnNaN`](../../tf/keras/callbacks/TerminateOnNaN.md): Callback that terminates training when a NaN loss is encountered.

## Other Members

<h3 id="__all__"><code>__all__</code></h3>


<div itemscope itemtype="http://developers.google.com/ReferenceObject">
<meta itemprop="name" content="tf.saved_model" />
<meta itemprop="path" content="Stable" />
<meta itemprop="property" content="ASSETS_DIRECTORY"/>
<meta itemprop="property" content="ASSETS_KEY"/>
<meta itemprop="property" content="CLASSIFY_INPUTS"/>
<meta itemprop="property" content="CLASSIFY_METHOD_NAME"/>
<meta itemprop="property" content="CLASSIFY_OUTPUT_CLASSES"/>
<meta itemprop="property" content="CLASSIFY_OUTPUT_SCORES"/>
<meta itemprop="property" content="DEFAULT_SERVING_SIGNATURE_DEF_KEY"/>
<meta itemprop="property" content="GPU"/>
<meta itemprop="property" content="LEGACY_INIT_OP_KEY"/>
<meta itemprop="property" content="MAIN_OP_KEY"/>
<meta itemprop="property" content="PREDICT_INPUTS"/>
<meta itemprop="property" content="PREDICT_METHOD_NAME"/>
<meta itemprop="property" content="PREDICT_OUTPUTS"/>
<meta itemprop="property" content="REGRESS_INPUTS"/>
<meta itemprop="property" content="REGRESS_METHOD_NAME"/>
<meta itemprop="property" content="REGRESS_OUTPUTS"/>
<meta itemprop="property" content="SAVED_MODEL_FILENAME_PB"/>
<meta itemprop="property" content="SAVED_MODEL_FILENAME_PBTXT"/>
<meta itemprop="property" content="SAVED_MODEL_SCHEMA_VERSION"/>
<meta itemprop="property" content="SERVING"/>
<meta itemprop="property" content="TPU"/>
<meta itemprop="property" content="TRAINING"/>
<meta itemprop="property" content="VARIABLES_DIRECTORY"/>
<meta itemprop="property" content="VARIABLES_FILENAME"/>
<meta itemprop="property" content="__all__"/>
</div>

# Module: tf.saved_model

Public API for tf.saved_model namespace.

## Modules

[`builder`](../tf/saved_model/builder.md) module: SavedModel builder.

[`constants`](../tf/saved_model/constants.md) module: Constants for SavedModel save and restore operations.

[`experimental`](../tf/saved_model/experimental.md) module: Public API for tf.saved_model.experimental namespace.

[`loader`](../tf/saved_model/loader.md) module: Loader functionality for SavedModel with hermetic, language-neutral exports.

[`main_op`](../tf/saved_model/main_op.md) module: SavedModel main op.

[`signature_constants`](../tf/saved_model/signature_constants.md) module: Signature constants for SavedModel save and restore operations.

[`signature_def_utils`](../tf/saved_model/signature_def_utils.md) module: SignatureDef utility functions.

[`tag_constants`](../tf/saved_model/tag_constants.md) module: Common tags used for graphs in SavedModel.

[`utils`](../tf/saved_model/utils.md) module: SavedModel utility functions.

## Classes

[`class Builder`](../tf/saved_model/Builder.md): Builds the `SavedModel` protocol buffer and saves variables and assets.

## Functions

[`build_signature_def(...)`](../tf/saved_model/build_signature_def.md): Utility function to build a SignatureDef protocol buffer.

[`build_tensor_info(...)`](../tf/saved_model/build_tensor_info.md): Utility function to build TensorInfo proto from a Tensor. (deprecated)

[`classification_signature_def(...)`](../tf/saved_model/classification_signature_def.md): Creates classification signature from given examples and predictions.

[`contains_saved_model(...)`](../tf/saved_model/contains_saved_model.md): Checks whether the provided export directory could contain a SavedModel.

[`get_tensor_from_tensor_info(...)`](../tf/saved_model/get_tensor_from_tensor_info.md): Returns the Tensor or CompositeTensor described by a TensorInfo proto. (deprecated)

[`is_valid_signature(...)`](../tf/saved_model/is_valid_signature.md): Determine whether a SignatureDef can be served by TensorFlow Serving.

[`load(...)`](../tf/saved_model/load.md): Loads the model from a SavedModel as specified by tags. (deprecated)

[`load_v2(...)`](../tf/saved_model/load_v2.md): Load a SavedModel from `export_dir`.

[`main_op_with_restore(...)`](../tf/saved_model/main_op_with_restore.md): Returns a main op to init variables, tables and restore the graph. (deprecated)

[`maybe_saved_model_directory(...)`](../tf/saved_model/contains_saved_model.md): Checks whether the provided export directory could contain a SavedModel.

[`predict_signature_def(...)`](../tf/saved_model/predict_signature_def.md): Creates prediction signature from given inputs and outputs.

[`regression_signature_def(...)`](../tf/saved_model/regression_signature_def.md): Creates regression signature from given examples and predictions.

[`save(...)`](../tf/saved_model/save.md): Exports the Trackable object `obj` to [SavedModel format](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/python/saved_model/README.md).

[`simple_save(...)`](../tf/saved_model/simple_save.md): Convenience function to build a SavedModel suitable for serving. (deprecated)

## Other Members

<h3 id="ASSETS_DIRECTORY"><code>ASSETS_DIRECTORY</code></h3>

<h3 id="ASSETS_KEY"><code>ASSETS_KEY</code></h3>

<h3 id="CLASSIFY_INPUTS"><code>CLASSIFY_INPUTS</code></h3>

<h3 id="CLASSIFY_METHOD_NAME"><code>CLASSIFY_METHOD_NAME</code></h3>

<h3 id="CLASSIFY_OUTPUT_CLASSES"><code>CLASSIFY_OUTPUT_CLASSES</code></h3>

<h3 id="CLASSIFY_OUTPUT_SCORES"><code>CLASSIFY_OUTPUT_SCORES</code></h3>

<h3 id="DEFAULT_SERVING_SIGNATURE_DEF_KEY"><code>DEFAULT_SERVING_SIGNATURE_DEF_KEY</code></h3>

<h3 id="GPU"><code>GPU</code></h3>

<h3 id="LEGACY_INIT_OP_KEY"><code>LEGACY_INIT_OP_KEY</code></h3>

<h3 id="MAIN_OP_KEY"><code>MAIN_OP_KEY</code></h3>

<h3 id="PREDICT_INPUTS"><code>PREDICT_INPUTS</code></h3>

<h3 id="PREDICT_METHOD_NAME"><code>PREDICT_METHOD_NAME</code></h3>

<h3 id="PREDICT_OUTPUTS"><code>PREDICT_OUTPUTS</code></h3>

<h3 id="REGRESS_INPUTS"><code>REGRESS_INPUTS</code></h3>

<h3 id="REGRESS_METHOD_NAME"><code>REGRESS_METHOD_NAME</code></h3>

<h3 id="REGRESS_OUTPUTS"><code>REGRESS_OUTPUTS</code></h3>

<h3 id="SAVED_MODEL_FILENAME_PB"><code>SAVED_MODEL_FILENAME_PB</code></h3>

<h3 id="SAVED_MODEL_FILENAME_PBTXT"><code>SAVED_MODEL_FILENAME_PBTXT</code></h3>

<h3 id="SAVED_MODEL_SCHEMA_VERSION"><code>SAVED_MODEL_SCHEMA_VERSION</code></h3>

<h3 id="SERVING"><code>SERVING</code></h3>

<h3 id="TPU"><code>TPU</code></h3>

<h3 id="TRAINING"><code>TRAINING</code></h3>

<h3 id="VARIABLES_DIRECTORY"><code>VARIABLES_DIRECTORY</code></h3>

<h3 id="VARIABLES_FILENAME"><code>VARIABLES_FILENAME</code></h3>

<h3 id="__all__"><code>__all__</code></h3>




page_type: reference


<!-- DO NOT EDIT! Automatically generated file. -->


# Module: tf.contrib.estimator



Defined in [`tensorflow/contrib/estimator/__init__.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.6/tensorflow/contrib/estimator/__init__.py).

Experimental utilities re:tf.estimator.*.

## Classes

[`class DNNEstimator`](../../tf/contrib/estimator/DNNEstimator): An estimator for TensorFlow DNN models with user-specified head.

[`class DNNLinearCombinedEstimator`](../../tf/contrib/estimator/DNNLinearCombinedEstimator): An estimator for TensorFlow Linear and DNN joined models with custom head.

[`class LinearEstimator`](../../tf/contrib/estimator/LinearEstimator): An estimator for TensorFlow linear models with user-specified head.

[`class TowerOptimizer`](../../tf/contrib/estimator/TowerOptimizer): Gathers gradients from all towers and reduces them in the last one.

## Functions

[`add_metrics(...)`](../../tf/contrib/estimator/add_metrics): Creates a new ${tf.estimator.Estimator} which has given metrics.

[`binary_classification_head(...)`](../../tf/contrib/estimator/binary_classification_head): Creates a `_Head` for single label binary classification.

[`call_logit_fn(...)`](../../tf/contrib/estimator/call_logit_fn): Calls logit_fn.

[`clip_gradients_by_norm(...)`](../../tf/contrib/estimator/clip_gradients_by_norm): Returns an optimizer which clips gradients before applying them.

[`dnn_logit_fn_builder(...)`](../../tf/contrib/estimator/dnn_logit_fn_builder): Function builder for a dnn logit_fn.

[`forward_features(...)`](../../tf/contrib/estimator/forward_features): Forward features to predictions dictionary.

[`linear_logit_fn_builder(...)`](../../tf/contrib/estimator/linear_logit_fn_builder): Function builder for a linear logit_fn.

[`multi_class_head(...)`](../../tf/contrib/estimator/multi_class_head): Creates a `_Head` for multi class classification.

[`multi_head(...)`](../../tf/contrib/estimator/multi_head): Creates a `_Head` for multi-objective learning.

[`multi_label_head(...)`](../../tf/contrib/estimator/multi_label_head): Creates a `_Head` for multi-label classification.

[`regression_head(...)`](../../tf/contrib/estimator/regression_head): Creates a `_Head` for regression using the `mean_squared_error` loss.

[`replicate_model_fn(...)`](../../tf/contrib/estimator/replicate_model_fn): Replicate `Estimator.model_fn` over GPUs.

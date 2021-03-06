<div itemscope itemtype="http://schema.org/Dataset">
  <div itemscope itemprop="includedInDataCatalog" itemtype="http://schema.org/DataCatalog">
    <meta itemprop="name" content="TensorFlow Datasets" />
  </div>
  <meta itemprop="name" content="imagenette" />
  <meta itemprop="description" content="Imagenette is a subset of 10 easily classified classes from the Imagenet&#10;dataset. It was originally prepared by Jeremy Howard of FastAI. The objective&#10;behind putting together a small version of the Imagenet dataset was mainly&#10;because running new ideas/algorithms/experiments on the whole Imagenet take a&#10;lot of time.&#10;&#10;This version of the dataset allows researchers/practitioners to quickly try out&#10;ideas and share with others. The dataset comes in three variants:&#10;&#10;  * Full size&#10;  * 320 px&#10;  * 160 px&#10;&#10;Note: The v2 config correspond to the new 70/30 train/valid split (released&#10;in Dec 6 2019).&#10;&#10;To use this dataset:&#10;&#10;```python&#10;import tensorflow_datasets as tfds&#10;&#10;ds = tfds.load(&#x27;imagenette&#x27;, split=&#x27;train&#x27;)&#10;for ex in ds.take(4):&#10;  print(ex)&#10;```&#10;&#10;See [the guide](https://www.tensorflow.org/datasets/overview) for more&#10;informations on [tensorflow_datasets](https://www.tensorflow.org/datasets).&#10;&#10;" />
  <meta itemprop="url" content="https://www.tensorflow.org/datasets/catalog/imagenette" />
  <meta itemprop="sameAs" content="https://github.com/fastai/imagenette" />
  <meta itemprop="citation" content="@misc{imagenette,&#10;  author    = &quot;Jeremy Howard&quot;,&#10;  title     = &quot;imagenette&quot;,&#10;  url       = &quot;https://github.com/fastai/imagenette/&quot;&#10;}" />
</div>

# `imagenette`

Note: This dataset has been updated since the last stable release. The new
versions and config marked with
<span class="material-icons" title="Available only in the tfds-nightly package">nights_stay</span>
are only available in the `tfds-nightly` package.

*   **Description**:

Imagenette is a subset of 10 easily classified classes from the Imagenet
dataset. It was originally prepared by Jeremy Howard of FastAI. The objective
behind putting together a small version of the Imagenet dataset was mainly
because running new ideas/algorithms/experiments on the whole Imagenet take a
lot of time.

This version of the dataset allows researchers/practitioners to quickly try out
ideas and share with others. The dataset comes in three variants:

*   Full size
*   320 px
*   160 px

Note: The v2 config correspond to the new 70/30 train/valid split (released in
Dec 6 2019).

*   **Homepage**:
    [https://github.com/fastai/imagenette](https://github.com/fastai/imagenette)

*   **Source code**:
    [`tfds.image_classification.Imagenette`](https://github.com/tensorflow/datasets/tree/master/tensorflow_datasets/image_classification/imagenette.py)

*   **Versions**:

    *   **`1.0.0`** (default)
        <span class="material-icons" title="Available only in the tfds-nightly package">nights_stay</span>:
        No release notes.

*   **Download size**: `Unknown size`

*   **Dataset size**: `Unknown size`

*   **Auto-cached**
    ([documentation](https://www.tensorflow.org/datasets/performances#auto-caching)):
    Unknown

*   **Splits**:

Split | Examples
:---- | -------:

*   **Features**:

```python
FeaturesDict({
    'image': Image(shape=(None, None, 3), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=10),
})
```

*   **Supervised keys** (See
    [`as_supervised` doc](https://www.tensorflow.org/datasets/api_docs/python/tfds/load#args)):
    `('image', 'label')`

*   **Citation**:

```
@misc{imagenette,
  author    = "Jeremy Howard",
  title     = "imagenette",
  url       = "https://github.com/fastai/imagenette/"
}
```

*   **Figure**
    ([tfds.show_examples](https://www.tensorflow.org/datasets/api_docs/python/tfds/visualization/show_examples)):
    Not supported.

*   **Examples**
    ([tfds.as_dataframe](https://www.tensorflow.org/datasets/api_docs/python/tfds/as_dataframe)):
    Missing.

## imagenette/full-size-v2 (default config)

*   **Config description**: full-size variant.

## imagenette/320px-v2

*   **Config description**: 320px variant.

## imagenette/160px-v2

*   **Config description**: 160px variant.

## imagenette/full-size

*   **Config description**: full-size variant.

## imagenette/320px

*   **Config description**: 320px variant.

## imagenette/160px

*   **Config description**: 160px variant.

# digit-recognizer-for-pros

[Digit Recognizer](https://www.kaggle.com/c/digit-recognizer) is a `Kaggle` competition where using the dataset you have to create a `classifier` that can classify handwritten images into digits.

Here `no pre-trained CNN or predefined architecture` is used, this is a `custom` CNN architecture.

**While doing this we'll go through**

- Data augmentation using `ImageDataGenerator`
- Building `custom` CNN architecture
- Visualizing CNN (`filters` and `feature maps`)

## Table of contents

- [Getting started](#getting-started)
- [Kaggle Competition Results](#kaggle-competition-results)
- [Models performance and visualizations](#models-performance-and-visualizations)
  - [Visualizing Filters](#visualizing-filters)
  - [Visualizing Feature Maps](#visualizing-feature-maps)
- [License](#license)

## Getting started

The [notebook](https://www.kaggle.com/akashsdas/digit-recognizer-for-pros) is available on Kaggle to work in the same environment where this notebook was created i.e. use the same version packages used, etc...

If you are interested in the `model` the you can find that in the `Output` section of the [notebook](https://www.kaggle.com/akashsdas/digit-recognizer-for-pros).

## Kaggle Competition Results

**The best model has an accuracy of 99.5%**

![](./docs/imgs/img1.png)

![](./docs/imgs/img2.png)

![](./docs/imgs/img3.png)

## Models performance and visualizations

**Count plot for labels**

![](./docs/imgs/count-plot.png)

**The model is trained for 50epochs and below is the last epoch's results**

![](./docs/imgs/last-epoch.png)

**Learning curves**

![](./docs/imgs/learning-curve.png)
![](./docs/imgs/loss-curve.png)

**Confidence matrix**

![](./docs/imgs/confusion-matrix.png)

**Some predictions on the validation set**

![](./docs/imgs/output-results.png)

### Visualizing filters

**Image of the 96th filter of the 1st conv layer**

![](./docs/imgs/top-conv-layer-filter.png)

**Images for only first 20 filters in the 1nd conv layer**

![](./docs/imgs/filter1.png)

**Images for only first 10 filters in the 2nd conv layer**

![](./docs/imgs/filter2.png)

### Visualizing feature maps

**We'll visualize feature maps for the digit 7**

![](./docs/imgs/feature-maps-1.png)

**Feature maps by 1st conv layer**

![](./docs/imgs/feature-maps-2.png)

**Feature maps by 2nd conv layer**

![](./docs/imgs/feature-maps-3.png)

## License

[APACHE LICENSE, VERSION 2.0](./LICENSE)

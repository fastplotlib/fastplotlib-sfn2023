# fastplotlib-sfn2023

Materials for the [`fastplotlib`](https://github.com/fastplotlib/fastplotlib/) talk at Society for Neuroscience (SFN) 2023. This repo includes installation instructions and the demo notebooks covered in our talk. 

For more info on `fastplotlib` see the repo: https://github.com/fastplotlib/fastplotlib/

The demos cover the following topics:
1. Simple introduction to `fastplotlib` - `Images`, `ImageWidget`, and `Lines`
   - plotting simple images, feature changes, image updates, fancy indexing of features
2. Neuroscience using `fastplotlib` 
   - building a complex plot to explore behavioral and calcium imaging data
   - integration of `fastplotlib` with other Python neuroscience tools (i.e. `mesmerize_core`, `CaImAn`, `pynapple`)
  
# Installation instructions

See the `fastplotlib` repo for [installation](https://github.com/fastplotlib/fastplotlib#installation). 

### Install using pip
```
```

# General `fastplotlib` API
## 1. Graphics - objects that are drawn
- `Image`, `Line`, `Scatter`, `Heatmap`
- Collections - `LineCollection`, `LineStack` (ex: neural timeseries data)
- Interactions
## 2. Layouts
- `Plot` - a single plot area
- `GridPlot` - a grid of `Subplots`
## 3. Widgets - high level widgets to make repetitive UIs easier
- `ImageWidget`- n-dimensional widget for Image data
- Sliders, support window functions, `GridPlot`, etc.

# Docs
For a more in-depth look at our API, please visit our [docs](https://fastplotlib.readthedocs.io/en/).

# Contributions
`fastplotlib` is a relatively new library, and we are always looking for feedback or help! Please see the [contributing guide](https://github.com/kushalkolar/fastplotlib/blob/master/CONTRIBUTING.md). 

You can also look at our [Roadmap for 2023](https://github.com/kushalkolar/fastplotlib/issues/55) and [Issues](https://github.com/kushalkolar/fastplotlib/issues) for more ideas on how to contribute.



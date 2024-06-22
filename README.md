## ML Model Visualization

This method provides the clearest visualization of neural network layers, displaying them in their initialization order. Whilst it offers a simplified, linear view of the model's architecture, it may not accurately reflect the true operational flow. Neural networks often involve complex layer interactions, such as skip connections or attention mechanisms, which this visualization doesn't capture.

The tool prioritizes clarity over complete accuracy, making it useful for quick overviews, debugging, and explaining architectures to non-experts. However, its limitations must be acknowledged. For an in-depth understanding of model behaviour, you must complement this visualization with detailed analyses of actual data flow and layer interactions during forward and backward passes.

[This visualization](./ml_model_visualization.ipynb) serves as a valuable starting point for understanding model architecture, but shouldn't be mistaken for a complete representation of the model's inner workings.

### Visualizing XsoraS/SmallLM Model

The [visualization of the XsoraS/SmallLM model architecture](./ml_model_visualization_example.ipynb) leverages NetworkX, a powerful Python library for complex networks, to create a comprehensive graph representation of the model's structure. By recursively traversing the model's modules and submodules, I constructed a directed graph (DiGraph) where each node represents a layer or component of the model, and edges illustrate the connections between these components. This graph-based approach allows for a clear depiction of the model's hierarchical structure, showcasing the intricate relationships between various layers in the transformer architecture. The resulting visualization, rendered using matplotlib, provides an intuitive and informative overview of the [XsoraS/SmallLM model](https://huggingface.co/XsoraS/SmallLM), offering insights into its complexity and design that are valuable for understanding and analysing deep learning models.

### License

This project is licensed under the [Apache License 2.0](./LICENSE).

### Citation

```tex
@misc{afommv2024,
  author       = {Oketunji, A.F.},
  title        = {ML Model Visualization},
  year         = 2024,
  version      = {0.0.1},
  publisher    = {Zenodo},
  doi          = {},
  url          = {}
}
```

### Copyright

(c) 2024 [Finbarrs Oketunji](https://finbarrs.eu). All Rights Reserved.

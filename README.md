# Tutorial on using Transfer Learning in histopathology
The aim of this tutorial is to classify patches of colorectal tissues in 9 different classes [1] using transfer learning.

We will run 3 experiments in parallel in order to better understand the topic:
- Using transfer learning & retraining all layers
- Using transfer learning & freezing half of the layers
- Training from scratch (= no transfer learning)

[1] J. N. Kather et al. (2018). 100,000 histological images of human colorectal cancer and healthy tissue (Version v0.1) [Data set]. Zenodo. http://doi.org/10.5281/zenodo.1214456

## Tutorial
The tutorial is implemented in tensorflow 2.0 in a jupyter notebook: `transfer_learning_classification.ipynb`

## Prerequisites
- [Jupyter notebook](https://jupyter.org/install)
- [Python](https://www.python.org/downloads/) (tested with: 3.7)
- [Tensorflow](https://www.tensorflow.org/install) (tested with: 2.0)

## Author
My name is Marie Duc, I am Research Scientist at the Werner Siemens Imaging Center in Tübingen Germany. I am working on applying machine learning to medical imaging.

By any questions, requests, or anything else, please contact me!! :)

## License
This project is [MIT](https://github.com/maduc7/tutorial_transfer_learning_tf/LICENSE) licensed.

## Acknowledgements
This project has received funding from the European Union’s Horizon 2020 research and innovation programme under the Marie Skłodowska-Curie grant agreement No 764458.

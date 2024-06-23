# Gaussian Mixture Model Estimation with EM Algorithm

This repository contains a Python implementation of the Gaussian Mixture Model (GMM) parameter estimation using the Expectation-Maximization (EM) algorithm. It includes detailed visualizations in both 2D and 3D, as well as animated transitions between iterations to help in understanding how GMM parameters evolve over time.

![Demo Animation](https://github.com/AliAssareh/GaussianMixtureModels/blob/main/2.5d_gmm.gif?raw=true)


## Description

Gaussian Mixture Models are a probabilistic model for representing normally distributed subpopulations within an overall population. The model uses the EM algorithm to efficiently find the maximum likelihood estimate of parameters in cases where direct computation is not feasible.

## Features

- **Parameter Estimation**: Estimate means, covariances, and mixing coefficients of a Gaussian mixture model.
- **Multiple Visualizations**:
  - **2D Visualization**: Display the data points and their Gaussian distributions.
  - **Contour Plot (2.5D Visualization)**: Visualize the probability density functions of the distributions.
  - **3D Visualization**: Explore the model in three dimensions to understand the depth of the data distribution.
- **Animation**: Animated progression of the EM algorithm showing gradual convergence of the model parameters.
- **Customization**: Easy to customize the initial parameters, number of components, and visualization styles.

## Use Cases

- **Clustering**: GMMs can be used for clustering data where the clusters are not necessarily spherical.
- **Density Estimation**: Useful in estimating the density distribution of data, especially for multimodal data.
- **Anomaly Detection**: Identifying unusual data points by evaluating their likelihood under the estimated model.
- **Image Segmentation**: Applying GMMs for segmenting different regions in images based on color and intensity distributions.

## Dependencies

- Python 3.x
- Matplotlib
- NumPy
- SciPy

### Contributing
Contributions to enhance the functionality or visualization of the Gaussian Mixture Model estimation are welcome. Please follow these steps to contribute:

1. Fork the project.
2. Create a feature branch (git checkout -b feature/amazing-feature).
3. Commit your changes (git commit -am 'Add some amazing feature').
4. Push to the branch (git push origin feature/amazing-feature).
5. Open a Pull Request.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Ali Asareh Nejad - assareh73@gmail.com

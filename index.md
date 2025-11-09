# Gahn Wuwong       
[gwuwong@ucsd.edu](mailto:gwuwong@ucsd.edu)

---

# Wildfire and Property Intelligence Modeling with Cotality     
Ilyes Meftah, Lawrence Vulis, and Peter Nagy.

**What is the most interesting topic covered in your domain this quarter?**

The most interesting topic this quarter was learning how to combine real geospatial datasets for wildfire analysis. I especially enjoyed clipping climate data to San Diego County, rasterizing the 2003 Cedar Fire perimeter, and using OpenStreetMap to count buildings inside the burn area. It was exciting to see how different datasets connect to reveal real impacts, which is very useful for exploratory data analysis and for choosing appropriate models and implementation approaches in future machine learning work.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

For my Quarter 2 project, I’d like to explore using deep learning models, such as neural networks and LSTMs, for climate and wildfire prediction. Instead of relying only on traditional machine learning approaches, I want to experiment with architectures that can capture both spatial and temporal dependencies in the data. For example, convolutional models could process 2D inputs of longitude and latitude along with multiple climate and vegetation features, forming 3D tensors where each grid cell contains values like temperature, precipitation, and vegetation index. This setup could help the model learn spatial patterns and temporal trends that drive wildfire occurrence, potentially improving predictive accuracy across different regions and time periods.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

A potential change I’d make is to have a more flexible framework that allows exploring different models and datasets beyond traditional machine learning approaches. In a more open-ended setting, I’d like to test deep learning architectures that can capture spatial and temporal patterns, and incorporate richer datasets with features like wind speed, soil moisture, and human activity. This flexibility would make the analysis more exploratory and realistic, allowing for deeper insights into complex wildfire dynamics.

**What other techniques would you be interested in using in your project?**

I’d like to explore a range of deep learning techniques for wildfire prediction that can handle complex spatial and temporal patterns in environmental data. This includes experimenting with transformers, visual transformers, and other attention-based architectures that can learn relationships across both space and time. I’d also like to test CNNs for analyzing gridded climate and vegetation features, as well as recurrent models like RNNs and LSTMs for capturing temporal dependencies in variables such as temperature, precipitation, and vegetation index. Combining these ideas into spatiotemporal hybrid models, such as transformer-based sequence models or attention-augmented CNNs, could make it possible to take in 3D climate tensors (longitude × latitude × features) and predict dynamic burn probabilities more accurately.
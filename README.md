# CS274Project
Bilateral Trade Flow Prediction Through GraphSage and MLP

With international trade continuing to grow to higher levels, predicting trade amounts between nations becomes more important for planning.
The gravity model has been used by economists to achieve this goal, but does not take into consideration many important factors. This paper
proposes two solutions to improve upon past works to forecast international trade quantities, and potentially other datasets which follow a
gravity-like pattern such as migration and traffic. First, a simple Multi-Layer Perceptron (MLP) is proposed which achieves its best results
on feature rich data. Second, a model which uses GraphSAGE alongside MLP for prediction, and currently performs best on a smaller dataset of 
simple features, but can better apply to dynamic data than previous experiments using other Graph Neural Networks (GNNs) such as Graph 
Convolutional Networks (GCNs).

This project was completed by Wilson Strasilla for the fulfillment of CS274 with Dr. Teng Moh at San Jose State University

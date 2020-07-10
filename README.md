# Shopee-Object-Detection
Experimental Object Detection for Shopee Code League powered by TensorFlow
The following code as of 11/7/2020 was created by @Vardentoh and I am only modifying his work for future experimentations.

Data Given and following Procedure:
The Data given are labelled images that are not centred and has multiple items on the same image. They come in pre-labelled folders that are formatted to work with flow_from_direcctory. As a result, the data is pre-split into training and testing data.

Initial Experimentation:
The first benchmark model that was created has 1 Conv2D layer built in with a Flatten and 2 Dense layers. MaxPooling was used to reduce the runtime of the model.
Initial model received an accuracy score of 33% which is expected.

Implementation Notes:

The model submitted for the competition is created using Jeremy Howard's Fastai modules with pre-trained weights and added an additional prediction layer.




Features to be implemented in the future

- [ ] Further usage of MaxPooling to speed up fitting process
- [ ] Restructuring of the hidden layers for further optimization
- [ ] Further use of Tensorflow/Pytorch to create more networks and experimentation with results

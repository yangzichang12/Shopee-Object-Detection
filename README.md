# Shopee-Object-Detection
Experimental Object Detection for Shopee Code League powered by TensorFlow

Data Given and following Procedure:
The Data given are labelled images that are not centred and has multiple items on the same image. They come in pre-labelled folders that are formatted to work with flow_from_direcctory. As a result, the data is pre-split into training and testing data.

Initial Experimentation:
The first benchmark model that was created has 1 Conv2D layer built in with a Flatten and 2 Dense layers. MaxPooling was used to reduce the runtime of the model.
Initial model received an accuracy score of 33% which is expected.

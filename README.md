# TimeSeries_MCNN
Exploring Time-series Data Classification in Time-frequency Domain by CNN 
Deep Learning course based project
* Time series data preprocessing: On 162 ECG (electrocardiogram) recordings, sliced the dataset to non-overlapping segments. Then Low pass filter and down-sampling technique was applied to the original signal separately. Augmented data by wavelet transformation, applied Morlet wavelet as mother wavelet.
* Multi-scale convolutional neural network (MCNN): Design the MCNN by local convolution stage, which consists of polling and concatenation; as well as full convolution stage, included convolution and polling, fully connection, softmax activation layers.
* Training, testing and comparing models: Three different models were compared, including Multiscale CNN combined by wavelet transform, only Multiscale CNN model and only wavelet transform model. By adjusting hyper-parameters, the first model had the best accuracy.

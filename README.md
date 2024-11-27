### Image Captioning using CNN-RNN Architecture

##### CNN Encoder:
The CNN encoder is responsible for extracting features from the input image and then flattened the features. After that we are sending those flattened features to embedding layer the get the embedded features. These embedded features will become the input to decoder.

##### RNN Decoder:
The input to RNN Decoder is the output of CNN encoder. RNN generates a sequence of words that describe the image. It uses a recurrent neural network, such as a Long Short-Term Memory (LSTM) or a Gated Recurrent Unit (GRU), to generate the sequence. The decoder is trained to predict the next word in the sequence given the previous words.

### Dataset:
To train the CNN-RNN model for image captioning, we need a dataset of images paired with their corresponding




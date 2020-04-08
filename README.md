# Image-Captioning-with-Complementary-Textual-and-Visual-Cues



Describing an image with natural sentence without human involvement can be achieved using Deep Neural network, it requires knowledge of both image processing and Natural language processing. Most of the existing works are based on single modality model with Encoder-Decoder architecture where input images are encoded using Convolution Neural Network (CNN) and caption is generated by Recurrent Neural Network (RNN). In this paper, we propose image captioning model with complementary visual and textual cues. Our model performs early fusion by combining encoded image features from different CNNs, along with combined textual features from different word embedding techniques. The fused inputs are passed to our language model Long Short-Term Memory (LSTM) which generate captions. The results show that our model with additional complementary information outperforms existing single modality models.

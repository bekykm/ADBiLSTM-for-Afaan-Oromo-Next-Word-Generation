# ADBiLSTM-for-Afaan-Oromo-Next-Word-Generation
This repository provides a resource for neural networks designed for the next-word generation in the Afaan Oromo language. The model leverages the power of attention mechanisms combined with bidirectional LSTMs to enhance the accuracy and fluency of word predictions in Afaan Oromo, a widely spoken Cushitic language in East Africa.

**Key Features**

**Bidirectional LSTM Architecture**: Utilizes both forward and backward LSTM layers to capture contextual information from both directions in the text sequence.

**Attention Mechanism**: Implements an attention layer to focus on relevant parts of the input sequence, improving the model's ability to generate coherent and contextually appropriate words.

**Next Word Prediction**: Trained to predict the next word in a sequence, which can be useful for various natural language processing applications such as text completion and language modeling.

**Dataset**

The model is trained on a dataset of Afaan Oromo text, which includes a diverse range of sources to ensure robustness and generalizability. The dataset preprocessing and tokenization scripts are included in this repository.

**Requirements**

Python 3.x

TensorFlow 2.x or PyTorch 1.x

NumPy
pandas

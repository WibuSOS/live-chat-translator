# live-chat-translator
AI-based live streaming chat translator for thesis requirement in Computer Science Program of BINUS International.

In the world of live streaming, language barrier in the live chat remains an issue as people from any language can gather in one live stream, making it harder to understand what each other has said in the chat. The issue becomes more relevant as many major live streaming platforms still do not have automatic live stream chat translation as their feature. To tackle this issue, the author has built the deep learning models that can perform the automatic translation on the live stream chat’s incoming English messages to Indonesian and outcoming Indonesian messages to English. These models follow the architecture of Seq2Seq model, an encoder for encoding the input and a decoder for predicting the translation. On both of the encoder and decoder, LSTM variant of the RNN is used to learn the important features of a sentence sequentially. Bidirectional language model allows the sentence to be processed in both directions. Global attention network helps the decoder in finding contextual information from the encoder for the prediction.

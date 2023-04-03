# Video_Classification
<h3> Deep Learning Assignment-2</h3>
CNN + LSTM model for video classification.
• Dataset : UCF-101 Dataset
     https://www.crcv.ucf.edu/data/UCF101.phpLinks to an external site.

• Encoder is a CNN. The input image is given to CNN to extract the features. The last hidden state of the CNN is connected to the Decoder.</br>
• Decoder is LSTM. The first time step receives the encoded output from the encoder and also the START vector.


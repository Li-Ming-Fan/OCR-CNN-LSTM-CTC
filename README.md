# OCR-CRNN-CTC

cnn + lstm/gru + ctc (CRNN) for image text recognition


### example results
 
![aaa_recog_test_results](https://github.com/Li-Ming-Fan/OCR-CRNN-CTC/blob/master/aaa_recog_test_results/test_results.JPG?raw=true)
  
  
### decription
  
To run this repo:

1, python data_generator.py 0     &nbsp; &nbsp; &nbsp;     # to generate validation data
  
2, python data_generator.py 1     &nbsp; &nbsp; &nbsp;    # to generate training data
  
3, python script_recog.py      &nbsp; &nbsp; &nbsp;     # to train and validate
  
  
This is branch: fixed_len, fixed-length.


### reference

The model is mainly based on the method described in the article:
  
An End-to-End Trainable Neural Network for Image-based Sequence Recognition and Its Application to Scene Text Recognition
  
Baoguang Shi, Xiang Bai, Cong Yao
  
https://arxiv.org/abs/1507.05717
  
  
</br>
  
We thank Jerod Weinman for make his code available: https://github.com/weinman/cnn_lstm_ctc_ocr



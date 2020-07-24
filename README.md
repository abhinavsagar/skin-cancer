# Skin Cancer Classification
Code for the paper `Convolutional Neural Networks for Classifying Melanoma Images`.

![loss/accuracy](images/skin1.png)

## Data

The dataset can be downloaded from [here](https://challenge2018.isic-archive.com/). This is a binary classification problem. I split the data as shown-

```
dataset train
  benign
   b1.jpg
   b2.jpg
   //
  malignant
   m1.jpg
   m2.jpg
   //  validation
   benign
    b1.jpg
    b2.jpg
    //
   malignant
    m1.jpg
    m2.jpg
    //...
```    

## Environment and tools

1. Jupyter Notebook
2. Numpy
3. Pandas
4. Scikit-image
5. Matplotlib
6. Scikit-learn
7. Keras

## Installation

`pip install numpy pandas scikit-image matplotlib scikit-learn keras`

`jupyter notebook`

## Results

### Loss vs Epoch

![loss/accuracy](images/skin2.png)

### Accuracy vs Epoch

![loss/accuracy](images/skin3.png)

### Confusion Matrix

![roc-auc](images/skin4.png)

### ROC-AUC curve

![roc-auc](images/skin5.png)

### Correct/Incorrect classification samples

![results](images/skin6.png)

## Citing

If you find this code useful in your research, please consider citing the paper:

```
@article{sagar2020convolutional,
  title={Convolutional Neural Networks for Classifying Melanoma Images},
  author={Sagar, Abhinav},
  journal={bioRxiv},
  year={2020},
  publisher={Cold Spring Harbor Laboratory}
}
```

## License

```
MIT License

Copyright (c) 2019 Abhinav Sagar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

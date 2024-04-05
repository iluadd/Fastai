# About
This is a group of the jupyter notebooks for practical part on the chapter 13

*CNNplayground.ipynb* - this one is a notebook from the book plus explorations in the field of the normalization.

*CNNplotWeights.ipynb* - this is my approach to visualizing trained weights.

*CNNdifferentArch.ipynb* - test for the different approach from the internet with the Dence layers

*50classesTry.ipynb* - a try to make good enough CCN without a transfer learning for the 50 class problem.

### How to follow 50classTry:
1)  go to the https://www.kaggle.com/datasets/gpiosenka/car-parts-40-classes/data
2) download archive
3) extract it and change this line:
```python
path = Path('/home/ilua/fastbook_week8_book13/archive/car parts')
```
4) also you can try only simple CNN. Bigger ones are very demanding on the GPU
# EmotionClassification
#### Predicting The Emotion From A User's Twit (Advanced Data Mining Course Assignment)

Train and evaluation information of each model are in these codes below:
BertCode.ipynb
DistilBertCode.ipynb
RobertaCode.ipynb
XLNETCode.ipynb
(still working on them to get better accuracy)

The data agumentation code is in the file below:
DataAgumentation.ipynb
(My computer RAM is not enough to make the desired amount of text, Colab crashes either. still working on it to find a way)


|    Model   |  Epoch | Learning Rate | Accuracy |  Loss | Precision | Recall | F-score |
|------------|--------|---------------|----------|-------|-----------|--------|---------|
|    Bert    |    5   |      2e-5     |    75%   |  0.72 |    68%    |   57%  |   61%   |
|    XLNET   |    5   |      2e-5     |    52%   |  1.32 |    40%    |   36%  |  360%   |
|   Roberta  |    5   |      2e-5     |    34%   |  1.57 |           |        |         |
| DistilBert |    5   |      2e-5     |    96%   |  0.14 |    83%    |  84%   |   83%   |

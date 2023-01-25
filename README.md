# Multi-task X-ray transferable polyrepresentation learning

## How to run the code
git clone https://github.com/anonymous-conference-journal/polyrepresentation.git \
cd polyrepresentation \
\
pip install -r requirements.txt

For training select **training.ipynb** \
For enference select **inference.ipynb**

## Results of polyrepresentation learning

![polyrepresentation image](https://github.com/anonymous-conference-journal/polyrepresentation/blob/main/overview.png?raw=true)

|  | **Siamese embedding, Tabular data, Segmentation features** | **Siamese embedding, Segmentation features** | **Tabular data, Segmentation features** | **Siamese embedding, Tabular data** | **Segmentation features** | **Siamese embedding** | **Tabular data** |
|---|---|---|---|---|---|---|---|
| accuracy | 0,391 | **0,402** | 0,384 | 0,353 | 0,394 | 0,348 | 0,222 |
| balanced acc | 0,38 |**0,386** | 0,369 | 0,348 | 0,385 | 0,329 | 0,211 |
| f1 macro | 0,379 | 0,377 | 0,369 | 0,347 |**0,382** | 0,319 | 0,2 |
| f1 micro | 0,391 |**0,402** | 0,384 | 0,353 | 0,394 | 0,348 | 0,222 |
| f1 weight | 0,392 |**0,396** | 0,387 | 0,353 | 0,393 | 0,342 | 0,212 |
| roc auc ovr | 0,766 |**0,776** | 0,761 | 0,72 | 0,764 | 0,72 | 0,618 |
| roc auc ovr weight | 0,742 |**0,754** | 0,735 | 0,694 | 0,739 | 0,703 | 0,582 |
| roc auc ovo | 0,762 |**0,774** | 0,758 | 0,718 | 0,764 | 0,717 | 0,621 |
| roc auc ovo weight | 0,755 |**0,767** | 0,749 | 0,709 | 0,754 | 0,712 | 0,606 |

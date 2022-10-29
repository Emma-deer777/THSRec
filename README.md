## THSRec
This is the implementation code of our paper **Cooperative Sequential Recommendation via Contrasting Transformer and Hypergraph Network**.

## Requirements
The code is built on Pytorch and the [RecBole](https://github.com/RUCAIBox/RecBole) benchmark library. 

Run the following code to satisfy the requeiremnts by pip:
`pip install -r requirements.txt`

## Run the model

`python run_THSRec.py --model='THSRec' --dataset='retail_beh' --beta='0.00008' `, where 'value' means the default value.

## Tips
- The model code is at `recbole/model/sequential_recommender/thsrec.py`
- The key parameters is at `THSRec.yaml`
## THCSRec
This is the implementation code of our paper **Contrasting Transformer and Hypergraph Network for Cooperative Sequential Recommendation**.

## Requirements
The code is built on Pytorch and the [RecBole](https://github.com/RUCAIBox/RecBole) benchmark library. 

Run the following code to satisfy the requeiremnts by pip:
`pip install -r requirements.txt`

## Run the model

`python run_THCSRec.py --model='THCSRec' --dataset='retail_beh' --beta='0.00008' `, where 'value' means the default value.

## Tips
- The model code is at `recbole/model/sequential_recommender/thcsrec.py`
- The key parameters is at `THCSRec.yaml`

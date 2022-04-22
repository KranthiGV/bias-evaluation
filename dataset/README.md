## Test StereoSet Dataset
- wget 'https://raw.githubusercontent.com/moinnadeem/StereoSet/master/code/evaluation.py'
- wget 'https://github.com/moinnadeem/StereoSet/blob/master/code/predictions/predictions_bert-base-cased_BertNextSentence_BertLM.json'
- python3 evaluation.py --gold-file dev.json --predictions-file ./predictions_bert-base-cased_BertNextSentence_BertLM.json

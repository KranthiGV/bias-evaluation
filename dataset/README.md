## Test CrowS-Pairs Dataset
- `git clone git@github.com:nyu-mll/crows-pairs.git`
- `pip3 install -r ./crows-pairs/requirements.txt`
- `python3 ./crows-pairs/metric.py --input_file ./crows-pairs/data/crows_pairs_anonymized.csv --lm_model bert --output_file crows-pairs-bert-temp-opt`

## Test StereoSet Dataset
- `wget 'https://raw.githubusercontent.com/moinnadeem/StereoSet/master/data/dev.json'`
- `wget 'https://raw.githubusercontent.com/moinnadeem/StereoSet/master/code/evaluation.py'`
- `wget 'https://raw.githubusercontent.com/moinnadeem/StereoSet/master/code/predictions/predictions_bert-base-cased_BertNextSentence_BertLM.json'`
- `python3 evaluation.py --gold-file dev.json --predictions-file ./predictions_bert-base-cased_BertNextSentence_BertLM.json`

## Possible Issues:
- Was getting issuse with installing `en_core_web_sm-2.2.5` Use: `pip3 install https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-2.2.5/en_core_web_sm-2.2.5.tar.gz`

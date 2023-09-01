# English-to-Hindi-Translator
Aim
Create a Hinglish translation from English text. The text should sound natural and also convert all the difficult words and phrases in English to Hinglish. This converted text should be easy to understand for even a non-native Hindi speaker.

**Algorithms Used:**
* AutoTokenizer
* TFAutoModelForSeq2SeqLM
* DataCollatorForSeq2Seq
* AdamWeightDecay
* AutoTokenizer
* TFAutoModelForSeq2SeqLM

Dataset used: (Source: https://huggingface.co/datasets/cfilt/iitb-english-hindi)

**Evaluation Metric**
Bilingual Evaluation Understudty Score (BLEU) can be used to Evaluate the model.
from nltk.translate.bleu_score import sentence_bleu

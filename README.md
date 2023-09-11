# EMNLP Shared Task-2
<h1>BLP Workshop</h1>
<h2>Violence Inciting Text Detection</h2>

<b>Work Flow of System Description Part 1</b>
* First, you have to run the file named MLM training.ipynb
* Then, you have to run the file named Fine Tuning ELECTRA.ipynb
* Lastly, you have to run the file named Test Set Prediction.ipynb

<b>Work Flow of System Description Part 2</b>
* Firstly, for transfer learning approach of XLM-RoBERTa, multiingual-BERT, sagorBERT please go to the folders 'submission xlm-roberta transfer', 'submission mbert' and 'series of tasks 1 sagorsarker' respectively.
* Secondly, run 'training on BD-SHS.ipynb' with path changes as needed.
* Thirdy, run 'applying transfer learning from BD-HS to VITD classification head non freeze.ipynb' with path changes as needed. For sagorBert, also run 'part 2 applying transfer learning from BD-HS to VITD classification head non freeze.ipynb' with path changes as needed.
* Fourtly, run 'applying transfer learning from BD-SHS to VITD Encoder layers non freeze.ipynb' with path changes as needed.
* For training models on both train+ validation data, run 'applying transfer learning from BD-SHS to VITD(train + validation) Encoder layers non freeze.ipynb' with path changes as needed.
* Finally, for generating predicted csv 'csv generator from saved model.ipynb'with path changes as needed.

<b>Work Flow of System Description Part 2</b>
* Go to Folder 'all model prediction val test csv + ensemble notebooks' containing all predicted csv files. The 'sub' string indicates csvs trained on both training + validation sets.
* For stacking, run 'stacking.ipynb'.
* For weighted ensemble, run 'weighted_ensemble.ipynb'.

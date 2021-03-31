BERT MODEL GOOGLE DRIVE LINK : https://drive.google.com/drive/folders/10Quow_tdCHPcAC1njqE7f2orvKCJZanN?usp=sharing

NOTE  : Transformers used models have big file size, so model's files are available in Drive link.
	1. config.json
	2. eval_results.txt
	3. model_args.json
	4. pytorch_model.bin
	5. special_tokens_map.json
	6. tokenizer_config.json
	7. training_args.bin
	8. vocab.txt


USAGE : 

	1. Download all 8 files and collect one folder like "/Desktop/model"
	2. Install necessary library and install model
		!pip install transformers
		!pip install scikit-learn
		!pip install simpletransformers

		from simpletransformers.ner import NERModel, NERArgs
		model = NERModel('bert','/Desktop/model')prediction, model_output = model.predict(["Fail yararına cezayı hafifletecek takdiri nedenlerin varlığı halinde, ağırlaştırılmış müebbet hapis cezası yerine, müebbet hapis; müebbet hapis cezası yerine, yirmibeş yıl hapis cezası verilir. Diğer cezaların altıda birine kadarı indirilir."])

		prediction




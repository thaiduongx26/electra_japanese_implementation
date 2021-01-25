### How to run QA with squad format
```
python run_finetuning.py --data-dir data --model-name electra_small --hparams '{"task_names": ["squad"], "debug": false, "do_train": true, "do_eval": false, "model_size": "small", "max_seq_length": 512, "num_train_epochs": 30, "learning_rate": 3e-5 ,"doc_stride":128, "max_answer_length": 512, "vocab_size": 32000, "learning_rate": 3e-5}
```

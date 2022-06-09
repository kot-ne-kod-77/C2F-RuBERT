# C2F-RuBERT
Code for training and evaluation of coreference resolution model for Russian

In order to start training, install dependies and run the command:
<code>python -m allennlp train -s resulting_models coref_bert.jsonnet</code>

Please note that training requires access to at least 43-45 GB of GPU memory at a time. Distributed training can be set up in the config file in the "distributed" section (see AllenNLP documentation).

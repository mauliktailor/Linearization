# Program for word linearization using N-gram language model
Preliminary:
1. Install Python. The code has been tested with Python 2.7.11.
2. Install KenLM, and install the KenLM Python bindings. (here models are already created in language_models)
3. Place the data and script files in accessible locations. (Modify the paths below as necessary.)

Steps:
1) To run the linearization on the single sentence of brown corpus in data/shuffled.text run,

python ngram_decoder.py language_models/5_gram_model.arpa data/shuffled.txt 64 --future language_models/future_model.arpa > output_order.txt


2) To run the linearization on brown corpus run the ngram_script_creator.ipynb

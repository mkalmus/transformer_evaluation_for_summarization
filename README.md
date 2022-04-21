# A Framework for Evaluating Hugging Face Transformers across Datasets
**Please note that we are still working on further documenting the notebooks and further modularizing the code**

### The directory contains the following files:
```baseline_script.ipynb```: used to create a simple three-sentence baseline. Note that multiprocessing needs to be rewritten.
```summarization_script.ipynb```: script to apply Hugging Face's pre-trained models for summarization
```evaluation_script.ipynb```: script to evaluate generated summaries against the ground truth summmaries by ROUGE and BLEU.

### To-do:
[ ] Better documentation throughout notebooks with links to Transformers docs <br>
[ ] Modularize code to more easily work with all the data in the Datasets package

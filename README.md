# AlT-NER

Alternate-training for multi-source weakly supervised Named Entity Recognition

## Dependency
- python 3.6 [link](https://www.python.org/)
- pytorch 1.6.0 [link](https://pytorch.org/)
- transformers 3.4.0 [link](https://github.com/huggingface/transformers)
- pytokenizations [link](https://github.com/tamuhey/tokenizations)
- NLTK [link](https://www.nltk.org/)

Note: this project is only tested under the given environment.
Other library versions may cause unexpected behaviors.

## Dataset Construction

## Run

Go to the root directory of this project then use the scripts included to start the training and evaluation process.
For example:
```shell script
./run_laptop.sh 5
```
The argument is the GPU id.
Currently this project only partially support parallel training.
We do not recommend running the project on multiple GPUs as this function has not been tested.


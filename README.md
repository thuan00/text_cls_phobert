### Vietnamese text classifier using [PhoBert](https://github.com/VinAIResearch/PhoBERT/) / topic detection
This is a work for the private competition in a data mining course <br>

#### Problem with the dataset:
The labels for class 9 and 20 are mixed together, may be the one who prepared this dataset wants to make the task a bit more challenging and confusing idk :> <br>
With that, the maximum accuracy that we can possibly get is about 92%

#### Experiment
* TF-IDF + SVM  - 85%
* PhoBert last two hidden states + 2-layer MLP  - 88,5%
* PhoBert last two hidden states + 2-layer MLP + turn class 20 into 9  - about 89%+

Colab project link: (dataset included)<br>
https://drive.google.com/drive/u/0/folders/1I_gqBTtGAlr8IRvdLa-GB8XMWAS4K7t2

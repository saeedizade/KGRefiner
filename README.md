## KGRefiner
An Open-source Framework for Knowledge Graph Refinement. <br>
If you use the code, please cite the following paper: <br>
KGRefiner: Knowledge Graph Refinement for Improving Accuracy of Translational Link Prediction Methods
## section 1 : KGRefiner
Code will be coming soon. 
## section 2 : Datasets
Datasets are suitable to run on [OpenKE](https://github.com/thunlp/OpenKE) framework. However, you can find triples in train2id, valid2id, and  test2id files. <br>
We made the FB15K237-Refined from FB15K237 and WN18RR-Refined from WN18RR by our KGRefiner.
## section 3 : Reproducing paper's results
|Model			|	Dataset	|	H@10	| MR| MRR|Link for reproduction|
|:-:		|:-:	|:-:  |:-:  |:-:  |:-:  |
|TransE	|FB15K237	|45.6|347|<b>29.4</b>| [ConvKB paper](https://arxiv.org/pdf/1712.02121)|
|TransE	|FB15K237-Refined	|<b>47.0</b>|<b>203</b>|29.1|
|TransE	|WN18RR	|50.1|3384|<b>22.6</b>|[ConvKB paper](https://arxiv.org/pdf/1712.02121)|
|TransE	|WN18RR-Refined	|<b>53.7</b>|<b>1125</b>|22.2|
<!-- |TransH	|0.512	|0.476|0.501|0.486|| -->
<!-- |TransD	|0.512	|0.476|0.501|0.486|| -->
<!-- |RotatE	|0.512	|0.476|0.501|0.486|| -->
completing table ...
## section 4 : Citations
```
@misc{saeedizade2021kgrefiner,
      title={KGRefiner: Knowledge Graph Refinement for Improving Accuracy of Translational Link Prediction Methods}, 
      author={Mohammad Javad Saeedizade and Najmeh Torabian and Behrouz Minaei-Bidgoli},
      year={2021},
      eprint={2106.14233},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

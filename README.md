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
### section 3.1 : FB15k237
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">Base Line</th>
    <th class="tg-0pky">H@10</th>
    <th class="tg-0pky">MR</th>
    <th class="tg-0pky">MRR</th>
    <th class="tg-0pky">Link for reproduction</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">TransE</td>
    <td class="tg-0pky">45.6</td>
    <td class="tg-0pky">347</td>
    <td class="tg-0pky">29.4</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">TransE + Shang et al </td>
    <td class="tg-0pky">47.6</td>
    <td class="tg-0pky">221</td>
    <td class="tg-0pky">28.8</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">TransE + KGRefiner</td>
    <td class="tg-0pky">47</td>
    <td class="tg-0pky">203</td>
    <td class="tg-0pky">29.1</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">TransD</td>
    <td class="tg-0pky">45.3</td>
    <td class="tg-0pky">256</td>
    <td class="tg-0pky">28.6</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">TransD + Shang et al </td>
    <td class="tg-0pky">48.2</td>
    <td class="tg-0pky">227</td>
    <td class="tg-0pky">28.5</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">TransD + KGRefiner</td>
    <td class="tg-0pky">43.7</td>
    <td class="tg-0pky">227</td>
    <td class="tg-0pky">24</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">RotatE</td>
    <td class="tg-0pky">47.4</td>
    <td class="tg-u0o7"><b>185</b></td>
    <td class="tg-0pky">29.7</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">RotatE + Shang et al </td>
    <td class="tg-0pky">43.8</td>
    <td class="tg-0pky">218</td>
    <td class="tg-0pky">27.3</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">RotatE + KGRefiner</td>
    <td class="tg-0pky">43.9</td>
    <td class="tg-0pky">226</td>
    <td class="tg-0pky">27.9</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">TransH</td>
    <td class="tg-0pky">36.6</td>
    <td class="tg-0pky">311</td>
    <td class="tg-0pky">21.1</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">TransH + Shang et al </td>
    <td class="tg-0pky">47.7</td>
    <td class="tg-0pky">237</td>
    <td class="tg-0pky">28.2</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">TransH + KGRefiner</td>
    <td class="tg-u0o7"><b>48.9</b></td>
    <td class="tg-0pky">221</td>
    <td class="tg-0pky"><b>30.2</b></td>
    <td class="tg-0pky"></td>
  </tr>
</tbody>
</table>


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

# KGRefiner
An Open-source Framework for Knowledge Graph Refinement. <br>
If you use the code, please cite the following paper: <br>
KGRefiner: Knowledge Graph Refinement for Improving Accuracy of Translational Link Prediction Methods
## Section 1 : KGRefiner
Code will be coming soon. 
## Section 2 : Datasets
Datasets are suitable to run on [OpenKE](https://github.com/thunlp/OpenKE) framework. However, you can find triples in train2id, valid2id, and  test2id files. <br>
We made the FB15K237-Refined from FB15K237 and WN18RR-Refined from WN18RR by our KGRefiner.
## Section 3 : Reproducing paper's results
### Section 3.1 : FB15k237
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
    <td class="tg-0pky"><a href="https://arxiv.org/pdf/1712.02121">ConvKB paper</a></td>
  </tr>
  <tr>
    <td class="tg-0pky">TransE + Shang et al </td>
    <td class="tg-0pky">47.6</td>
    <td class="tg-0pky">221</td>
    <td class="tg-0pky">28.8</td>
    <td class="tg-0pky">Notebook</td>
  </tr>
  <tr>
    <td class="tg-0pky">TransE + KGRefiner</td>
    <td class="tg-0pky">47</td>
    <td class="tg-0pky">203</td>
    <td class="tg-0pky">29.1</td>
    <td class="tg-0pky">Notebook</td>
  </tr>
  <tr>
    <td class="tg-0pky">TransD</td>
    <td class="tg-0pky">45.3</td>
    <td class="tg-0pky">256</td>
    <td class="tg-0pky">28.6</td>
    <td class="tg-0pky"><a href="https://www.aclweb.org/anthology/D18-1358.pdf">HRS paper</a></td>
  </tr>
  <tr>
    <td class="tg-0pky">TransD + Shang et al </td>
    <td class="tg-0pky">48.2</td>
    <td class="tg-0pky">227</td>
    <td class="tg-0pky">28.5</td>
    <td class="tg-0pky">Notebook</td>
  </tr>
  <tr>
    <td class="tg-0pky">TransD + KGRefiner</td>
    <td class="tg-0pky">43.7</td>
    <td class="tg-0pky">227</td>
    <td class="tg-0pky">24</td>
    <td class="tg-0pky">Notebook</td>
  </tr>
  <tr>
    <td class="tg-0pky">RotatE</td>
    <td class="tg-0pky">47.4</td>
    <td class="tg-u0o7"><b>185</b></td>
    <td class="tg-0pky">29.7</td>
    <td class="tg-0pky">Notebook</td>
  </tr>
  <tr>
    <td class="tg-0pky">RotatE + Shang et al </td>
    <td class="tg-0pky">43.8</td>
    <td class="tg-0pky">218</td>
    <td class="tg-0pky">27.3</td>
    <td class="tg-0pky">Notebook</td>
  </tr>
  <tr>
    <td class="tg-0pky">RotatE + KGRefiner</td>
    <td class="tg-0pky">43.9</td>
    <td class="tg-0pky">226</td>
    <td class="tg-0pky">27.9</td>
    <td class="tg-0pky">Notebook</td>
  </tr>
  <tr>
    <td class="tg-0pky">TransH</td>
    <td class="tg-0pky">36.6</td>
    <td class="tg-0pky">311</td>
    <td class="tg-0pky">21.1</td>
    <td class="tg-0pky"><a href="https://www.aclweb.org/anthology/D18-1358.pdf">HRS paper</a></td>
  </tr>
  <tr>
    <td class="tg-0pky">TransH + Shang et al </td>
    <td class="tg-0pky">47.7</td>
    <td class="tg-0pky">237</td>
    <td class="tg-0pky">28.2</td>
    <td class="tg-0pky">Notebook</td>
  </tr>
  <tr>
    <td class="tg-0pky">TransH + KGRefiner</td>
    <td class="tg-u0o7"><b>48.9</b></td>
    <td class="tg-0pky">221</td>
    <td class="tg-0pky"><b>30.2</b></td>
    <td class="tg-0pky">Notebook</td>
  </tr>
</tbody>
</table>

### Section 3.2 : WN18RR
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
    <td class="tg-0pky">50.1</td>
    <td class="tg-0pky">3384</td>
    <td class="tg-0pky">22.6</td>
    <td class="tg-0pky"><a href="https://www.aclweb.org/anthology/N18-2053.pdf">Nguyen et al</a></td>
  </tr>
  <tr>
    <td class="tg-0pky">TransE + KGRefiner</td>
    <td class="tg-0pky">53.7</td>
    <td class="tg-0pky">1125</td>
    <td class="tg-0pky">22.2</td>
    <td class="tg-0pky">Notebook</td>
  </tr>
  <tr>
    <td class="tg-0pky">TransH</td>
    <td class="tg-0pky">42.4</td>
    <td class="tg-0pky">5875</td>
    <td class="tg-0pky">18.6</td>
    <td class="tg-0pky"><a href="https://www.aclweb.org/anthology/D18-1358.pdf">HRS paper</a></td>
  </tr>
  <tr>
    <td class="tg-0pky">TransH + KGRefiner</td>
    <td class="tg-0pky">51.4</td>
    <td class="tg-0pky">1534</td>
    <td class="tg-0pky">20.8</td>
    <td class="tg-0pky">Notebook</td>
  </tr>
  <tr>
    <td class="tg-0pky">TransD</td>
    <td class="tg-0pky">42.8</td>
    <td class="tg-u0o7">5482</td>
    <td class="tg-0pky">18.5</td>
    <td class="tg-0pky"><a href="https://www.aclweb.org/anthology/D18-1358.pdf">HRS paper</a></td>
  </tr>
  <tr>
    <td class="tg-0pky">TransD + KGRefiner</td>
    <td class="tg-0pky">52.3</td>
    <td class="tg-0pky">1348</td>
    <td class="tg-0pky">21.4</td>
    <td class="tg-0pky">Notebook</td>
  </tr>
  <tr>
    <td class="tg-0pky">RotatE</td>
    <td class="tg-0pky">54.7</td>
    <td class="tg-0pky">4274</td>
    <td class="tg-0pky">47.3</td>
    <td class="tg-0pky"><a href="https://www.aclweb.org/anthology/D18-2024.pdf">OpenKE paper</a></td>
  </tr>
  <tr>
    <td class="tg-0pky">RotatE + KGRefiner</td>
    <td class="tg-u0o7">57.0</td>
    <td class="tg-0pky">683</td>
    <td class="tg-u0o7">44.8</td>
    <td class="tg-0pky">Notebook</td>
  </tr>
</tbody>
</table>

completing codes (notebooks) for table is still on going.

## section 4 : Citations

```
@article{saeedizade2021kgrefiner,
  title={KGRefiner: Knowledge Graph Refinement for Improving Accuracy of Translational Link Prediction Methods},
  author={Saeedizade, Mohammad Javad and Torabian, Najmeh and Minaei-Bidgoli, Behrouz},
  journal={arXiv preprint arXiv:2106.14233},
  year={2021}
}
```

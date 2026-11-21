<h1 align="center">Hi, I'm Ozan 👋</h1>

<p align="center">
  <a href="https://github.com/wly0eta/vlm2vec-fgvc">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1200&color=8B5CF6&center=true&vCenter=true&width=600&lines=Teaching+VLMs+to+embed+%F0%9F%A7%A0;Fine-grained+recognition+%F0%9F%90%A6+%F0%9F%9A%97+%E2%9C%88%EF%B8%8F;English+or+Latin%3F+Why+not+both.;LoRA+%C2%B7+GradCache+%C2%B7+contrastive+learning" alt="typing" />
  </a>
</p>

<p align="center">
  CS undergrad at <b>UMass Amherst</b> · I work on <b>vision-language models</b> and <b>fine-grained visual recognition</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Amherst,%20MA-555?style=flat-square&logo=googlemaps&logoColor=white" />
  <img src="https://img.shields.io/badge/UMass%20Amherst-881c1c?style=flat-square" />
  <a href="https://github.com/wly0eta/vlm2vec-fgvc"><img src="https://img.shields.io/badge/research-VLM%20embeddings-6f42c1?style=flat-square" /></a>
</p>

---

### 🔬 What I'm working on

**[vlm2vec-fgvc](https://github.com/wly0eta/vlm2vec-fgvc)**: turning generative VLMs (Qwen2.5-VL-7B, Qwen3-VL-2B) into
contrastive **image–text embedding models**, and studying what it costs and what it buys.

<details>
<summary><b>🐦 Fine-grained without forgetting</b>: CUB-200 63% → 90%, VQA unchanged</summary>
<br>

Contrastive fine-tuning on birds raises CUB-200 accuracy from 63% to 90%, while A-OKVQA (84%),
MMBench (79%) and MMMU stay flat. Fine-grained skill and general VQA don't have to trade off.
</details>

<details>
<summary><b>🔤 Names are a vocabulary</b>: English and Latin don't transfer to each other</summary>
<br>

| trained on | English names | Latin names |
|---|---|---|
| English | **90%** | 44% |
| Latin | 70% | **89%** |
| both, mixed | **89%** | **89%** |

Mixing both at the same compute also pulls each species' two names together in embedding space.
</details>

<details>
<summary><b>🚗 Transfer across domains</b>: training on cars helps dogs, aircraft and birds</summary>
<br>

Adding Stanford Cars to the training mix improves every other fine-grained benchmark (Dogs +4.8,
Aircraft +4.4, CUB +3.0) with no in-domain data and no VQA loss.
</details>

<details>
<summary><b>⚙️ The infrastructure</b></summary>
<br>

LoRA + GradCache contrastive training on multi-GPU nodes, paired significance tests
(McNemar + bootstrap CI) on every comparison, and a SQLite results database over 30+ runs.
</details>

### 🛠️ Tools I use

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

### 📊 GitHub stats

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=wly0eta&theme=tokyonight&hide_border=true" />
    <img alt="contribution streak" src="https://streak-stats.demolab.com?user=wly0eta&theme=default&hide_border=true" />
  </picture>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=wly0eta&theme=tokyo-night&hide_border=true&area=true" />
  <img alt="activity graph" src="https://github-readme-activity-graph.vercel.app/graph?username=wly0eta&theme=minimal&hide_border=true&area=true" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/wly0eta/wly0eta/output/snake-dark.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/wly0eta/wly0eta/output/snake.svg" />
</picture>

### 📫 Reach me

<p>
  <a href="https://www.linkedin.com/in/ozan-bicakci/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:ozanbicakci07@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="mailto:obicakci@umass.edu"><img src="https://img.shields.io/badge/UMass%20email-881c1c?style=for-the-badge&logo=maildotru&logoColor=white" /></a>
</p>

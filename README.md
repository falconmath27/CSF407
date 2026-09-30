<div align="center">

# CSF407 · Artificial Intelligence Lab

**A compact collection of hands-on AI experiments — from classical search to Transformers.**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/status-active-22C55E?style=flat-square)

</div>

## What's inside

| Lab | Topic | Files |
|:---|:---|:---:|
| 🔎 **Search** | Breadth-first search, A*, heuristics, and path reconstruction | [Notebook](search_lab/search.ipynb) · [Exercise](search_lab/search_lab_ex.pdf) |
| 🧩 **Logic** | Propositions, action preconditions, state transitions, and planning | [Notebook](logic_lab/logic.ipynb) · [Exercise](logic_lab/logic_lab_ex.pdf) |
| 🎲 **Bayesian Networks** | First- and second-order probabilistic language models | [Notebook](BN_lab/Bn.ipynb) · [Exercise](BN_lab/BN_lab.pdf) |
| 🧠 **Neural Models** | XOR, backpropagation, activation functions, and output layers | [Notebook](NeuralModels/nnmodel.ipynb) · [Exercise](NeuralModels/neur_models_lab.pdf) |
| ⚡ **Transformers** | Translation, text generation, and sentiment classification | [Notebook](Transformers_lab/transformers.ipynb) |
| 🤖 **Agents** | A goal-based warehouse agent powered by BFS | [Notebook](agents_lab/agents.ipynb) · [Exercise](agents_lab/agents_lab.pdf) |

## Quick start

```bash
git clone <repository-url>
cd CSF407

python -m venv .venv
# Windows
.venv\Scripts\activate

pip install jupyter matplotlib torch transformers sentencepiece
jupyter notebook
```

Open any lab notebook and run its cells from top to bottom. The classical AI labs use mostly Python's standard library; the neural and Transformer labs require the additional packages above. Transformer models are downloaded on their first run, so that lab also needs an internet connection.

## Suggested path

```text
Search → Logic → Bayesian Networks → Neural Models → Transformers → Agents
```

Each folder is self-contained and pairs the implementation with its exercise sheet where available.

---

<div align="center">
  <sub>Built for learning, experimenting, and understanding AI one notebook at a time.</sub>
</div>

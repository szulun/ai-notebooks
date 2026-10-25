# Hands-On AI Notebooks

Six interactive notebooks that teach core AI ideas by letting students change a setting and watch what happens. They run in a browser on JupyterHub or Google Colab, with nothing to install by hand.

Built by **SzuLun (Zoey) Huang**, UC Berkeley Data Science, under the guidance of **Eric Van Dusen**.

## The notebooks

| # | Notebook | What students do | Time | Runs on |
|---|----------|------------------|------|---------|
| 1 | [Write with AI: Prompts, Settings, and Your Own Style](Write_with_AI.ipynb) | Meet a small language model that runs on its own. Give it a persona, change settings such as temperature, compare what it writes, and answer short knowledge checks. | See notebook | JupyterHub, Colab |
| 2 | [Why Does AI Forget? Building a Chat Assistant with Memory](Why_Does_AI_Forget.ipynb) | Follow a developer building an AI study assistant that must adapt to students at different levels. Find out why a model forgets, how system prompts shape its behavior, and what to do when a conversation gets too long. | See notebook | JupyterHub, Colab |
| 3 | [How Does a Recommender Know What's “Similar”?](How_Does_a_Recommender_Work.ipynb) | Sort out how AI, ML, DL and LLMs relate with a matching game, then build a small similarity-based recommender. | About 30 min (up to 45 with extensions) | JupyterHub, Colab |
| 4 | [Choosing the Right Model: Machine Learning vs. Deep Learning](Choosing_the_Right_Model.ipynb) | Find out when traditional ML is not enough, see how a neural network learns, walk an interactive decision map of model families, and try a tiny convolution demo. | 30–45 min for the core path | JupyterHub, Colab |
| 5 | [How Do Language Models Work? From Words to Answers](How_Do_Language_Models_Work.ipynb) | Decide when rules are enough and when a language model is needed. Follow text from tokens to embeddings to transformers, then watch a small model predict the next word. | See notebook | JupyterHub, Colab |
| 6 | [From Idea to Launch: Running an AI Project](From_Idea_to_Launch.ipynb) | Walk through a full AI project, from problem to deployment, for a newspaper predicting viral articles. Tune thresholds and see what precision and recall trade off. | See notebook | JupyterHub, Colab |

## Open in Colab


| Notebook | Colab |
|----------|-------|
| Write with AI: Prompts, Settings, and Your Own Style | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/szulun/ai-notebooks/blob/main/Write_with_AI.ipynb) |
| Why Does AI Forget? Building a Chat Assistant with Memory | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/szulun/ai-notebooks/blob/main/Why_Does_AI_Forget.ipynb) |
| How Does a Recommender Know What's “Similar”? | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/szulun/ai-notebooks/blob/main/How_Does_a_Recommender_Work.ipynb) |
| Choosing the Right Model: Machine Learning vs. Deep Learning | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/szulun/ai-notebooks/blob/main/Choosing_the_Right_Model.ipynb) |
| How Do Language Models Work? From Words to Answers | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/szulun/ai-notebooks/blob/main/How_Do_Language_Models_Work.ipynb) |
| From Idea to Launch: Running an AI Project | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/szulun/ai-notebooks/blob/main/From_Idea_to_Launch.ipynb) |

The three notebooks that use a language model (*Write with AI*, *Why Does AI Forget?* and *How Do Language Models Work?*) set themselves up on Colab. The first run installs one package and downloads the model (about 0.8 GB), which takes roughly 3–5 minutes.

## How to use a notebook

1. **Open it** in Colab, or through the JupyterHub link your instructor gave you.
2. **Run everything once.** JupyterHub: *Kernel → Restart Kernel and Run All Cells*. Colab: *Runtime → Run all*.
3. **Play and explain.** Move the sliders, click the buttons, pick from the menus, answer the questions, and say why you chose what you chose.

**You never need to type or change any code.** The code boxes are collapsed on purpose. You only click buttons, move sliders, choose from menus, and type into the text boxes that the notebook shows you. If you are curious, you can open a code box to read it, but you cannot edit it.

**If something looks stuck:** refresh the page and run everything again. Run the boxes from top to bottom rather than one at a time.

**Want to start over with a fresh copy?**
- **JupyterHub:** in the file list on the left, right-click your copy of the notebook and choose *Delete*, then click your instructor's link again. Clicking the link alone does not replace a copy you already have.
- **Colab:** open the Colab link again.

## A note about the questions in the notebooks

Each notebook has a short check at the start and a similar one at the end, plus a few quick prediction and quiz questions. Each notebook also ends with a short review game, just for practice. They are optional and nothing is graded. Answers are sent anonymously (a random code, no name or email) and are used only to learn whether the notebooks help and how to improve them.

## License

See the `LICENSE` file in this repository.

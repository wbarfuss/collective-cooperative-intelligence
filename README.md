# Supplemenatry Information for "Collective Cooperative Intelligence" 
Collective cooperation – in which intelligent actors in complex environments seek ways to improve their joint well-being – is critical for a sustainable future, yet unresolved. Mathematical models are essential for moving forward with this challenge. 
Our perspective paper argues that building bridges between CSS and MARL offers a more robust understanding of the drivers, mechanisms, and dynamics of collective cooperation from intelligent actors in dynamic environments.
Both fields complement each other in their goals, methods, and scope. 

This supplementary information presents a more detailed background on the [literature](02_LiteratureBackground.ipynb). Furthermore, we give all the details regarding the collective reinforcement learning dynamics [framework](03_Framework.ipynb) we employ and how we applied it to create all complex phenomena presented in the main text (see subsequent notebooks).

### Reproducibility {.unnumbered}
This supplementary information was created in a *fully reproducible writing and computing environment* with the help of [nbdev](https://nbdev.fast.ai) and [quarto](https://quarto.org). 

To reproduce all simulations, create a new conda environment with the provided `pythonenvironment.yml` file.

```bash
conda env create -f pythonenvironment.yml
```

This installs also the [Collective Reinforcement Learning Dynamics in Python](https://github.com/BarfussLab/pyCRLD). They are provided by a separate Python package, which is in its early stages of development. 

You activate the environment with:
```bash
conda activate cocoin
```

Afterwards, you should be able to follow along and execute all notebooks.

If you have any feedback, questions or problems with code, please do not hesitate to open a Github issue here: [https://github.com/wbarfuss/collective-cooperative-intelligence/issues](https://github.com/wbarfuss/collective-cooperative-intelligence/issues).


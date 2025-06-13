# Installation point

### How to install Pytorch using UV

1. Follow directions here: [Using uv with PyTorch](https://docs.astral.sh/uv/guides/integration/pytorch/)

# Building a LSTM Neural Network Using PyTorch

<p>
  <img alt="Long Short-Term Memory (LSTM) Intro Figure" src="imgs/lstm_intro.png"/>
</p>

[img source](https://www.aiplusinfo.com/blog/introduction-to-long-short-term-memory-ltsm/)

## Project Description

This project utilizes `Long Short-Term Memory (LSTM)` neural networks, a variant of Recurrent Neural Networks (RNN) that address the vanishing graident problem and can better capture long-term dependencies in sequential data.

### What this Project Does Specifically

I build two Jupyter notebooks,

- Example 1 - Building a Long Short-Term Memory Unit one Component at a time using `PyTorch and Lightning`
- Example 2 - Building a Long Short-Term Memory Unit using `PyTorch and Lightning`, but taking advantage of `nn.LSTM()`

---

## Objective

The project uses two techninques to visualize the latent space of the [MNIST](https://en.wikipedia.org/wiki/MNIST_database) dataset of handwritten digits:

- [Principal Component Analysis (PCA)](https://en.wikipedia.org/wiki/Principal_component_analysis)
- [t-Distributed Stochastic Neighbor Embedding(t-SNE)](https://en.wikipedia.org/wiki/T-distributed_stochastic_neighbor_embedding)

The project contains the key elements:

- `Deep Learning` for neural networks building,
- `Git` (version control),
- `Jupyter` python coded notebooks,
- `Lightning` wrapper for PyTorch to make easier to develop and train deep learning models,
- `Long Short-Term Memory (LSTM)` neural network variant of RNN to process sequential data,
- `Python` the standard modules,
- `PyTorch` Machine Learning framework to train our deep neural network,
- `Recurrent Neural Network (RNN)`,feedback loop neural networks to process sequential data,
- `Tensors` mathematical objects that generalize scalars, vectors, and matrices into higher dimensions. A multi-dimensional array of numbers, and
- `uv` package management including use of `ruff` for linting and formatting

---

## Tech Stack

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Lightning](https://img.shields.io/badge/Lightning-792DE4?style=for-the-badge&logo=lightning&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## Getting Started

Here are some instructions to help you set up this project locally.

---

## Installation Steps

The Python version used for this project is `Python 3.12` to be compatible with `PyTorch`.

Follow the requirements for [Using uv with PyTorch](https://docs.astral.sh/uv/guides/integration/pytorch/)

- Make sure to use python versions `Python 3.9–3.12
- pip version 19.0 or higher for Linux (requires manylinux2014 support) and Windows. pip version 20.3 or higher for macOS.
- Windows Native Requires Microsoft Visual C++ Redistributable for Visual Studio 2015, 2017 and 2019

### Clone the Repo

1. Clone the repo (or download it as a zip file):

   ```bash
   git clone https://github.com/beenlanced/ltsm_project_pytorch.git
   ```

2. Create a virtual environment named `.venv` using `uv` Python version 3.12:

   ```bash
   uv venv --python=3.12
   ```

3. Activate the virtual environment: `.venv`

   On macOs and Linux:

   ```bash
   source .venv/bin/activate #mac
   ```

   On Windows:

   ```bash
    # In cmd.exe
    venv\Scripts\activate.bat
   ```

4. Install packages using `pyproject.toml` or (see special notes section)

   ```bash
   uv pip install -r pyproject.toml
   ```

### Install the Jupyter Notebook(s)

1. **Run the Project**

   - Run the Jupyter Notebook(s) in the Jupyter UI or in VS Code.

---

## Special Notes

- Including`requirements.txt` file as there are unique considerations when using the `TensorFlow` library. Plus, just in case you run into issues wth the `pyproject.toml` file there is the ability to use the requirements file as well to build the virtual environment.

- Running this notebook took approximately 25 minutes to run using an Apple M4 Pro with macOS Sequoia. Depending on the processor(s) that you are running this time will vary.

---

### Final Words

Thanks for visting.

Give the project a star (⭐) if you liked it or if it was helpful to you!

You've `beenlanced`! 😉

---

## Acknowledgements

I would like to extend my gratitude to all the individuals and organizations who helped in the development and success of this project. Your support, whether through contributions, inspiration, or encouragement, have been invaluable. Thank you.

Specifically, I would like to acknowledge:

- [Joshua Starmer - StatQuest](https://youtu.be/YCzL96nL7j0). This project was based off of his Illustrated Guide to Neural Networks and AI course, particularly the LSTM section. Thanks!

- [Hema Kalyan Murapaka](https://www.linkedin.com/in/hemakalyan) and [Benito Martin](https://martindatasol.com/blog) for sharing their README.md templates upon which I have derieved my README.md.

- The folks at Astral for their UV [documentation](https://docs.astral.sh/uv/)

---

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details

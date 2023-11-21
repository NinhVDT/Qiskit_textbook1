# 2023 review: Learn Quantum Computing with Python and IBM Quantum Experience

<a href="https://www.packtpub.com/programming/learn-quantum-computing-with-python-and-ibm-q-experience?utm_source=github&utm_medium=repository&utm_campaign=9781838981006"><img src="https://static.packt-cdn.com/products/9781838981006/cover/smaller" alt="Learn Quantum Computing with Python and IBM Quantum Experience" height="256px" align="right"></a>

This is a 2023 review attempt for the Github repo: https://github.com/PacktPublishing/Learn-Quantum-Computing-with-Python-and-IBM-Quantum-Experience.

The original book can be found [here](https://www.packtpub.com/programming/learn-quantum-computing-with-python-and-ibm-q-experience?utm_source=github&utm_medium=repository&utm_campaign=9781838981006).

## Installation:

To run the code in this repo on your local systems (Linux/Windows):

- Install Anaconda (or Miniconda): https://www.anaconda.com/

- Create a virtual environment with Python 3.7.8:

```
conda create -n qiskit_env python==3.7.8 -c conda-forge
```

- Install requirements.txt:

```
conda activate qiskit_env
pip install -r requirements.txt
```

To be able to run the full code repo, including the IBMQ online components, continue the installation with these steps:

- Go to https://quantum-computing.ibm.com/ and create an account

- Log in and from the Dashboard tab, copy the API token on the top right of the screen

- Replace the copied API token into `setup.py`, then run this file:

```
python setup.py
```

Note that for several regions, a VPN may be required whenever an IBMQ command is called.

## Nov 2023 Update:

`setup.py` is now created to help with the registration for IBMQ (extracted from Chapter 7's notebook).

## Oct 2023 Update:

Currently the online modules of this repo are not working and have been commented out.

However, Chapters 4, 5, 6 are completely offline and run right after installing `requirements.txt`.

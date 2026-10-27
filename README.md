# Anaconda Installation:

- For Linux-based installation [https://www.anaconda.com/docs/getting-started/anaconda/install/linux-install](https://www.anaconda.com/docs/getting-started/anaconda/install/linux-install)

- Or if you are using Windows, follow [https://www.anaconda.com/docs/getting-started/anaconda/install/windows-cli-install](https://www.anaconda.com/docs/getting-started/anaconda/install/windows-cli-install) 


# Virtual Environment Creation and Libraries Installation

1. Create an environment named "qiskit" and then "activate" it using the following commands:

```bash
    conda create -n qiskit python=3

    conda activate qiskit
```

    - The conda environment is now ready for you to install the Qiskit package.

2. Enter the following commands to install the latest version of Qiskit and the other required packages.

```bash
    pip install numpy matplotlib qiskit==2.4.0 jupyter notebook qutip
```
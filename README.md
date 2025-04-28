# Structural_evo_tutorial
An introduction to structural phylogenetics
## Getting Started

Follow these steps to set up the tutorial environment:

1. Change to your home directory:
    ```bash
    cd $HOME
    ```

2. Clone the repository:
    ```bash
    git clone https://github.com/DessimozLab/Structural_evo_tutorial
    cd Structural_evo_tutorial
    ```

3. Install the latest version of [Miniforge](https://github.com/conda-forge/miniforge/):
    ```bash
    wget "https://github.com/conda-forge/miniforge/releases/latest/download/Miniforge3-$(uname)-$(uname -m).sh"

    bash Miniforge3-$(uname)-$(uname -m).sh

    ```

4. Create the environment from the `env.yaml` file:
    ```bash
    mamba env create -f env.yaml
    ```

5. Activate the environment:
    ```bash
    mamba activate structural_evo_env
    ```

6. Start Jupyter Lab to begin the exercises (located in the main folder):
    ```bash
    jupyter lab
    ```
# rna_classifier
Drop in your sequence and see what type of RNA it is!

> **Proof of concept**: The `RNA type classifier` is a `Neural Network` model trained with `CoDNaS-RNA` conformers information.
> Several architectures were tested, the one that gave the best results was a model with `Conv1D`, `GlobalMaxPooling1D` and `Dense` layers.

## Requirements
- UV (>=0.8)
- GPU (optional, but recommended)

### How to install `uv`?
Go to the [UV installation guide](https://docs.astral.sh/uv/getting-started/installation/)

### Installation
#### Step 1
```bash
git clone <repository-url>; cd <repository-name>
```
#### Step 2 (this will create a virtual environment and install the dependencies)
```bash
uv sync
```

### Usage
After cloning the repository and installing the dependencies, go to the repository folder
```bash
cd <repository-name>
```

Then, open the notebook using Jupyter Lab or from VS Code.
```bash
jupyter lab src/notebooks/tf_rna.ipynb
```
or
```bash
code src/notebooks/tf_rna.ipynb
```

## Data sources used

### CoDNaS-RNA
- Website: [CoDNaS-RNA](http://ufq.unq.edu.ar/codnasrna/)
- Release: 2024-08
- Description: Minimal redundant dataset of RNA sequences with RNA type annotations from RCSB, INSDC, SO and CoDNaS-RNA.
- Filepath: [2025-09_cdrna_sequences.tsv.gz](./data/2025-09_cdrna_sequences.tsv.gz)

## Author
- Martín González Buitrón (martingonzalezbuitron@gmail.com)
- Matías Carletti (matias.carletti@gmail.com)

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
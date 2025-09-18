# Memory Augmented-based MAE3D Network(MA-MAE3D)
> MA-MAE3D is designed to reconstruct complete geometries from incomplete observations, thereby facilitating downstream tasks such as classification, segmentation, and 3D object detection.
> 
> Key words:   Point Cloud Completion (PCC), Pretraining–Finetuning, Masked Autoencoder, Memory Network
> 
> Background:
> - The pretraining–finetuning paradigm is widely adopted in deep learning, as it can provide abundant transferable knowledge.
> - However, applying this paradigm to PCC is challenging due to the domain shift between the inputs used in the pretraining and finetuning stages. 

---
The following detiled information will be made public when MA-MAE3D is accepted.

## Table of Contents(TBD)
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Usage Examples](#usage-examples)
- [API / Command Reference](#api--command-reference)
- [Training](#training)
- [Evaluation](#evaluation)
- [Performance / Results](#performance--results)
- [Datasets](#datasets)
- [Model Zoo / Pretrained Weights](#model-zoo--pretrained-weights)
- [Citation](#citation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)


## Installation
(TBD)
### Requirements
Tested on: `Ubuntu 20.04`, `Python 3.9+`

```bash
# create venv (recommended)
python -m venv .venv
source .venv/bin/activate

# install from pip
pip install -r requirements.txt
# or editable install for development
pip install -e .

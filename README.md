

## Setup

Setup a `virtualenv` (optional, but recommended):

```sh
pyenv virtualenv 3.6.4 gsa-adv-cart-analysis-3.6.4
pyenv activate gsa-adv-cart-analysis-3.6.4
```

Install dependencies:

```sh
pip install -r requirements.txt
```

Download a ZIP file of the data from the [Google Drive](https://drive.google.com/drive/folders/1rTe5UUfwc0Wqji_E7s-7M_sX0yr-QkCc) and unzip its contents to the `data/` directory in this project.

Start `Jupyter` if it is not already started:

```sh
jupyter notebook
```

This will spawn a browser window showing a directory browsing interface. Open `GSA Advantage Cart Analysis.ipynb` from that interface to start exploring the data!

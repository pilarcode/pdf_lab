
# Pdf & images lab
A project to explore libraries to extract text from pdfs such as:
* pdfminer
* pyMuPDF
* pyPDF2
* ptpdfium2

Besides, I explore others to extract text from images such as
* pytesseract
* easyocr
* transformers models from huggingface

## Setup

**Step 1**. Navigate to the root directory of the repository and create a new conda environment for development:

```bash
conda create -n <your_env_name> python=3.12 -y && conda activate <your_env_name>
```

**Step 2**. Install poetry

```bash
conda install -c conda-forge poetry
```

**Step 3**. Install  ipywidgets

```bash
conda install -n <your_env_name> ipywidgets
```

**Step 4**. Install all the dependencies

```bash
poetry install --no-root
```

## Usage
Go to the notebook and select your environment to run the cells.
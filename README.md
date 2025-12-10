# Black-Scholes Pricing Model

An interactive Jupyter Notebook implementation of the Black-Scholes-Merton (BSM) option pricing model with visual heatmap analysis.

## Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package manager)

### Setup Instructions

1. **Clone the repository** (or download the files):
   ```bash
   git clone <repository-url>
   ```

2. **Create a virtual environment**:
   
   On Linux/Mac:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   ```
   
   On Windows:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate
   ```

3. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
   
   Or if you're using VS Code, simply open `notebook.ipynb` in the editor.

## Usage

### Running the Notebook

1. Open `notebook.ipynb` in Jupyter Notebook or VS Code
2. Run all cells sequentially (Cell → Run All)
3. Interact with the widgets

## Troubleshooting

### Interactive Widgets

**⚠️ Important: Interactive widgets are essential for full functionality!**

If the interactive widgets don't appear:

1. Ensure `ipywidgets` is installed:
   ```bash
   pip install ipywidgets
   ```

2. For JupyterLab, install the extension:
   ```bash
   jupyter labextension install @jupyter-widgets/jupyterlab-manager
   ```

3. For VS Code, install the "Jupyter" extension from the marketplace


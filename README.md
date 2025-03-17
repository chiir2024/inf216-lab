# INF216 Lab template

This repository serves as a starting point for managing data science projects using Google Colab, Google Drive, and GitHub. It was designed for a lab session taught as part of the module INF216 on version control and dependency management.

## Contents
- `example.ipynb`: A sample Colab notebook with a basic data science workflow (e.g., loading data, plotting).
- `data.csv`: A sample dataset (e.g., simple tabular data like sales or weather records).
- `requirements.txt`: A list of Python package dependencies needed to run the notebook.

## Setup Instructions
1. **Fork this Repository**:
   - Click "Fork" on GitHub to create your own copy under your account.
2. **Clone to Google Drive**:
   - Open Google Colab: `https://colab.research.google.com`.
   - Mount your Drive: `from google.colab import drive; drive.mount('/content/drive')`.
   - Clone the repo: `!git clone https://github.com/<your-username>/inf216-lab.git /content/drive/MyDrive/INF216-week9lab/repo`.
3. **Open the Notebook**:
   - Navigate to `/content/drive/MyDrive/INF216-week9lab/repo/example.ipynb` in Colab and open it.
4. **Install Dependencies**:
   - Run: `!pip install -r /content/drive/MyDrive/ds-lab/repo/requirements.txt` in a Colab cell to install required packages.

## Usage
- **Version Control**:
  - Modify `example.ipynb` (e.g., add a plot or analysis).
  - Save changes to Drive (File > Save).
  - Commit to GitHub: File > Save a copy to GitHub, select your repo, and add a commit message.
- **Collaboration**:
  - Share your repo link with peers. They can clone it, make changes, and commit back.
- **Dependencies**:
  - Update `requirements.txt` with any new packages (e.g., `seaborn==0.12.2`), then reinstall with `!pip install -r requirements.txt`.

## Notes
- Colab’s runtime resets after ~12 hours, so save work to Drive and commit often.
- For advanced Git features (e.g., branching), explore GitHub’s web interface or a local Git setup.

## Example Dependencies
pandas==1.5.3
matplotlib==3.7.1

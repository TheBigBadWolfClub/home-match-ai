# HomeMatch AI

Jupyter notebook project for AI-powered home matching using LangChain and OpenAI.

## Setup

### 1. Create and activate virtual environment

```bash
python3 -m venv venv
source venv/bin/activate  # On macOS/Linux
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Install Jupyter kernel

```bash
python -m ipykernel install --user --name=home-match-ai --display-name "Python (home-match-ai)"
```

### 4. Configure API key

Open `HomeMatch.ipynb` and `GenerateListings.ipynb` and replace `"YOUR API KEY"` with your actual API key.

### 5. Generate listings (if needed)

If `house_listings.csv` doesn't exist, run:

```bash
source venv/bin/activate
jupyter execute GenerateListings.ipynb
```

## Run

### 1. Activate environment and start Jupyter on Web Browser

```bash
source venv/bin/activate
jupyter notebook
```

### 2. Open notebook and select kernel

1. Open `HomeMatch.ipynb`
2. Select kernel: **"Python (home-match-ai)"**
3. Run cells

### 3. Run from command line (alternative)

```bash
source venv/bin/activate
jupyter execute HomeMatch.ipynb
```

**Note:** This will use the default input if no user input is provided.

## Prerequisites

- Python 3.8+
- `house_listings.csv` file (generate using `GenerateListings.ipynb` if needed)
- See `requirements.txt` for package dependencies

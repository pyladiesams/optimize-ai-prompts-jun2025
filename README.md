# ScaleDown: Optimize AI prompts to reduce verbosity and carbon footprint
### Presentation: [ScaleDown: Shrinking AI's CarbonFootprint, One Token at a Time](workshop/ScaleDown_Python_package.pdf)

## Workshop description
During this workshop, you will learn how to leverage the ScaleDown Python package to optimize AI prompts, reduce token usage, and minimize your AI applications' carbon footprint. 

We'll explore practical techniques for creating structured templates, implementing model-specific optimizations, and measuring environmental impact. 

You'll gain hands-on experience with the package's key features while understanding how even small efficiency improvements can lead to significant cost savings and environmental benefits when adopted at scale.

## Requirements
* Google account if you want to use [Google Colab](https://colab.research.google.com/)
* Python 3.10 (recommended) or higher
* Jupyter notebook or jupyter-lab
 
## Usage
### with Google Colab
1. Open [Google Colab notebook](https://colab.research.google.com/drive/1w7bOIs3mOu7btyFjZc_FvYlOIMiE8duJ?usp=sharing)
2. In the top left corner select "File" &#8594; "Save a Copy to Drive"
3. This will open a new tab with a colab notebook that you can edit and run
4. Follow the instructions in the notebook

### with Jupyter notebook
1. First clone the repo:
```bash
git clone https://github.com/pyladiesams/optimize-ai-prompts-jun2025
cd optimize-ai-prompts-jun2025
```
2. Set up a virtual environment using virtualenv:
```
# Install virtualenv package (typically pre-installed)
pip install virtualenv

# Create virtual environment
python3 -m venv .venv

# Activate virtuale environment (command might differ per OS)
source ./.venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```
3. Navigate to `workshop` and run `ScaleDown_compression_challenge.ipynb`.

### ScaleDown API Key

ScaleDown API key can be requested [here](https://docs.scaledown.ai/docs/getting-started/api-keys).

The key in Google Colab will only be available during the workshop. If you want to follow the workshop after, please request your API key via the link above.

If you are using Jupyter notebook locally, please replace `your api key` with your actual ScaleDown API key.
   
## Credits
This workshop was set up by @pyladiesams and @varchanaiyer

# FragranceSuccessPrediction
This project was developed as part of the *Digital Transformation Management* course at the University of Bologna.  
The goal is to build a machine learning system capable of **predicting the commercial success of fragrances**, based on their olfactory composition (notes, accords) and market-related features (brand reputation, perfumer expertise, launch year, etc.).

## Open the Notebook in Google Colab

Click the button below to launch the project directly in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pR0BX_x-prjE5n03EYGJbdaoKlsIoy56#scrollTo=OE3Aw_ZWFnjT)

## Required Dataset

The project uses the **Fragrance Dataset** scraped from [Fragrantica.com](https://www.fragrantica.com/), containing over 24,000 perfumes with attributes such as:
- Brand  
- Perfumer(s)  
- Release year  
- Gender  
- Notes (top, middle, base)  
- Main accords  
- Consumer ratings and rating counts  

### How to use it in Colab:

1. **Download the dataset** from this repository (included in the `.zip`)  
2. Once the notebook is open in Colab, **upload the file manually** using this code:

```python
from google.colab import files
uploaded = files.upload()

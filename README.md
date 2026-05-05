# Emotion Classifier from Text

Fine-tuned DistilBERT model to detect 6 emotions: sadness, joy, love, anger, fear, surprise.

## Live Demo
https://drive.google.com/file/d/1HvtIF1BtFXNG7CqSoPzNIiKVPqT3gooM/view?usp=share_link

## Results
- Validation accuracy: **94.25%**
- Test accuracy: **94.2%**
- Confusion matrix: 
## <img width="563" height="491" alt="Screenshot 2026-05-05 at 15 08 23" src="https://github.com/user-attachments/assets/75cc1912-e1ea-45d8-b627-ce3f4ef35628" />

## Repository structure
- `notebook/` – training and evaluation notebook
- `app/` – Gradio web app
- `model/` – saved model files (via Git LFS)

## Run locally
```bash
git clone ...
cd app
pip install -r requirements.txt
python app.py 



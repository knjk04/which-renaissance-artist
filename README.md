---
title: Which Renaissance Artist
emoji: 🌍
colorFrom: red
colorTo: green
sdk: gradio
sdk_version: 4.12.0
app_file: app.py
pinned: false
license: mit
---

<img width="1230" alt="readme-image" src="https://github.com/knjk04/which-renaissance-artist/assets/11173328/c65d7f98-6cdf-4a77-b209-79a890926d08">


See it [running live](https://huggingface.co/spaces/scronfinkle/which-renaissance-artist) on Hugging Face

Files:
- `artist_detector.ipynb` is the notebook used to train the model
- `app.ipynb` is the deployed version of the notebook that loads the model pickle file
- `app.py` is the deployed version used by Hugging Faces
- `requirements.txt` is automatically detected and installed in a container by Hugging Faces

<img width="638" alt="Pasted Graphic 7" src="https://github.com/knjk04/which-renaissance-artist/assets/11173328/267b00bd-3ea3-4b23-a2d7-cf03ee374720">


Trained on an A5000 24GB using resnet50. 91% accurate.

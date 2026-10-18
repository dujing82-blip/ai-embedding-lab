# AI Embedding Lab — AI Builders Lab

Two Google Colab projects for high-school students.

## Project 1 — Train Your Own Word Embeddings
[Open notebook](01-train-word2vec/Train_Word_Embeddings.ipynb)

- Train 2D Skip-Gram embeddings from scratch with TensorFlow
- Visualize embeddings before and after training and plot loss
- Compare nearest neighbors with cosine similarity
- Experiment with vector arithmetic and its limitations
- Runs on Colab CPU

## Project 2 — CLIP Text-to-Image Search
[Open notebook](02-clip-image-search/CLIP_Text_to_Image_Search.ipynb)

- Load pretrained `openai/clip-vit-base-patch32`
- Search a sample image gallery with natural-language descriptions
- Optionally upload custom images
- No training required; GPU optional

## Run
Open a notebook on GitHub, then use **Open in Colab**, or import it from https://colab.research.google.com/. Run cells from top to bottom.

**Teaching note:** Project 1 uses a small synthetic corpus and cannot guarantee classic Word2Vec analogies. Project 2 downloads pretrained model weights on first run.

MIT License.

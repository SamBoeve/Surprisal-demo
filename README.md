# Surprisal Visualizer

A small Gradio demo that illustrates next-word prediction with a Dutch GPT-2 language model ([GroNLP/gpt2-small-dutch](https://huggingface.co/GroNLP/gpt2-small-dutch)). Type a sentence and the app shows how surprising each word is to the model.

For each sentence, the demo returns:

- the mean (length-normalized) surprisal
- a per-word surprisal plot

**Live demo:** https://huggingface.co/spaces/Sboeve/Surprisal-demo

## Running locally

```bash
pip install gradio surprisal matplotlib
python app.py
```

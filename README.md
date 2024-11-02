# ArabicLLM Tokenization Strategies

## Project Overview and Goal
This study investigates the effectiveness of various tokenization strategies, specifically targeting the challenges of Arabic language processing. Our goal is to optimize tokenization for Arabic NLP tasks by comparing four tokenization methods—Byte Pair Encoding (BPE), WordPiece, BPE with Farasa (a morphological analyzer), and Word-level tokenization—across three vocabulary sizes.

---

## Files

  - **main_model.ipynb:** integrates the main components of the project, potentially covering data preprocessing, model training, and evaluation.
  - **fine_tuning_process.ipynb:** details the fine-tuning process for the model, including steps for training on specific tasks or datasets.
  - **analaysing.ipynb:** dedicated to analyzing project results or processing insights from the model's outputs.
    
---

## Performance Results

The fine-tuned models were evaluated on four downstream tasks, achieving the following F1 scores:
- **News Classification**: 97.8% (BPE with Farasa)
- **Hate Speech Detection**: 68.4% (BPE with Farasa)
- **Sentiment Analysis**: 83.0% (BPE)
- **Natural Language Inference**: 56.3% (BPE with Farasa)

These results underscore the impact of different tokenization strategies on Arabic NLP tasks.

---

**Models**:
   Pre-trained and fine-tuned models are available on Hugging Face:
   - [Arabic Language Model - Tokenization Strategies](https://huggingface.co/nourmorsy)

---

## Citation

If you use this repository, please cite the following paper:
```
@{
  author = {Mohamed Taher Alrefaie and Nour Eldin Morsy and Nada Samir},
  title = {Exploring Tokenization Strategies and Vocabulary Sizes for Enhanced Arabic Language Models},
  journal = {arXiv preprint arXiv:2403.11130},
  year = {2024}
}
```

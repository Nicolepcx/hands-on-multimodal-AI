![OReilly_logo_rgb.png](resources%2FOReilly_logo_rgb.png)

# Hands-On Multimodal AI

This repository provides the hands-on excercises for the Live Event. It covers policy rollouts, reward modeling, trajectory generation, optimization methods, and tool-use training for agentic systems.

## Repository Structure

```
.
├── hands_on/  # Hands-on exercises
├── helper_functions/  # Helper functions for some notebooks     
└── README.md
```

---


## Contents and Exercises

### Section 1 • Multimodal Foundations and Tokenization

Core concepts:

* How transformers extend beyond text  
* Tokenization across text, images, and audio  
* Embedding alignment across modalities  

**Hands-on notebook:**  
(Tokenizing text, images, and audio into embeddings)

<a href="COLAB_LINK_01" target="_blank">
<img src="https://colab.research.google.com/assets/colab-badge.svg"/>
</a>

---

### Section 2 • Working with Images and Videos

Core concepts:

* LVLMs (Large Vision-Language Models)  
* Frame extraction and visual context windows  
* Prompting with visual + textual inputs  

**Hands-on notebook:**  
(Video question answering and visual information extraction)

<a href="COLAB_LINK_02" target="_blank">
<img src="https://colab.research.google.com/assets/colab-badge.svg"/>
</a>

---

### Section 3 • Understanding Audio and Speech

Core concepts:

* Spectrograms and mel-frequency features  
* Audio tokenization and sampling rates  
* Speech transcription and audio classification  

**Hands-on notebook:**  
(Audio Q&A, classification, and transcription)

<a href="COLAB_LINK_03" target="_blank">
<img src="https://colab.research.google.com/assets/colab-badge.svg"/>
</a>

---

### Section 4 • Real-World Multimodal Workflows

Core concepts:

* Speaker segmentation and identification  
* Meeting transcription pipelines  
* Multimodal understanding workflows  

**Hands-on notebook:**  
(Automatic speaker segmentation + transcription + summarization)

<a href="COLAB_LINK_04" target="_blank">
<img src="https://colab.research.google.com/assets/colab-badge.svg"/>
</a>

---

### Section 5 • Multimodal Retrieval-Augmented Generation (RAG)

Core concepts:

* Multimodal RAG pipelines  
* Retrieving text, tables, and images  
* Structured data extraction from PDFs  

**Hands-on notebook:**  
(Asking questions over tables, charts, and images)

<a href="COLAB_LINK_05" target="_blank">
<img src="https://colab.research.google.com/assets/colab-badge.svg"/>
</a>

---

## Prerequisites

To get the most out of these exercises:

* Python 3.12 (Colab recommended)  
* Hugging Face API token  
* Colab Pro (recommended for larger models)  
* Intermediate Python knowledge  
* Basic understanding of LLMs  
* Familiarity with Hugging Face Transformers  

---

## Running the Notebooks

All notebooks are designed to run in **Google Colab without local setup**.

1. Click the **Open in Colab** button for any exercise  
2. Add your Hugging Face token when prompted  
3. Run the cells sequentially  

---

## Recommended Reading

For deeper theoretical background, see:

* [Transformers: The Definitive Guide](https://learning.oreilly.com/library/view/transformers-the-definitive/9781098167004/)* — Chapters 4, 5, 6, and 11 

---

## License

This repository is for educational purposes as part of the O’Reilly Live Event.  
Please respect dataset and model licenses where applicable.

---

Happy building with multimodal AI 🚀



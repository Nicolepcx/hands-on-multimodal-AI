![OReilly_logo_rgb.png](resources%2FOReilly_logo_rgb.png)

# Hands-On Multimodal AI

This repository provides the hands-on excercises for the Live Event. It covers policy rollouts, reward modeling, trajectory generation, optimization methods, and tool-use training for agentic systems.

## Repository Structure

```
.
├── hands_on/  # Hands-on exercises
├── demo/  # Demo Notebooks
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

**Hands-on notebook** — Tokenizing text, images, and audio into embeddings

| Notebook | Colab |
|---|---|
| Multimodal Tokens & Embeddings | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/hands-on/HANDS_ON_session_01_multimodal_tokens_and_embeddings.ipynb) |

**Demos**

| Notebook | Colab |
|---|---|
| Multimodal Tokens & Embeddings | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/demo/DEMO_session_01_multimodal_tokens_and_embeddings.ipynb) |



---

### Section 2 • Working with Images and Videos

Core concepts:

* LVLMs (Large Vision-Language Models)  
* Frame extraction and visual context windows  
* Prompting with visual + textual inputs  

**Hands-on notebook** — Video question answering and visual information extraction

| Notebook | Colab |
|---|---|
| Video Information Extraction | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/hands-on/HANDS_ON_session_02_video_information_extracting.ipynb) |

**Demos**

| Notebook | Colab |
|---|---|
| GLM-4.6 Flash | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/demo/DEMO_session_02_GLM_4_6_Flash.ipynb) |
| LongCat Image Edit | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/demo/DEMO_session_02_LongCat_image_edit.ipynb) |
| Video Classification | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/demo/DEMO_session_02_video_classification_example.ipynb) |
| Video Information Extraction | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/demo/DEMO_session_02_video_information_extracting.ipynb) |


---

### Section 3 • Understanding Audio and Speech

Core concepts:

* Spectrograms and mel-frequency features  
* Audio tokenization and sampling rates  
* Speech transcription and audio classification  

**Hands-on notebook** — Audio Q&A, classification, and transcription

| Notebook | Colab |
|---|---|
| Extract Audio from Video Q&A | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/hands-on/HANDS_ON_session_03_Extract_Audio_from_Video_QA.ipynb) |

**Demos**

| Notebook | Colab |
|---|---|
| Qwen2-Audio Audio Tasks | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/demo/DEMO_session_03_Qwen2_Audio_different_audio_tasks.ipynb) |
| SAM Audio | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/demo/DEMO_session_03_SAM_audio.ipynb) |
| Voxtral Mini 4B Realtime | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/demo/DEMO_session_03_Voxtral_Mini_4B_Realtime.ipynb) |


---

### Section 4 • Real-World Multimodal Workflows

Core concepts:

* Speaker segmentation and identification  
* Meeting transcription pipelines  
* Multimodal understanding workflows  

**Hands-on notebook** — Automatic speaker segmentation + transcription + summarization

| Notebook | Colab |
|---|---|
| AudioFlamingo3 Meeting Analysis | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/hands-on/HANDS_ON_session_04_AudioFlamingo3_meeting_analysis.ipynb) |

**Demos**

| Notebook | Colab |
|---|---|
| Meeting Transcription | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/demo/DEMO_session_04_audio_transcribe_meeting.ipynb) |
| SAM 3 Agent | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/demo/DEMO_session_04_sam3_agent.ipynb) |


---

### Section 5 • Multimodal Retrieval-Augmented Generation (RAG)

Core concepts:

* Multimodal RAG pipelines  
* Retrieving text, tables, and images  
* Structured data extraction from PDFs  

**Hands-on notebook** — Asking questions over tables, charts, and images

| Notebook | Colab |
|---|---|
| Multimodal RAG Pipeline | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/hands-on/HANDS_ON_session_05_Multimodal_RAG_Pipeline.ipynb) |

**Demos**

| Notebook | Colab |
|---|---|
| Multimodal RAG Pipeline | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicolepcx/hands-on-multimodal-AI/blob/main/demo/DEMO_session_05_Multimodal_RAG_Pipeline.ipynb) |


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



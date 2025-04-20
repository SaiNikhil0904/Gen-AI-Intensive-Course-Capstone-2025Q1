# Urban Chronoscope AI  
**Gen AI Intensive Course Capstone 2025Q1**

Urban Chronoscope AI is a generative AI project that transforms present-day images of real-world locations into either historical or futuristic versions. It enhances the experience with era-specific visual and audio narratives.

## What It Does

- Accepts a real-world **image** and a **text query** (e.g., "Show this place in 1980" or "Imagine it in 2100").
- Analyzes the image and understands your request.
- Retrieves relevant historical or futuristic context using a simulated RAG process.
- Generates a new image representing the past or future using Gemini models.
- Adds **narratives**:
  - Audio narration for historical scenes.
  -  Written story for futuristic scenarios.
- Displays side-by-side comparison of original and generated images.

## Process Overview

1. **User Input** – Upload image + enter prompt.
2. **Image Understanding** – Gemini analyzes visual content.
3. **Query Classification** – Detects location and year from user query.
4. **Context Retrieval** – Simulates RAG to fetch relevant background info.
5. **Prompt Generation** – Creates structured input for Gemini.
6. **Image Creation** – Uses Gemini to generate new era-specific image.
7. **Narrative Generation** – Adds engaging context (audio/text).
8. **Final Display** – Shows original + generated image together.

## Technologies Used

- **Gemini API** (`gemini-2.0`)
- **ChromaDB** (simulated RAG)
- **Google Text-to-Speech (gTTS)** for audio
- **PIL & Matplotlib** for image handling
- **Python 3.10+**

---

## Dataset

You can find the dataset used for this project here: [Capstone Dataset on Kaggle](https://www.kaggle.com/datasets/godavarthisainikhil/capstone)

---

> This project was developed as part of the **Gen AI Intensive Course - Capstone Project (Q1 2025)** to explore real-world applications of multimodal generative models with RAG pipelines.

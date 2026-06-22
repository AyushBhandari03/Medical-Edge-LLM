# Project Roadmap

## Goal

Build a medical question-answering assistant using an open-source LLM that can run efficiently on a normal laptop and later on an Android device.

The project includes:
- Creating a medical FAQ dataset
- Fine-tuning the model using QLoRA
- Quantizing the model for faster inference
- Running the model offline
- Comparing performance before and after quantization

---

## Development Plan

### ✅ Stage 1 - Repository Setup
- Create project structure
- Set up Git and GitHub
- Add documentation
- Configure development environment

### ⬜ Stage 2 - Dataset Preparation (Google Colab)
- Collect medical information
- Generate synthetic medical FAQs
- Clean and validate the dataset
- Save the dataset in JSONL format

### ⬜ Stage 3 - Model Fine-tuning (Google Colab)
- Load the base model
- Configure QLoRA
- Fine-tune the model
- Merge LoRA weights

### ⬜ Stage 4 - Export Trained Model
- Download the merged model
- Verify the model
- Prepare it for local use

### ⬜ Stage 5 - GGUF Conversion (Local)
- Convert the model to GGUF
- Verify successful conversion

### ⬜ Stage 6 - Model Quantization (Local)
- Generate Q8_0 model
- Generate Q4_K_M model
- Generate Q3_K_L model

### ⬜ Stage 7 - Benchmarking
- Measure inference speed
- Measure memory usage
- Measure perplexity
- Generate comparison graphs

### ⬜ Stage 8 - Local Deployment
- Run the model on Windows
- Build a simple medical chatbot

### ⬜ Stage 9 - Android Deployment
- Deploy the GGUF model
- Test offline inference

### ⬜ Stage 10 - Project Completion
- Final documentation
- Performance analysis
- Future improvements

---

## Current Progress

**Current Stage:** Stage 1 - Repository Setup

**Progress:** 10%
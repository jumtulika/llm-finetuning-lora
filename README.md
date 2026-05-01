# Fine-Tuning Large Language Models using LoRA (QLoRA)

## 📌 Overview
This project focuses on fine-tuning Large Language Models (LLMs) using LoRA/QLoRA techniques for:
- Text-to-SQL generation
- Instruction-following conversational tasks

## ⚙️ Approach
- Base Model: LiquidAI/LFM2-2.6B
- Fine-tuning: LoRA / QLoRA
- Frameworks: Hugging Face Transformers, TRL
- Quantization: 4-bit (BitsAndBytes)

## 📊 Datasets
- Text-to-SQL Dataset (HeavyDB schema)
- Instruction dataset (HuggingFaceH4 deita-6k)

## 🔧 Key Steps
- Converted structured datasets into chat format
- Applied supervised fine-tuning (SFTTrainer)
- Compared base vs fine-tuned model outputs

## 📈 Results
- Fine-tuned model produced more concise and task-aligned responses
- Improved structure in domain-specific queries (text-to-SQL)
- Better instruction-following behavior

## 🚀 Skills Demonstrated
- LLM Fine-tuning (LoRA / QLoRA)
- Prompt structuring
- Dataset preprocessing for conversational AI
- Model evaluation and comparison

## 📂 Project Structure

## 💡 Business Relevance
- Enables natural language querying of databases (Text-to-SQL)
- Improves efficiency in data-driven decision-making
- Demonstrates real-world application of LLMs in enterprise analytics

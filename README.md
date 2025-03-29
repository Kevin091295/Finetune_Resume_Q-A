# Finetune_Resume_Question-Answers

This repository contains the fine-tuned LLaMA 3.1 3B Instruct model for resume screening, using a Kaggle dataset. It includes the fine-tuning process and an inference notebook to test the model.

Contents
  
    📌 Completed_Resume_FineTune_kaggleData_03_14_25.ipynb – Jupyter Notebook for fine-tuning the model
    
    📌 Test_Inference.ipynb – Jupyter Notebook for testing the fine-tuned model

Technologies & Libraries Used

      🧠 Model: LLaMA 3.1 3B Instruct (Meta AI)
      📊 Dataset: Kaggle Resume Dataset
      🔥 Fine-Tuning: LoRA (Low-Rank Adaptation)
      🖥 Framework: PyTorch
      ⚡ Training Accelerator: Google Cloud T4 GPU
      🔢 Libraries:
                
                Transformers (Hugging Face)

                PEFT (Parameter-Efficient Fine-Tuning)
                
                Bitsandbytes (8-bit and 4-bit quantization)
                
                PyTorch Lightning (for efficient training)
                
                Tokenizers (for text processing)
                

Model Storage

      ✅ Fine-tuned model saved on Hugging Face for easy access and deployment

Features
      
      ✅ Fine-tuned LLaMA 3.1 8B model for resume screening
      ✅ Optimized with LoRA for parameter-efficient training
      ✅ Uses quantization for reduced memory footprint
      ✅ Includes an inference notebook for easy testing
      ✅ Provides perfect answers when asked questions from

Usage

          1️⃣ Fine-tune the model using Completed_Resume_FineTune_kaggleData_03_14_25.ipynb
          
          2️⃣ Test inference with Test_Inference.ipynb on new resume data
          
          3️⃣ Modify and improve based on your specific resume data



🚀 Coming Soon: API deployment & real-world integration!

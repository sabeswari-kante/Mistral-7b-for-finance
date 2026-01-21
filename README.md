# Mistral--7b-for-finance





Synthetic Data Generation: Used Phi-3-Mini (Teacher) to generate reasoning pairs (Explanation + Market Implication) from raw text.
Fine-Tuning: Trained Mistral-7B-v0.3 (Student) using QLoRA (4-bit quantization) on a T4 GPU.
Optimization: Utilized Unsloth for 2x faster training and 60% less memory usage.
Deployment: Automated upload of adapters and datasets to the Hugging Face Hub.



### Inference

This is example code that loads both the foundation model and Bactrian LoRA weights from the Hugging Face model hub, and runs a Gradio interface for inference on a specified input. 
```bash
python generate.py \
    --load_8bit \
    --base_model 'decapoda-research/llama-7b-hf' \
    --lora_weights 'MBZUAI/bactrian-x-llama-7b-lora' \
    --share_gradio 
```


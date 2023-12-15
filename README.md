

### Inference

This is example code that loads both the foundation model and Bactrian LoRA weights from the Hugging Face model hub, and runs a Gradio interface for inference on a specified input. 

for Hindi
```bash
!python generate.py \
    --load_8bit \
    --base_model 'ybelkada/Mistral-7B-v0.1-bf16-sharded' \
    --lora_weights 'HydraIndicLM/mistral-MoQlora-hindi-expert' \
    --share_gradio
```

for Tamil
```bash
!python generate.py \
    --load_8bit \
    --base_model 'ybelkada/Mistral-7B-v0.1-bf16-sharded' \
    --lora_weights 'HydraIndicLM/mistral-MoQlora-tamil-expert' \
    --share_gradio
```

for Punjabi
```bash
!python generate.py \
    --load_8bit \
    --base_model 'ybelkada/Mistral-7B-v0.1-bf16-sharded' \
    --lora_weights 'HydraIndicLM/mistral-MoQlora-punjabi-expert' \
    --share_gradio
```

for Odia
```bash
!python generate.py \
    --load_8bit \
    --base_model 'ybelkada/Mistral-7B-v0.1-bf16-sharded' \
    --lora_weights 'HydraIndicLM/mistral-MoQlora-odia-expert' \
    --share_gradio
```

for Bengali
```bash
!python generate.py \
    --load_8bit \
    --base_model 'ybelkada/Mistral-7B-v0.1-bf16-sharded' \
    --lora_weights 'HydraIndicLM/mistral-MoQlora-bengali-expert' \
    --share_gradio
```

for telgu
```bash
!python generate.py \
    --load_8bit \
    --base_model 'ybelkada/Mistral-7B-v0.1-bf16-sharded' \
    --lora_weights 'HydraIndicLM/mistral-MoQlora-telgu-expert' \
    --share_gradio
```

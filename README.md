# Open-R1-0528-Distill

# Model Usage

## Using with /v1/completions API (Recommended)

We recommend using the raw `/v1/completions` API for precise control of the thinking behavior.

### Prompt template

```
<|role|>system<|says|>You(assistant) are a helpful, respectful and honest INTP-T AI Assistant named Buddy. You are talking to a human(user).
Current mode: System 2, think step-by-step and answer.<|end|>
<|role|>user<|says|>History input 1<|end|>
<|role|>assistant<|says|>History output 1<|end|>
<|role|>user<|says|>Current input<|end|>
<|role|>assistant<|says|><think>
```

# Model Download

ModelScope: https://modelscope.cn/collections/DeepSeek-R1-0528--zhengliumoxing-cb9744ce57744c

Huggingface: https://huggingface.co/collections/OpenBuddy/r1-0528-distill-685828b61c77e5c04240f5a0

# Dataset 

https://huggingface.co/datasets/OpenBuddy/R1-0528-Distill

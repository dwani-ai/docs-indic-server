vLLM setup

python3.10 -m venv venv
source venv/bin/activate

pip install vllm torch

vllm serve RedHatAI/gemma-3-4b-it-FP8-dynamic

vllm serve RedHatAI/gemma-3-4b-it-quantized.w4a16 
# Install

```sh
VLLM_USE_PRECOMPILED=1 uv pip install --editable .
# Building torch CUDA still doesn't work right now it ooms on my computer ill figure this part out later. 
# Anyways at least torch + vllm builds with preinstalled 12.8 (check cuda.txt deps) updated with 
# --extra-index-url https://download.pytorch.org/whl/cu128

# Then you can 
uv run ipython ...
```

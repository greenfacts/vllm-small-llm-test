# Test the use of vllm
*vLLM is a fast and easy-to-use library for LLM inference and serving.*  
https://docs.vllm.ai/en/latest/getting_started/quickstart.html  

Run from within Google Colab using the runtime set to T4 GPU.
Hosts the model [bigscience/bloomz-560m](https://huggingface.co/bigscience/bloomz-560m/tree/main)  
Uses the npx package and localtunnel to create a secure tunnel to the localhost to temporarly create a publicly available tunnel to issue curl commands against.

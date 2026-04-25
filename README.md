# Qsaver
Qwen model based Quiz saver, OCR/split/save/export quiz. Now the script is for CNBO test.

Need llama-server.exe and model file.

Qwen3.5-0.8B-GGUF: https://huggingface.co/unsloth/Qwen3.5-0.8B-GGUF/tree/main; download Qwen3.5-0.8B-UD-Q8_K_XL.gguf and mmproj.gguf and put them in ./models/

llama-server: https://github.com/ggml-org/llama.cpp/releases; download and put them at the same folder with script.

- main
   - qsaver.py
   - llama
   - models
       - Qwen3.5-0.8B-UD-Q8_K_XL.gguf
       - mmproj.gguf

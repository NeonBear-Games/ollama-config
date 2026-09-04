1. **Download Ollama**

  Windows:`irm https://ollama.com/install.ps1 | iex`  
  Linux&Mac:`curl -fsSL https://ollama.com/install.sh | sh`

2. **Choose a model *(qwen3-coder:30b)***

  `ollama pull qwen3-coder:30b`

3. **Launch via claude code**

  `ollama launch claude --config`
  choose qwen3-coder:30b

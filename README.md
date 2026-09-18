1. **Download Ollama**

   Windows: `irm https://ollama.com/install.ps1 | iex`  
   Linux & Mac: `curl -fsSL https://ollama.com/install.sh | sh`

2. **Choose a model** (`qwen3-coder:30b`)

   ```bash
   ollama pull qwen3-coder:30b
   ```

3. **Launch via Claude Code**

   ```bash
   ollama launch claude --config choose qwen3-coder:30b
   ```

4. **Use the `.exe` launcher (Optional)**

   Unzip `launch_claude.zip`, navigate to `dist\launch_claude`, and add `launch_claude.exe` to the desktop. (via shortcuts)
  
   [Download launch_claude.zip](./launch_claude.zip)

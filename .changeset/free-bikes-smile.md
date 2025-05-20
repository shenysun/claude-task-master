---
'task-master-ai': minor
---

Add Ollama as a supported AI provider.

- You can now add it by running `task-master models --setup` and selecting it.
- Ollama is a local model provider, so no API key is required.
- Ollama models are available at `http://localhost:11434/api` by default.
- You can change the default URL by setting the `OLLAMA_BASE_URL` environment variable or by adding a `baseUrl` property to the `ollama` model role in `.taskmasterconfig`.
  - If you want to use a custom API key, you can set it in the `OLLAMA_API_KEY` environment variable.   

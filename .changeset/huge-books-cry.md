---
'task-master-ai': patch
---

add support for custom API base URLs
- Added new `_resolveBaseURL` function to resolve base URLs from environment variables
- Implemented uniform parameter handling across all AI provider clients
- Refactored provider modules to accept and use custom base URLs:
  - Anthropic
  - Google
  - OpenAI
  - OpenRouter
  - Perplexity
  - xAI
- Updated `_unifiedServiceRunner` to resolve and pass base URLs to providers
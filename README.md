# Test New LLMs (CodeLlama, Llama2, etc.) 

Notice you forked chatgpt-ui. if you're trying to test other LLMs (codellama, wizardcoder, etc.) with it, I just wrote a [1-click proxy](https://github.com/BerriAI/litellm#openai-proxy-server) to translate openai calls to huggingface, anthropic, togetherai, etc. api calls.

**code**
```
$ pip install litellm
$ litellm --model huggingface/bigcode/starcoder
#INFO:     Uvicorn running on http://0.0.0.0:8000
$ aider --openai-api-base http://0.0.0.0:8000
```

I'd love to know if this solves a problem for you

<div align="center">
<h1>ChatGPT UI</h1>
</div>

A ChatGPT web client that supports multiple users, multiple languages, and multiple database connections for persistent data storage.

The server of this project：[https://github.com/WongSaang/chatgpt-ui-server](https://github.com/WongSaang/chatgpt-ui-server)

## Documentation
- [English](https://wongsaang.github.io/chatgpt-ui/)
- [中文](https://wongsaang.github.io/chatgpt-ui/zh/)


https://user-images.githubusercontent.com/46235412/227156264-ca17ab17-999b-414f-ab06-3f75b5235bfe.mp4


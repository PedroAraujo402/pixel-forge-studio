# PixelForge Studio 🎮

Pixel art editor para criação de sprites, personagens e animações. Com assistente de IA integrado.

## Features

- ✏️ Ferramentas: lápis, borracha, balde, conta-gotas, retângulo, linha
- 🎨 Paleta de cores + seletor customizado
- 🔄 Flip, rotação, zoom
- 🎬 Animação frame-a-frame com preview
- 📋 Character sheet com 8 slots
- 🤖 Assistente de IA (Hugging Face — gratuito)
- 📦 Export: PNG, spritesheet, character sheet

## Como usar

Abra o `index.html` no navegador. Simples assim.

## IA

O assistente usa a **Hugging Face Inference API** com o modelo open-source **Qwen2.5-Coder-32B-Instruct**. É gratuito e não requer API key.

Para uso ilimitado, crie uma conta em [huggingface.co](https://huggingface.co) e adicione sua token no arquivo `index.html`:

```js
'Authorization': 'Bearer hf_SEU_TOKEN_AQUI'
```

## Tech

- HTML + CSS + JS vanilla (zero dependências)
- Canvas 2D para renderização pixel-perfect
- Sem build step

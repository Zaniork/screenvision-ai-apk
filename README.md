# ScreenVision AI - Android APK & Screen Advisor

Este repositório contém a suíte completa do ScreenVision AI para compilar em APK Android através do GitHub Actions.

## Como Gerar o APK
1. Vá até a aba **Actions** neste repositório.
2. Selecione o workflow **Build Android APK (ScreenVision AI)**.
3. Clique em **Run workflow** (escolha debug ou release).
4. Ao finalizar, baixe o APK diretamente na seção **Artifacts** da execução!

## Variáveis Secretas Recomendadas (Settings > Secrets and variables > Actions):
- `GROQ_API_KEY`: Sua chave de API da Groq para Llama 3.2 Vision.
- `GEMINI_API_KEY`: Sua chave de API do Google Gemini.

# Trancrição de imagens com Python

## Descrição

Este projeto utiliza a biblioteca `google.generativeai` para transcrever o conteúdo de imagens carregadas em formato JPEG. A funcionalidade principal permite que você envie uma imagem para o modelo generativo da Google, que processará a imagem para extrair o texto nela contido.

## Pré-requisitos

- Python 3.x
- `google-generativeai` instalado
- Arquivo `.env` configurado com sua chave de API do Google

## Instalação

1. Execute o script Python:
    ```bash
    python transcricao_imagem.py

O script começará por carregar uma imagem 2.png e enviá-la ao modelo generativo da Google para transcrição. Após o processamento, o texto extraído será exibido no terminal.
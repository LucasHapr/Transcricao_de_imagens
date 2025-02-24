# 📜 Image-to-Text Transcription with Google AI  

Este projeto utiliza a inteligência artificial do Google para converter imagens em texto de forma eficiente e precisa. Com a **Google Cloud Vision API**, é possível extrair textos de imagens como documentos escaneados, placas, recibos e outros.  

## 🚀 Funcionalidades  
✅ **Reconhecimento de texto em imagens** com alta precisão.  
✅ **Suporte para múltiplos idiomas** disponibilizados pela Google AI.  
✅ **Processamento de várias imagens em lote** para maior eficiência.  
✅ **Exportação dos textos extraídos** em `.txt`, `.csv` ou outros formatos.  
✅ **Configuração flexível** para ajustar parâmetros de OCR.  

## 🛠️ Tecnologias Utilizadas  
- **Python** 🐍  
- **Google Cloud Vision API** 🧠  
- **Pillow** 📷 (manipulação de imagens)  
- **Tesseract OCR** (opcional, como fallback)  

## 📌 Pré-requisitos  
Antes de executar o projeto, certifique-se de ter:  
- **Python 3.8+** instalado.  
- Uma conta na **Google Cloud Platform** com a **Vision API** ativada.  
- Um arquivo de credenciais JSON da API.  

## 🚀 Como Usar  
1. Clone este repositório:  
   ```sh
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```  
2. Instale as dependências:  
   ```sh
   pip install -r requirements.txt
   ```  
3. Configure a autenticação da **Google Cloud Vision API** adicionando o caminho do JSON de credenciais:  
   ```sh
   export GOOGLE_APPLICATION_CREDENTIALS="caminho/para/seu/arquivo.json"
   ```  
4. Execute o script para processar uma imagem:  
   ```sh
   python main.py --image caminho/para/imagem.jpg
   ```  
5. Para processar várias imagens de uma vez, use:  
   ```sh
   python main.py --folder caminho/para/pasta/
   ```  

## 🖼️ Exemplo de Uso  
Entrada:  
(imagem)

Saída (texto extraído):  
```
Este é um exemplo de transcrição de texto a partir de uma imagem.
```  

## 🔄 Contribuindo  
Se quiser contribuir com melhorias para o projeto:  
1. Faça um **fork** do repositório.  
2. Crie um **branch** para a nova funcionalidade:  
   ```sh
   git checkout -b minha-nova-feature
   ```  
3. Faça o commit das alterações:  
   ```sh
   git commit -m "Adiciona nova funcionalidade X"
   ```  
4. Envie para o GitHub:  
   ```sh
   git push origin minha-nova-feature
   ```  
5. Abra um **Pull Request**! 🚀  

## 📜 Licença  
Este projeto está licenciado sob a **MIT License** – fique à vontade para usar e contribuir!  

---
💡 **Dica:** Se precisar de suporte ou encontrar um bug, abra uma issue! 🚀  

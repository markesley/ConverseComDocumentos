# Converse com Documentos 📚

Uma aplicação desenvolvida com Streamlit que permite conversar com documentos PDF carregados. Ideal para buscar informações específicas de documentos grandes de forma rápida e intuitiva.

## Funcionalidades

- **Carregar documentos PDF**: Carregue múltiplos arquivos PDF na aplicação.
- **Divisão inteligente de textos**: Usa divisão baseada em caracteres para otimizar o processamento.
- **Consulta por IA**: Faça perguntas em linguagem natural e obtenha respostas baseadas no conteúdo dos documentos carregados.
- **Modelos personalizáveis**: Suporte para modelos Hugging Face e OpenAI.
- **Referências das respostas**: Identifique de qual documento e página veio a resposta fornecida.

## Pré-requisitos

Certifique-se de ter os seguintes itens instalados:

- Python 3.9+
- [Streamlit](https://streamlit.io/)
- Conta na [Hugging Face](https://huggingface.co/) (opcional para modelos de IA).
- Chave de API do OpenAI (opcional).

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
2. Crie um ambiente virtual e instale as dependências
python -m venv venv
source venv/bin/activate # ou venv\Scripts\activate no Windows
pip install -r requirements.txt

3. Crie um arquivo .env na raiz do projeto com suas chaves de API:
   HUGGINGFACEHUB_API_TOKEN=your_huggingface_api_token
   OPENAI_API_KEY=your_openai_api_key

4. Execute
   streamlit run projeto3.py



![Captura de tela 2025-01-02 204050](https://github.com/user-attachments/assets/834e1f28-bd09-489a-9432-b1cd822c90b1)

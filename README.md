# Análise de Cartões de Crédito com Azure AI

Este projeto foi desenvolvido como parte do bootcamp **AI-102** oferecido pela [DIO - Digital Innovation One](https://www.dio.me/) em parceria com a Microsoft. Ele demonstra como utilizar o **Azure AI** para realizar a análise de cartões de crédito, utilizando a linguagem **Python** e serviços como **Azure Document Intelligence** e **Azure Blob Storage**.

## Funcionalidades

- Processamento e análise de documentos de cartões de crédito.
- Extração de informações usando o **Azure AI Document Intelligence**.
- Upload e manipulação de arquivos no **Azure Blob Storage**.
- Interface interativa com **Streamlit**.
- Configuração segura com **dotenv**.

## 🛠️ Tecnologias Utilizadas

- **Python**
- **Azure AI Document Intelligence**
- **Streamlit** (para a interface do usuário)
- **Azure Blob Storage**
- **dotenv** (para gerenciamento de variáveis de ambiente)

---

## Pré-requisitos

Antes de começar, você precisará ter:

- **Conta no Azure** para configurar os serviços necessários.
- **Python 3.8 ou superior** instalado no seu sistema.
- Um ambiente virtual configurado (recomendado).

---

## 🚀 Como Executar o Projeto

1. **Clone este repositório**:

```https://github.com/AlinyKelly/PROJDOCSFRAUDE.git```

2. Configure o arquivo .env:

```
ENDPOINT = "ENDPOINT DOCUMENT INTELLIGENCE"
SUBSCRIPTION_KEY = "KEY DOCUMENT INTELLIGENCE"
AZURE_STORAGE_CONNECTION_STRING = "STORAGE CONNECTION STRING"
CONTAINER_NAME = "NOME DO CONTAINER"
```

3. Instale as dependências do projeto:
- Navegue até a pasta src e execute:

```pip install -r src/requirements.txt```

4. Execute o projeto:

- Use o comando abaixo para iniciar o servidor do Streamlit (Windows):

```
python -m streamlit run app.py
```

5. Acesse a aplicação:

```Abra o navegador e vá para http://localhost:8501.```

## 🤝 Contribuições

Contribuições são bem-vindas! Siga os passos abaixo para contribuir:

1. Faça um fork do repositório.
2. Crie uma branch para sua feature: git checkout -b feature/sua-feature.
3. Realize suas alterações e faça commit: git commit -m 'Adiciona nova feature'.
4. Faça um push para a branch: git push origin feature/sua-feature.
5. Abra um Pull Request.

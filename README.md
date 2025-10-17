# chatbot-pdfs-azure-ai
Chatbot baseado em PDFs usando Azure AI Foundry (GPT-4o + embeddings)

# 🤖 Chatbot baseado em PDFs usando Azure AI Foundry

Projeto desenvolvido como desafio final da DIO, integrando **Azure AI Foundry** com os modelos **GPT-4o** e **text-embedding-3-large**.

## 🎯 Objetivo
Criar um **chat interativo** capaz de responder perguntas com base em conteúdos de arquivos PDF.  
O sistema utiliza IA generativa e embeddings para analisar e responder de forma contextual.

## 🧩 Tecnologias e Modelos
- Azure AI Foundry  
- GPT-4o (Chat Completion)  
- text-embedding-3-large (Embeddings)  
- Azure OpenAI Service  
- Azure Web App  

## 🧠 Funcionalidades
- Upload de PDFs e vetorização do conteúdo  
- Sistema de busca inteligente (busca vetorial)  
- Chat interativo que responde com base nos documentos carregados  
- Geração de respostas contextualizadas e referenciadas  

## 📁 Estrutura do repositório
chatbot-pdfs-azure-ai/
│
├── inputs/
│ └── exemplo.txt
│
└── README.md


## 🚀 Como o projeto foi construído
1. Criação de um **hub** no Azure AI Foundry  
2. Deploy dos modelos `gpt-4o` e `text-embedding-3-large`  
3. Configuração do **Playground** com PDFs e contexto de SNA  
4. Deploy de uma **Web App** com autenticação e histórico de chat  
5. Testes de interação e análise das respostas geradas  

## 💡 Insights aprendidos
- Como integrar modelos de linguagem no Azure  
- Como conectar embeddings para busca semântica  
- Boas práticas de deploy de chatbots no Foundry  
- Otimização de custos e tokens por minuto  

## 🧾 Autor
**Marlon Cardozo**  
Desenvolvido para o desafio **"Criando um Chatbot baseado em PDFs" - DIO x Microsoft**

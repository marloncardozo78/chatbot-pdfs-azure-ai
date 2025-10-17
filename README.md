🧠 Projeto 2 – Chatbot baseado em PDFs com Azure AI Foundry 📘 Descrição

Este projeto foi desenvolvido como parte do Desafio Final da DIO - Microsoft AI. O objetivo é criar um chat inteligente capaz de responder perguntas com base no conteúdo de arquivos PDF, utilizando os recursos da Azure AI Foundry e o modelo GPT-4.1-mini.

🎯 Objetivo

Demonstrar a integração entre:

Modelos de linguagem do Azure (GPT-4.1-mini)

Conhecimento baseado em documentos (PDFs)

Playground de Agentes da Azure AI Foundry

O agente lê os arquivos PDF e responde de forma contextual, gerando respostas fundamentadas.

⚙️ Tecnologias Utilizadas

Azure AI Foundry

GPT-4.1-mini (Chat Completion)

Vector Store para embeddings

Playground de Agentes

GitHub (documentação e versionamento)

🧩 Estrutura do Repositório ├── agent-config.json # Export do agente configurado no Azure (prova técnica) ├── inputs/ # Pasta opcional com PDFs de teste ├── README.md # Documentação principal └── LICENSE # Licença MIT

🚀 Execução e Testes

Acesse o Azure AI Foundry → https://ai.azure.com

Vá em Playgrounds → Agentes

Selecione o agente configurado (Agent449)

Faça perguntas sobre os PDFs carregados (ex: “Resuma o conteúdo de impressao.pdf”)

O modelo responde com base nos dados armazenados nos documentos.

📎 Evidências

Modelo implantado: gpt-4.1-mini

Agente criado: Agent449

PDFs integrados: impressao.pdf, slides.pdf

Export JSON: agent-config.json

👤 Autor

Marlon Cardozo Desenvolvido para o programa Microsoft AI + DIO. 🔗 GitHub do Projeto

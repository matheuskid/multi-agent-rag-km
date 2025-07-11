# 🧠 RAG Multiagente para Recuperação de Conhecimento Organizacional

Este projeto implementa um sistema de Recuperação Aumentada de Geração (RAG) baseado em múltiplos agentes especializados para apoiar a gestão do conhecimento organizacional. Utilizando o framework [LangGraph](https://github.com/langchain-ai/langgraph), o sistema é capaz de interpretar perguntas feitas por usuários e gerar respostas contextualizadas com apoio de LLMs.

---

## ⚙️ Pré-requisitos

- Python 3.10+
- API key válida da Mistral, Groq ou outro provedor de LLM

---

## 🔧 Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/matheuskid/multi-agent-rag-km.git
```

### 2. Crie um ambiente virtual

```bash
python3 -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate
```

### 3. Configure variáveis de ambiente

```bash
MISTRAL_API_KEY=your_mistral_key
GROQ_API_KEY=your_groq_key
```

---

## 🧪 Execução
Para executar, basta abrir o arquivo Rag-Agentica.ipynb e executar todas as celulas. <br>
A última celula contem a pergunta a ser enviada para o sistema (variável query_teste).
<img width="1162" height="324" alt="image" src="https://github.com/user-attachments/assets/97a56b3d-73d4-445b-bea8-a775d649a244" />






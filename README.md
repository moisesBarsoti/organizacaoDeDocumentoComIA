# Laboratório de Organização e Pesquisa de Documentos com IA

## 📌 Visão Geral
Repositório contendo a implementação de um pipeline de processamento de documentos utilizando técnicas de IA para:
- Ingestão inteligente de conteúdo
- Criação de índices semânticos
- Exploração de conhecimento em bases documentais

## 🎯 Objetivos
| Objetivo | Descrição |
|----------|-----------|
| **Implementação** | Construir pipeline completo de processamento |
| **Documentação** | Registrar todo o processo técnico |
| **Exploração** | Testar consultas semânticas nos dados |

## 🛠️ Tecnologias Utilizadas
- **Linguagem**: Python 3.x
- **Frameworks**: 
  - LangChain (orquestração)
  - FAISS (vetorização)
- **Modelos**: 
  - OpenAI Embeddings
  - (Opcional) HuggingFace

## 📂 Estrutura do Projeto

├── /data
│ ├── raw/ → Documentos originais
│ └── processed/ → Textos pré-processados
├── /src
│ ├── ingestion.py → Scripts de ingestão
│ ├── indexing.py → Criação de índices
│ └── query.py → Consultas semânticas
├── /notebooks → Análises exploratórias
├── /docs → Documentação adicional
└── /images → Capturas de tela


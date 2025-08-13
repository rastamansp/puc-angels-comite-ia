# 📚 Glossário de Inteligência Artificial para Chatbots

## 🎯 Sobre este Glossário

Este documento contém definições e explicações dos principais conceitos de Inteligência Artificial utilizados no workshop **"Criando Chatbot de IA com N8N"**. Use como referência rápida durante e após o workshop.

---

## 🔤 Índice Alfabético

- [**A**](#a) - AI Agent, API
- [**B**](#b) - Banco de Dados Vetorial, Base de Conhecimento
- [**C**](#c) - Chatbot, Consulta Vetorial, Contexto
- [**D**](#d) - Deep Learning, Deploy
- [**E**](#e) - Embeddings, ETL
- [**F**](#f) - Fine-tuning, Framework
- [**G**](#g) - GPT, Generative AI
- [**H**](#h) - Hallucination, HTTP
- [**I**](#i) - IA, Integração, Inference
- [**J**](#j) - JSON
- [**L**](#l) - LLM, Large Language Model
- [**M**](#m) - Memória, Modelo, Machine Learning
- [**N**](#n) - N8N, Neural Network
- [**O**](#o) - OpenAI, Orchestration
- [**P**](#p) - Pinecone, Prompt, Prompt Engineering
- [**Q**](#q) - Query, Q&A
- [**R**](#r) - RAG, Retrieval, Response
- [**S**](#s) - Similaridade, Semântica, Sistema
- [**T**](#t) - Token, Training, Tools
- [**U**](#u) - User Experience, User Interface
- [**V**](#v) - Vector, Vector Store
- [**W**](#w) - Workflow, Webhook

---

## A

### **AI Agent (Agente de IA)**
- **Definição:** Sistema inteligente que pode perceber seu ambiente, tomar decisões e executar ações para atingir objetivos específicos
- **No contexto do workshop:** O componente central do chatbot que orquestra todas as operações, decide quando usar ferramentas e como responder
- **Exemplo:** O agente "Marley" que gerencia conversas sobre Junior Dread

### **API (Application Programming Interface)**
- **Definição:** Conjunto de regras e protocolos que permite que diferentes sistemas se comuniquem entre si
- **No contexto do workshop:** Usado para conectar N8N com OpenAI, Pinecone e Google Sheets
- **Exemplo:** OpenAI API para enviar prompts e receber respostas

---

## B

### **Banco de Dados Vetorial**
- **Definição:** Sistema de armazenamento especializado em dados vetoriais (embeddings) que permite busca rápida por similaridade
- **No contexto do workshop:** Pinecone armazena embeddings para busca semântica eficiente
- **Características:** Indexação otimizada, busca por similaridade, escalabilidade

### **Base de Conhecimento**
- **Definição:** Repositório estruturado de informações sobre um domínio específico
- **No contexto do workshop:** Conjunto de dados sobre Junior Dread (biografia, shows, discografia)
- **Exemplo:** Documentos, FAQs, dados estruturados sobre o artista

---

## C

### **Chatbot**
- **Definição:** Software que simula conversas humanas através de texto ou voz
- **No contexto do workshop:** Sistema automatizado que responde perguntas sobre Junior Dread
- **Tipos:** Baseado em regras, IA, híbrido

### **Consulta Vetorial**
- **Definição:** Busca por similaridade entre vetores numéricos (embeddings)
- **No contexto do workshop:** Encontrar informações relacionadas mesmo com palavras diferentes
- **Exemplo:** Buscar por "música reggae" encontra informações sobre "Junior Dread"

### **Contexto**
- **Definição:** Informações sobre o estado atual da conversa e interações anteriores
- **No contexto do workshop:** Sistema de memória que mantém histórico das conversas
- **Importância:** Permite respostas mais relevantes e personalizadas

---

## D

### **Deep Learning**
- **Definição:** Subconjunto de machine learning que usa redes neurais com múltiplas camadas
- **No contexto do workshop:** Base tecnológica dos LLMs como GPT-4
- **Características:** Aprendizado automático de padrões complexos

### **Deploy**
- **Definição:** Processo de disponibilizar uma aplicação em produção
- **No contexto do workshop:** Colocar o chatbot em funcionamento para uso real
- **Considerações:** Performance, escalabilidade, monitoramento

---

## E

### **Embeddings**
- **Definição:** Representação numérica (vetorial) de texto, imagens ou outros dados
- **No contexto do workshop:** Converte perguntas e respostas em números para comparação
- **Características:** Vetores de alta dimensionalidade, similaridade semântica
- **Exemplo:** OpenAI Embeddings API

### **ETL (Extract, Transform, Load)**
- **Definição:** Processo de extrair dados de fontes, transformá-los e carregá-los em um destino
- **No contexto do workshop:** N8N pode executar operações ETL para preparar dados

---

## F

### **Fine-tuning**
- **Definição:** Processo de ajustar um modelo pré-treinado para uma tarefa específica
- **No contexto do workshop:** Personalizar um LLM para o domínio de música reggae
- **Vantagens:** Melhor performance em tarefas específicas

### **Framework**
- **Definição:** Estrutura de software que fornece funcionalidades básicas para desenvolvimento
- **No contexto do workshop:** N8N como framework de automação de workflows

---

## G

### **GPT (Generative Pre-trained Transformer)**
- **Definição:** Modelo de linguagem baseado em arquitetura Transformer
- **No contexto do workshop:** OpenAI GPT-4 para geração de respostas
- **Características:** Geração de texto, compreensão de contexto

### **Generative AI**
- **Definição:** Tipo de IA que pode gerar novo conteúdo (texto, imagem, áudio)
- **No contexto do workshop:** LLMs que geram respostas para perguntas
- **Exemplos:** ChatGPT, DALL-E, Midjourney

---

## H

### **Hallucination**
- **Definição:** Fenômeno onde um LLM gera informações incorretas ou inventadas
- **No contexto do workshop:** RAG ajuda a reduzir alucinações fornecendo dados reais
- **Prevenção:** Base de conhecimento confiável, validação de respostas

### **HTTP (HyperText Transfer Protocol)**
- **Definição:** Protocolo de comunicação para transferência de dados na web
- **No contexto do workshop:** Usado para APIs REST entre N8N e serviços externos

---

## I

### **IA (Inteligência Artificial)**
- **Definição:** Campo da computação que busca criar sistemas capazes de realizar tarefas que normalmente requerem inteligência humana
- **No contexto do workshop:** Chatbots inteligentes, processamento de linguagem natural
- **Subcampos:** Machine Learning, Deep Learning, NLP

### **Integração**
- **Definição:** Processo de conectar diferentes sistemas e serviços para funcionarem em conjunto
- **No contexto do workshop:** Conectar N8N com OpenAI, Pinecone e Google Sheets
- **Benefícios:** Automação, eficiência, funcionalidades expandidas

### **Inference**
- **Definição:** Processo de usar um modelo treinado para fazer predições ou gerar respostas
- **No contexto do workshop:** LLM processando perguntas e gerando respostas
- **Características:** Tempo real, baixa latência

---

## J

### **JSON (JavaScript Object Notation)**
- **Definição:** Formato de dados leve e legível para humanos
- **No contexto do workshop:** Formato padrão para troca de dados entre APIs
- **Estrutura:** Chave-valor, arrays, objetos aninhados

---

## L

### **LLM (Large Language Model)**
- **Definição:** Modelo de IA treinado com grandes volumes de texto para compreender e gerar linguagem natural
- **No contexto do workshop:** OpenAI GPT-4 para processamento de conversas
- **Características:** Compreensão contextual, geração de texto, conhecimento geral

### **Large Language Model**
- **Definição:** Ver LLM

---

## M

### **Memória**
- **Definição:** Sistema que armazena e recupera informações sobre interações anteriores
- **No contexto do workshop:** Simple Memory no N8N para manter contexto de conversas
- **Tipos:** Memória de curto prazo, longo prazo, contextual

### **Modelo**
- **Definição:** Representação matemática de um sistema ou processo
- **No contexto do workshop:** LLM treinado para compreender e gerar linguagem
- **Características:** Parâmetros, arquitetura, performance

### **Machine Learning**
- **Definição:** Campo da IA que permite sistemas aprenderem com dados sem programação explícita
- **No contexto do workshop:** Base tecnológica dos LLMs e sistemas de embeddings

---

## N

### **N8N**
- **Definição:** Plataforma open-source de automação de workflows
- **No contexto do workshop:** Ferramenta principal para construir o chatbot
- **Características:** Interface visual, nodes conectáveis, integrações nativas

### **Neural Network**
- **Definição:** Modelo computacional inspirado no cérebro humano
- **No contexto do workshop:** Arquitetura base dos LLMs
- **Componentes:** Neurônios, camadas, conexões

---

## O

### **OpenAI**
- **Definição:** Empresa de pesquisa em IA que desenvolve modelos como GPT
- **No contexto do workshop:** Fornece LLMs e embeddings para o chatbot
- **Serviços:** GPT-4, Embeddings API, DALL-E

### **Orchestration**
- **Definição:** Coordenação de múltiplos serviços e sistemas para executar um workflow
- **No contexto do workshop:** N8N orquestra OpenAI, Pinecone e Google Sheets

---

## P

### **Pinecone**
- **Definição:** Serviço de banco de dados vetorial otimizado para aplicações de IA
- **No contexto do workshop:** Armazena embeddings para busca semântica
- **Características:** Alta performance, escalabilidade, APIs REST

### **Prompt**
- **Definição:** Instrução ou entrada fornecida a um modelo de IA
- **No contexto do workshop:** Comando para o AI Agent sobre como se comportar
- **Exemplo:** "Você é Marley, assistente de Junior Dread..."

### **Prompt Engineering**
- **Definição:** Arte e ciência de criar prompts eficazes para LLMs
- **No contexto do workshop:** Otimizar instruções para obter respostas precisas
- **Técnicas:** Few-shot learning, chain-of-thought, role-playing

---

## Q

### **Query**
- **Definição:** Pergunta ou solicitação feita a um sistema
- **No contexto do workshop:** Mensagem do usuário para o chatbot
- **Processamento:** Análise, busca na base de conhecimento, geração de resposta

### **Q&A (Question & Answer)**
- **Definição:** Sistema de perguntas e respostas
- **No contexto do workshop:** Funcionalidade principal do chatbot
- **Implementação:** RAG para respostas baseadas em conhecimento

---

## R

### **RAG (Retrieval-Augmented Generation)**
- **Definição:** Técnica que combina busca de informações com geração de texto
- **No contexto do workshop:** Busca dados relevantes antes de gerar respostas
- **Vantagens:** Precisão, factualidade, transparência

### **Retrieval**
- **Definição:** Processo de buscar e recuperar informações relevantes
- **No contexto do workshop:** Consulta à base de conhecimento via Pinecone
- **Métodos:** Busca vetorial, busca por similaridade

### **Response**
- **Definição:** Resposta gerada pelo sistema para uma pergunta do usuário
- **No contexto do workshop:** Texto gerado pelo LLM baseado em dados recuperados
- **Qualidade:** Relevância, precisão, naturalidade

---

## S

### **Similaridade**
- **Definição:** Medida de quão próximos são dois vetores ou conceitos
- **No contexto do workshop:** Comparação de embeddings para encontrar conteúdo relacionado
- **Métricas:** Cosseno, euclidiana, manhattan

### **Semântica**
- **Definição:** Significado e interpretação do conteúdo
- **No contexto do workshop:** Compreensão do contexto das perguntas
- **Aplicação:** Busca inteligente, agrupamento de conceitos

### **Sistema**
- **Definição:** Conjunto de componentes que trabalham juntos para uma função específica
- **No contexto do workshop:** Arquitetura completa do chatbot
- **Componentes:** Trigger, AI Agent, Memory, Vector Store

---

## T

### **Token**
- **Definição:** Unidade básica de processamento em LLMs
- **No contexto do workshop:** Palavras, partes de palavras ou caracteres especiais
- **Considerações:** Limite de tokens, custo por token

### **Training**
- **Definição:** Processo de ensinar um modelo com dados
- **No contexto do workshop:** LLMs pré-treinados que podem ser fine-tuned
- **Fases:** Pré-treinamento, fine-tuning, validação

### **Tools**
- **Definição:** Ferramentas especializadas que um agente de IA pode usar
- **No contexto do workshop:** gwan_q, Google Sheets, APIs externas
- **Funcionalidades:** Busca, armazenamento, processamento

---

## U

### **User Experience (UX)**
- **Definição:** Experiência geral do usuário ao interagir com um sistema
- **No contexto do workshop:** Interface e fluidez do chatbot
- **Fatores:** Facilidade de uso, velocidade, precisão

### **User Interface (UI)**
- **Definição:** Interface através da qual usuários interagem com um sistema
- **No contexto do workshop:** Chat interface, configurações do N8N
- **Design:** Intuitivo, responsivo, acessível

---

## V

### **Vector**
- **Definição:** Representação numérica multidimensional de dados
- **No contexto do workshop:** Embeddings que representam texto
- **Características:** Dimensionalidade, similaridade, operações matemáticas

### **Vector Store**
- **Definição:** Sistema especializado em armazenar e buscar vetores
- **No contexto do workshop:** Pinecone para armazenar embeddings
- **Funcionalidades:** Indexação, busca por similaridade, escalabilidade

---

## W

### **Workflow**
- **Definição:** Sequência de passos ou operações para executar uma tarefa
- **No contexto do workshop:** Fluxo de processamento no N8N
- **Componentes:** Nodes, conexões, triggers, ações

### **Webhook**
- **Definição:** Método de comunicação entre sistemas via HTTP
- **No contexto do workshop:** Trigger para receber mensagens do chat
- **Funcionamento:** POST request com dados do evento

---

## 🔗 Referências e Recursos

### **Documentação Oficial**
- [N8N Documentation](https://docs.n8n.io/)
- [OpenAI API Reference](https://platform.openai.com/docs)
- [Pinecone Documentation](https://docs.pinecone.io/)

### **Artigos e Tutoriais**
- [Understanding RAG](https://arxiv.org/abs/2005.11401)
- [Vector Similarity Search](https://www.pinecone.io/learn/vector-similarity-search/)
- [Prompt Engineering Guide](https://www.promptingguide.ai/)

### **Comunidades**
- [N8N Community](https://community.n8n.io/)
- [OpenAI Community](https://community.openai.com/)
- [PUC Angels Network](https://pucangels.com.br/)

---

## 📝 Notas de Uso

- **Durante o workshop:** Use como referência rápida para conceitos
- **Após o workshop:** Material de estudo e consulta
- **Personalização:** Adapte exemplos para seu contexto específico
- **Atualizações:** Mantenha atualizado com novas tecnologias

---

*Este glossário foi criado para o workshop "Criando Chatbot de IA com N8N" da PUC Angels. Para dúvidas ou sugestões, entre em contato com Pedro Almeida.*

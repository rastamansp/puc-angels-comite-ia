# 🚀 Workshop: Criando Chatbot de IA com N8N

## 📋 Sobre o Workshop

**Tema:** Criando Chatbot de IA com N8N  
**Organização:** PUC Angels - Aceleradora de Startups  
**Instituição:** Pontifícia Universidade Católica do Brasil  
**Data:** 14/08/2024 às 19h  
**Formato:** Online via Google Meet  
**Duração:** 1h30min (1h de conteúdo + 30min Q&A)  
**Link:** [https://meet.google.com/ryv-quwh-bhy?authuser=0](https://meet.google.com/ryv-quwh-bhy?authuser=0)

## 🎯 Objetivos do Workshop

- **Compreender** os fundamentos de chatbots de IA e automação
- **Explorar** a plataforma N8N para automação de workflows
- **Implementar** um chatbot funcional com integração de IA
- **Integrar** ferramentas externas (Azure OpenAI, Pinecone, Google Sheets, Notion)
- **Aplicar** conceitos práticos em um projeto real

## 🎓 Público-Alvo

- Empreendedores e startups da PUC Angels
- Desenvolvedores interessados em IA e automação
- Profissionais de marketing e atendimento ao cliente
- Estudantes de tecnologia e inovação
- Qualquer pessoa interessada em chatbots e automação

## 📚 Pré-requisitos

- Conhecimento básico de programação (recomendado)
- Familiaridade com APIs e integrações (opcional)
- Conta no GitHub (para versionamento)
- Acesso à internet durante o workshop

## 🔧 Configuração Prévia dos Serviços

**⚠️ IMPORTANTE:** Como o workshop será online e hands-on, é **OBRIGATÓRIO** criar as contas nos serviços abaixo **ANTES** do evento para acompanhar as demonstrações práticas.

### **1. Azure OpenAI (Obrigatório)**
- **Objetivo:** Gerar token de acesso à API de IA
- **Passos:**
  1. Acesse [portal.azure.com](https://portal.azure.com)
  2. Crie um novo recurso "OpenAI"
  3. Configure a região e plano de preços
  4. Anote a **chave da API** e **endpoint**
- **Tempo estimado:** 15-20 minutos
- **Custo:** Plano gratuito disponível

### **2. N8N (Obrigatório)**
- **Objetivo:** Criar workflows junto com o instrutor
- **Passos:**
  1. Acesse [n8n.io](https://n8n.io)
  2. Clique em "Get Started for Free"
  3. Crie uma conta gratuita
  4. Faça login e acesse o dashboard
- **Tempo estimado:** 5 minutos
- **Custo:** Gratuito para uso básico

### **3. Pinecone (Obrigatório)**
- **Objetivo:** Criar index para consultas RAG no Agente de IA
- **Passos:**
  1. Acesse [pinecone.io](https://pinecone.io)
  2. Clique em "Get Started Free"
  3. Crie uma conta gratuita
  4. Crie um novo **index** (anote o nome)
  5. Anote a **API Key** e **Environment**
- **Tempo estimado:** 10-15 minutos
- **Custo:** Plano gratuito disponível

### **4. Notion (Opcional mas Recomendado)**
- **Objetivo:** Integração com N8N para leitura/escrita de documentos
- **Passos:**
  1. Acesse [notion.so](https://notion.so)
  2. Crie uma conta gratuita
  3. Crie um workspace
  4. Crie um documento de teste
  5. **Crie uma integração:** Acesse [https://www.notion.so/profile/integrations/form/new-integration](https://www.notion.so/profile/integrations/form/new-integration)
  6. Configure a integração:
     - Nome: "N8N Chatbot Integration"
     - Descrição: "Integração para chatbot com N8N"
     - Selecione o workspace criado
     - Anote o **Internal Integration Token**
  7. Compartilhe o documento com a integração (será explicado no workshop)
- **Tempo estimado:** 15-20 minutos
- **Custo:** Gratuito para uso básico

### **📋 Checklist de Preparação**
- [ ] Conta Azure OpenAI criada e API Key anotada
- [ ] Conta N8N criada e acessível
- [ ] Conta Pinecone criada com index configurado
- [ ] Conta Notion criada (opcional)
- [ ] **Integração Notion criada e Internal Integration Token anotado**
- [ ] Todas as credenciais organizadas e acessíveis
- [ ] Conexão de internet estável para o workshop

## 🛠️ Ferramentas e Tecnologias

### Plataforma Principal
- **N8N** - Plataforma de automação de workflows

### Serviços de IA
- **Azure OpenAI** - Modelos de linguagem e embeddings
- **Pinecone** - Banco de dados vetorial

### Integrações
- **Google Sheets** - Armazenamento de dados
- **Notion** - Leitura e escrita de documentos
- **Sistemas de memória** - Gerenciamento de contexto

## 📖 Conteúdo Programático

### **📱 Formato Online e Hands-on**
- **Workshop 100% prático** - Todos os participantes criarão junto com o instrutor
- **Formato colaborativo** - Compartilhamento de tela e acompanhamento em tempo real
- **Suporte individual** - Dúvidas respondidas durante a execução
- **Material compartilhado** - Todos os recursos disponíveis para download

### **Apresentação e Introdução (5min)**
- Apresentação do instrutor Pedro Almeida
- Visão geral do workshop e objetivos
- Contexto da PUC Angels e inovação
- Verificação de contas e configurações dos participantes

### **Módulo 1: Fundamentos e N8N (25min)**
- Introdução aos chatbots de IA
- Visão geral da plataforma N8N
- **Linha do Tempo de Conceitos Fundamentais:**
  - **RAG (Retrieval-Augmented Generation)** - Combinação de busca e geração
  - **Embeddings** - Representação vetorial de texto
  - **Memória de Histórico de Chat** - Contexto de conversas
  - **Banco de Dados Vetorial** - Armazenamento de embeddings
  - **Consulta Vetorial** - Busca por similaridade semântica
  - **Tools de Agente de IA** - Ferramentas especializadas
  - **LLMs (Large Language Models)** - Modelos de linguagem
  - **Prompt Engineering** - Otimização de instruções
- Arquitetura de chatbots inteligentes
- Casos de uso e aplicações práticas

### **Módulo 2: Construindo o Chatbot (30min)**
- Configuração rápida do ambiente
- Criação do workflow principal
- Implementação do trigger de mensagens
- Configuração do agente de IA e integrações
- Demonstração prática do chatbot "Marley"

### **Sessão de Perguntas e Respostas (30min)**
- Dúvidas sobre o conteúdo apresentado
- Discussão sobre casos de uso específicos
- Networking e troca de experiências
- Próximos passos e recursos adicionais

## 🏗️ Arquitetura do Projeto

### Componentes Principais
1. **Trigger Node** - Recebimento de mensagens
2. **AI Agent** - Orquestração e inteligência
3. **Chat Model** - Processamento de linguagem natural
4. **Memory System** - Gerenciamento de contexto
5. **Vector Store** - Busca semântica
6. **External Tools** - Integrações específicas

## 🧠 Conceitos Fundamentais da IA

### **📅 Ordem Cronológica de Apresentação (15min)**

#### **1. RAG (Retrieval-Augmented Generation) - 2min**
- **Definição:** Técnica que combina busca de informações com geração de texto
- **Funcionamento:** Busca dados relevantes antes de gerar respostas
- **Vantagem:** Respostas mais precisas e baseadas em fatos
- **Aplicação:** Chatbots que consultam bases de conhecimento

#### **2. Embeddings - 2min**
- **Definição:** Representação numérica (vetorial) de texto
- **Funcionamento:** Converte palavras/frases em números para comparação
- **Vantagem:** Permite busca por similaridade semântica
- **Aplicação:** Pinecone, OpenAI Embeddings

#### **3. Memória de Histórico de Chat - 2min**
- **Definição:** Sistema que mantém contexto das conversas
- **Funcionamento:** Armazena interações anteriores
- **Vantagem:** Chatbot "lembra" do que foi discutido
- **Aplicação:** Simple Memory no N8N

#### **4. Banco de Dados Vetorial - 2min**
- **Definição:** Sistema especializado em armazenar e buscar embeddings
- **Funcionamento:** Indexa vetores para busca rápida por similaridade
- **Vantagem:** Busca eficiente em grandes volumes de dados
- **Aplicação:** Pinecone Vector Store

#### **5. Consulta Vetorial - 2min**
- **Definição:** Busca por similaridade entre vetores de texto
- **Funcionamento:** Compara embeddings para encontrar conteúdo relacionado
- **Vantagem:** Encontra informações mesmo com palavras diferentes
- **Aplicação:** Busca semântica na base de conhecimento

#### **6. Tools de Agente de IA - 2min**
- **Definição:** Ferramentas especializadas que o agente pode usar
- **Funcionamento:** Extendem as capacidades do chatbot
- **Vantagem:** Permite ações específicas (Google Sheets, APIs)
- **Aplicação:** gwan_q, sheets, integrações externas

#### **7. LLMs (Large Language Models) - 2min**
- **Definição:** Modelos de linguagem treinados com grandes volumes de texto
- **Funcionamento:** Processam e geram texto natural
- **Vantagem:** Compreensão e geração de linguagem humana
- **Aplicação:** Azure OpenAI GPT, Claude, modelos de chat

#### **8. Prompt Engineering - 1min**
- **Definição:** Arte de criar instruções eficazes para LLMs
- **Funcionamento:** Estrutura comandos para obter respostas desejadas
- **Vantagem:** Melhora qualidade e relevância das respostas
- **Aplicação:** Instruções para o AI Agent

### **💡 Dicas de Apresentação para Cada Conceito**

#### **RAG (2min)**
- **Exemplo prático:** "Imagine que você pergunta sobre um produto e o chatbot busca na base de conhecimento antes de responder"
- **Analogia:** "Como um assistente que consulta um manual antes de dar uma resposta"
- **Demonstração:** Mostrar como o chatbot "Marley" busca informações sobre Junior Dread

#### **Embeddings (2min)**
- **Exemplo prático:** "Palavras como 'carro' e 'automóvel' geram vetores similares"
- **Analogia:** "Como um tradutor que converte palavras em coordenadas numéricas"
- **Demonstração:** Mostrar como o OpenAI converte texto em números

#### **Memória de Chat (2min)**
- **Exemplo prático:** "O chatbot lembra que você já perguntou sobre shows"
- **Analogia:** "Como uma conversa com alguém que se lembra do que vocês falaram antes"
- **Demonstração:** Mostrar o Simple Memory no N8N

#### **Banco Vetorial (2min)**
- **Exemplo prático:** "Pinecone armazena milhões de embeddings para busca rápida"
- **Analogia:** "Como um índice de livro, mas para encontrar conteúdo similar"
- **Demonstração:** Mostrar a interface do Pinecone

#### **Consulta Vetorial (2min)**
- **Exemplo prático:** "Buscar por 'música reggae' encontra 'Junior Dread' mesmo sem mencionar o nome"
- **Analogia:** "Como encontrar pessoas com interesses similares em uma rede social"
- **Demonstração:** Mostrar busca semântica na base de dados

#### **Tools de IA (2min)**
- **Exemplo prático:** "O chatbot pode salvar contatos no Google Sheets e criar documentos no Notion automaticamente"
- **Analogia:** "Como dar superpoderes ao chatbot para ações específicas"
- **Demonstração:** Mostrar integração com Google Sheets e Notion

#### **LLMs (2min)**
- **Exemplo prático:** "Azure OpenAI GPT-4 entende e responde em português naturalmente"
- **Analogia:** "Como ter uma conversa com alguém muito inteligente e bem informado"
- **Demonstração:** Mostrar resposta do Azure OpenAI no N8N

#### **Prompt Engineering (1min)**
- **Exemplo prático:** "Instruções claras geram respostas mais precisas"
- **Analogia:** "Como fazer uma pergunta bem formulada para obter a resposta certa"
- **Demonstração:** Mostrar o prompt do AI Agent



### Fluxo de Dados
```
Mensagem → AI Agent → Processamento → Resposta
    ↓           ↓           ↓
  Trigger  Azure OpenAI  Pinecone
    ↓           ↓           ↓
  N8N      Chat Model  Vector DB
    ↓           ↓           ↓
  Notion   Google Sheets  Memory
```

## 📁 Estrutura do Projeto

```
workshop-chatbot-n8n/
├── README.md
├── prompt.md
├── slides/
│   ├── modulo1-fundamentos.md
│   ├── modulo2-configuracao.md
│   ├── modulo3-construcao.md
│   ├── modulo4-avancado.md
│   └── modulo5-deploy.md
├── exemplos/
│   ├── workflow-basico.json
│   ├── workflow-avancado.json
│   └── configuracao.env
├── exercicios/
│   ├── exercicio1-setup.md
│   ├── exercicio2-workflow.md
│   └── exercicio3-integracao.md
└── recursos/
    ├── links-uteis.md
    ├── troubleshooting.md
    └── next-steps.md
```

## 🎯 Projeto Prático: Chatbot "Marley"

### Descrição
Implementação de um chatbot profissional chamado **Marley** para gerenciamento de negócios do artista brasileiro Junior Dread.

### Funcionalidades
- **Consultas de IA** via `gwan_q` (base de conhecimento)
- **Armazenamento** de contatos via Google Sheets
- **Gestão de documentos** via Notion
- **Memória contextual** para conversas
- **Busca semântica** na base de dados

### Casos de Uso
- Agendamento de shows
- Contatos de imprensa
- Informações sobre o artista
- Gestão de parcerias
- **Gestão de documentos** (contratos, propostas, materiais promocionais)
- **Base de conhecimento** estruturada no Notion

## 📋 Checklist de Preparação

### Antes do Workshop
- [ ] Contas criadas (Azure OpenAI, Pinecone, N8N, Notion)
- [ ] N8N acessível via web
- [ ] APIs configuradas e testadas
- [ ] Materiais preparados
- [ ] Ambiente de desenvolvimento configurado
- [ ] Link do Google Meet salvo e testado

### Durante o Workshop
- [ ] Apresentação dos conceitos
- [ ] Demonstração prática
- [ ] Exercícios hands-on
- [ ] Resolução de dúvidas
- [ ] Feedback dos participantes

### Após o Workshop
- [ ] Compartilhamento de materiais
- [ ] Acesso aos recursos
- [ ] Suporte pós-workshop
- [ ] Avaliação e feedback

## 🔗 Recursos Adicionais

### Documentação
- [N8N Documentation](https://docs.n8n.io/)
- [Azure OpenAI Documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/)
- [Pinecone Documentation](https://docs.pinecone.io/)
- [Notion API Documentation](https://developers.notion.com/)

### Comunidade
- [N8N Community](https://community.n8n.io/)
- [PUC Angels Network](https://pucangels.com.br/)

### 📚 Materiais do Workshop
- [Glossário de IA](glossario-ia.md) - Conceitos e definições completas
- [Prompt do Chatbot](prompt.md) - Instruções para o AI Agent

## 📞 Suporte e Contato

- **Organizador:** Pedro Almeida
- **Email:** pedro.almeida@pucangels.org
- **GitHub:** [@rastamansp](https://github.com/rastamansp)
- **LinkedIn:** [Pedro Almeida](https://www.linkedin.com/in/pedro-halmeida/)

## 📝 Notas para o Instrutor

### Pontos de Atenção
- Verificar conectividade de internet
- Ter contas de backup para as APIs
- Preparar exemplos de fallback
- Cronometrar rigorosamente: 5min + 25min + 30min + 30min
- Manter o foco no conteúdo essencial para o tempo limitado

### Adaptações
- Manter o cronograma rigoroso devido ao tempo limitado
- Focar em demonstrações práticas e casos de uso reais
- Encorajar perguntas durante a sessão de Q&A
- Fornecer materiais complementares para estudo posterior
- Priorizar o que é essencial para entender e implementar um chatbot básico

---

**🎉 Prepare-se para uma jornada incrível no mundo da automação e IA!**

*Este workshop foi desenvolvido para a PUC Angels, combinando teoria e prática para criar soluções reais de chatbot inteligente.*

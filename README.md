# 🤖 Chatbot Institucional da FPM – Sentinela Caveira

💼 **Faculdade de Princípios Militares – FPM**  
📚 **Curso:** Sistemas de Informação  
📘 **Disciplina:** Inteligência Artificial Aplicada  
📌 **Projeto:** Chatbot Institucional com Gradio + IA (Unify)  
👨‍🏫 **Professor:** Dr. Jonas Augusto Kunzler  
👨‍🎓 **Aluno:** José Tayllan Pinto Almeida  
📅 **Período:** 2025/1  
📆 **Data de Entrega:** 15/06/2025  

---

## 🎯 Objetivo do Projeto
Este notebook implementa um **assistente virtual inteligente** para a Faculdade de Princípios Militares (FPM), com os seguintes propósitos:

- Automatizar o atendimento às dúvidas frequentes de alunos e interessados.  
- Oferecer uma interface acessível e personalizada via **Gradio**.  
- Permitir **atualização dinâmica** da base de conhecimento pela secretaria.  
- Integrar **modelos de linguagem avançados** (Claude/GPT via UnifyAI) com fallback inteligente.  

---

## 📂 Componentes Principais
- **ChatBot** → classe central com lógica de resposta, memória de conversa e integração com IA.  
- **`gradio_chatbot_interface()`** → interface interativa para usuários em ambiente web.  
- **`painel_secretaria()`** → painel administrativo para registrar novas respostas manualmente.  
- **`base_conhecimento_manual.json`** → base local com perguntas/respostas validadas.  
- **`perguntas_sem_resposta.json`** → log de perguntas que não foram respondidas pela base.  

---

## 👥 Público-Alvo
- Estudantes e interessados na FPM  
- Equipe da secretaria e coordenação  
- Professores e avaliadores do projeto  

---

## 🌱 Melhorias e Implementações Futuras
### 🔐 Autenticação e Acesso
- Cadastro de múltiplos usuários (secretaria, coordenação, TI).  
- Controle de permissões por função.  

### 📊 Dashboard de Estatísticas
- Quantidade de perguntas respondidas por dia/semana.  
- Principais tópicos mais perguntados (ex: cursos, bolsas, contato).  

### 🔎 Busca Inteligente
- Sugestões automáticas ao digitar.  
- Uso de **embeddings** para comparação semântica.  

### 📤 Exportação de Dados
- Download das perguntas sem resposta (.csv / .xlsx).  
- Exportação da base manual para backup ou migração.  

### 🧠 Aprendizado Contínuo
- Atualização automática da base com aprovações humanas.  
- Treinamento incremental com base nos logs.  

### 🗣️ Suporte a Voz
- Entrada por microfone (**STT** – Speech to Text).  
- Resposta falada (**TTS** – Text to Speech).  

### 📱 Versão Mobile
- Layout responsivo focado em uso por celular.  
- **PWA (Progressive Web App)** para acesso como aplicativo.  

### 🔁 Integração com Mensageiros
- Conexão com API oficial do **WhatsApp Business**.  
- Canal alternativo de atendimento com **Telegram**.  

### 📂 Categorização e Filtros
- Classificação automática das perguntas (ex: curso, bolsa, estrutura).  
- Filtros no painel da secretaria para facilitar gestão.  

### 🌐 Modo Multilíngue
- Suporte a **Português-Inglês** com tradutor automático.  
- Detecção automática de idioma.  

---

## 📌 Conclusão
Essas ideias abrem caminho para transformar o **Sentinela Caveira** em uma **plataforma inteligente de atendimento educacional**, com foco em **automação, eficiência e inovação institucional**.  

📍 **Responsável:** José Tayllan Pinto Almeida

# 💰 App de Finanças Pessoais com Vibe Coding

Este projeto foi desenvolvido como um Desafio de Projeto da DIO de Vibe Coding utilizando e o Lovable e Copilot Web. A proposta é criar um aplicatio de organização financeira pessoal baseado em interações em linguagem natural.

---

## 📄 PRD Refinado no Copilot Web

```markdown
# PRD – Aplicativo de Finanças Pessoais via Conversa

## CONTEXTO
Este documento descreve os requisitos do produto **Aplicativo de Finanças Pessoais via Conversa**, cujo objetivo é permitir o controle financeiro pessoal por meio de interações em linguagem natural.
O produto propõe substituir interfaces tradicionais baseadas em formulários, planilhas e múltiplas telas por uma experiência conversacional acessível, simples e inclusiva.

## PROBLEMA
Usuários enfrentam dificuldades para manter o controle financeiro utilizando aplicativos tradicionais devido a:
- Excesso de entrada manual de dados  
- Curva de aprendizado elevada  
- Interfaces complexas e pouco acessíveis  
- Falta de personalização conforme o perfil do usuário  
- Baixo engajamento ao longo do tempo  

Esses fatores impactam negativamente pessoas com menor familiaridade tecnológica e usuários com limitações visuais, motoras ou cognitivas.

## OBJETIVOS DO PRODUTO
### 🎯 Objetivo principal
Permitir que usuários organizem e acompanhem suas finanças pessoais utilizando linguagem natural, com o mínimo de esforço cognitivo e operacional.

### 🎯 Objetivos secundários
- Aumentar a adesão e recorrência no controle financeiro
- Garantir acessibilidade desde o MVP
- Oferecer insights financeiros claros e acionáveis
- Reduzir a fricção na entrada de dados financeiros

## 👥 PÚBLICO-ALVO
O produto é destinado a:
- Jovens adultos iniciando a vida financeira
- Usuários com pouca familiaridade com aplicativos financeiros
- Pessoas com limitações visuais, motoras ou cognitivas
- Usuários que priorizam simplicidade, clareza e rapidez

## ⚙️ ESCOPO FUNCIONAL
### Funcionalidades principais
- Registro de despesas e receitas via chat em linguagem natural  
- Classificação automática de transações por categoria  
- Criação, acompanhamento e alerta de metas financeiras  
- Agente Financeiro com regras para recomendações básicas  
- Visualização de relatórios financeiros simplificados  
- Dashboard resumido com indicadores principais  
- Listagem de transações com filtros simples  
- Sugestões de economia baseadas no histórico do usuário  

### 🚫 Fora de escopo (MVP)
- Integração bancária automática  
- Planejamento financeiro avançado  
- Investimentos e produtos financeiros complexos  
- Inteligência preditiva avançada  

## 🛡️ REQUISITOS NÃO FUNCIONAIS
### Acessibilidade
- Alto contraste e tipografia legível  
- Compatibilidade com leitores de tela  
- Navegação compatível com comandos por voz  
- Fluxos simples e previsíveis  

### Usabilidade
- Baixa carga cognitiva  
- Linguagem clara e não técnica  
- Feedback imediato para ações do usuário  

### Performance
- Respostas do chat em tempo próximo ao real  
- Persistência rápida de dados  

### Segurança
- Armazenamento seguro de dados financeiros  
- Controle de acesso por autenticação  
- Conformidade com boas práticas de privacidade  

## 🏗️ ARQUITETURA DE ALTO NÍVEL
### Componentes principais
- Interface Conversacional (Chat UI)  
- Processador de Linguagem Natural (NLP)  
- Motor de Classificação de Transações  
- Módulo de Metas e Alertas  
- Agente Financeiro baseado em regras  
- Banco de dados relacional ou NoSQL leve  

### Fluxo simplificado
- Usuário envia mensagem em linguagem natural  
- NLP interpreta intenção e entidades  
- Motor classifica a transação  
- Dados são persistidos  
- Agente Financeiro avalia regras  
- Resposta é apresentada ao usuário

## 🚀 MVP (Produto Mínimo Viável)
### Telas
- Tela de Conversa (Chat)  
- Dashboard Resumido  
- Tela de Metas  
- Tela de Relatórios Simples
  
### Funcionalidades obrigatórias
- Registro manual via chat  
- Classificação automática básica  
- Visualização de saldo e gastos por categoria  
- Alertas simples de metas  

## 📊 MÉTRICAS DE SUCESSO
- Taxa de engajamento semanal  
- Percentual de transações classificadas corretamente  
- Taxa de criação e acompanhamento de metas  
- Feedback qualitativo sobre clareza e acessibilidade  
- Retenção de usuários no período piloto  

## 🔄 VALIDAÇÃO E ITERAÇÃO
- Testes com grupo piloto diverso  
- Coleta de feedback contínuo  
- Ajustes com foco em acessibilidade e clareza  
- Iterações rápidas com base nas métricas definidas  

## ⚠️ RISCOS E MITIGAÇÕES
- Erros de interpretação de linguagem natural  
  - Mitigação: fallback manual e confirmação do usuário  
- Baixo engajamento inicial  
  - Mitigação: onboarding guiado via chat  
- Barreiras de acessibilidade não identificadas  
  - Mitigação: testes frequentes com usuários diversos
```
 
## 💻 Interações com o Lovable
> Criação do App de Finanças Pessoais com base no PRD.

> Ajuste da categoria "Salário" para interpretar corretamente valores como 1.500,00.

> Implementação da tela de cadastro com login e senha básico.

---
 
## 🎯 Resultado final:

Acesse o protótipo funcional no Lovable:  
**https://minhasfinancasfacil.lovable.app/auth**

<img width="708" height="768" alt="image" src="https://github.com/user-attachments/assets/afb36e64-77d8-4d23-be01-0f4305aa6750" />

---

## 📱 Funcionalidades do App
### 💬 Tela de Conversa (Chat)
Registro de gastos em linguagem natural.

Respostas automáticas do Agente Financeiro.

Experiência conversacional como núcleo do aplicativo.

### 📊 Dashboard Resumido
Exibe saldo real, receitas e despesas.

Cards simples e intuitivos.

Design universal: contraste adequado, texto legível e navegação acessível.

### 🧾 Transações Recentes
Lista organizada de despesas e receitas com categorias.

Histórico acessível sem esforço manual.

### 🎯 Metas Financeiras
Definição de objetivos.

Barra de progresso para acompanhar evolução.

Alertas e recomendações para engajamento.

### 📈 Relatórios Simples
Gráficos básicos (pizza e barras).

Insights rápidos sobre gastos.

Linguagem acessível.

### 💡 Sugestões de Economia
Recomendações personalizadas.

Dicas práticas e educativas.

## Síntese:  
O aplicativo funciona como um assistente financeiro conversacional, que organiza despesas e receitas, mostra relatórios simples, ajuda a definir metas e dá dicas de economia. Foi projetado com Design Universal, garantindo boa experiência para o maior número possível de usuários.

---

## 🧠 Reflexão

### O que funcionou bem?
O refinamento do PRD feito no Copilot ajudou muito, sendo necessário apenas pequenos ajustes em poucas interações.

### O que não funcionou como o esperado?
Por ser gratuito, as interações são limitadas. Foi necessário concentrar ajustes em uma única interação para não perder rapidamente as interações disponíveis.

### O que aprendeu sobre conversar com IAs?
Aprendi que conversar com uma IA é parecido com conversar com uma pessoa: quanto mais detalhes e clareza você fornece, melhor é a interação e o resultado gerado.

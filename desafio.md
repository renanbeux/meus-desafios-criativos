# 🤖 Prompt de Engenharia: Planej.ai

> Este documento contém o prompt principal estruturado para gerar o escopo e a lógica do **Planej.ai**, um Educador Financeiro Inteligente. 

---

## 🎭 Papel
Atue como um **Especialista em Educação Financeira Digital** e **Arquiteto de Software Frontend**.

## 🎯 Objetivo
Crie a proposta conceitual e o escopo do **Planej.ai**, uma aplicação web inteligente desenvolvida em `React`, `TypeScript` e `IA Generativa`, focada em jovens de 15 a 35 anos. O sistema atuará como um Educador Financeiro Inteligente que recebe informações de uma simulação financeira e gera insights personalizados para a pessoa usuária.

## 🛑 O Problema
O usuário-alvo sofre de **"neblina financeira"**: não sabe exatamente quanto tem na conta, não tem controle de quanto gastou e não faz ideia de quanto pode investir.

## ⚙️ As Funcionalidades
O **Planej.ai** deve organizar a vida financeira do usuário em 4 pilares:

1. **💵 Visão de Renda:** Mostrar de forma clara e visual quanto a pessoa ganha no mês.
2. **📉 Controle de Gastos:** Um fluxo simples e sem atrito para inserção e acompanhamento de despesas.
3. **🔮 Simulação Financeira:** Formulário interativo para receber os dados do usuário, projetando metas de economia, investimentos e objetivos de compra *(ex: viagens, eletrônicos)*.
4. **🧠 Geração de Insights (Motor de IA):** Análise dos dados da simulação para entregar recomendações exclusivas com base na renda, idade e objetivos, criando planos de melhoria.

## 🗣️ Regras de Comunicação e Tom de Voz
*(Aplicável aos textos da interface e às respostas do motor de IA)*

- Seja humano, amigável, acolhedor e altamente prático.
- Evite **qualquer** jargão técnico financeiro (como CDI, Selic, Liquidez) sem antes explicar com uma analogia simples do dia a dia.
- As sugestões da IA devem ser entregues em formato de **listas curtas** e **exemplos visuais/práticos**.

---

## 📤 Formato de Saída Exigido
Estruture a sua resposta utilizando rigorosamente os seguintes tópicos:

### 1. Visão Geral do Planej.ai
Resumo da proposta de valor com foco absoluto na experiência do usuário.

### 2. Detalhamento dos Pilares
Explique como os 4 pilares descritos acima funcionarão na prática.

### 3. Exemplo Prático de Insight Gerado
Faça uma simulação exata de como a IA do **Planej.ai** responderia a um usuário real:
> *Perfil do teste: Um jovem de 22 anos que inseriu na simulação o desejo de comprar um celular novo, mas cujo controle de gastos apontou um consumo altíssimo com aplicativos de delivery.*

### 4. Proposta para o Frontend (React + TS)
Apresente de **3 a 5 sugestões** de componentes interativos e visuais *(ex: bibliotecas de gráficos, elementos de gamificação, microinterações de estado, skeletons)* que tirem proveito de `React` e `TypeScript` para tornar a aplicação atraente, moderna e funcional.
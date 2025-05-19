# 🚀 Desafio Técnico — Cientista de Dados Sênior · Doc9

Bem-vindo(a) ao desafio técnico para a posição de Cientista de Dados Sênior na Doc9!

Este desafio tem como objetivo avaliar sua capacidade analítica, raciocínio estratégico e domínio técnico a partir de um cenário realista baseado na **logística de audiências jurídicas**, uma das frentes mais críticas e operacionais da Doc9.

---

## 🧭 Contexto do Negócio

A Doc9 é responsável por enviar advogados e prepostos para representar grandes clientes em audiências em **todo o território nacional**. O processo envolve diversos desafios logísticos, como localização geográfica, prazos apertados, qualidade da atuação dos parceiros e cumprimento de SLAs.

Você receberá um conjunto de dados fictício representando as **solicitações de audiência realizadas entre junho e dezembro de 2024**. Esses dados foram estruturados com base na tabela [`solicitacoes_audiencias_logistica`](docs/solicitacoes_audiencias_logistica.md), que contém colunas como tipo de demanda, datas, trocas de parceiros, falhas e outros indicadores operacionais.

Seu papel é analisar esses dados e apoiar os stakeholders da empresa com **insights práticos e recomendações**.

---

## 🎯 Objetivo

Você deverá realizar uma análise exploratória dos dados e gerar recomendações estratégicas e operacionais que ajudem os times de **Produto, Operações e Jurídico** a melhorar a eficiência, reduzir falhas e aumentar a previsibilidade da operação.

---

## 📂 Estrutura Sugerida de Entrega

```
├── README.md                   # Instruções gerais do desafio
├── data/
│ └── solicitacoes_doc9.csv     # Base de dados fictícia
├── notebooks/
│ └── 01_exploracao.ipynb       # Análises exploratórias (obrigatório)
├── reports/
│ └── recomendacoes.pdf         # Apresentação ou relatório executivo (obrigatório)
├── models/
│ └── modelo_churn.py           # Modelo preditivo (opcional)
├── pipeline/
│ └── transformacoes.py         # Scripts de ETL ou transformação (opcional)
├── requirements.txt            # Dependências Python
└── .gitignore
```

---

## 🧪 O Desafio

### 1. 🔍 Exploração de Dados

Com base nos dados disponíveis em `data/solicitacoes_audiencias_logistica.csv`, analise padrões e responda perguntas que surgiram de reuniões com nossos times internos:

#### 📌 Perguntas feitas pelos stakeholders:

- **Produto:**  
  _“Estamos recebendo muitas reclamações sobre trocas de audiencistas. Quais clientes têm maior incidência de trocas ou recusas? Existem padrões por região ou tipo de audiência?”_

- **Operações:**  
  _“Quais fatores mais influenciam para que um parceiro falhe (revelia, ausência ou má atuação)? Conseguimos prever quais solicitações têm maior risco de falha?”_

- **Jurídico:**  
  _“Em quais áreas do direito ocorrem mais problemas? É mais comum em trabalhista ou cível? Existe relação com a antecedência com que o cliente envia os dados?”_

- **Executivo:**  
  _“Se tivéssemos que priorizar melhorias, por onde começar? Que tipo de mudança teria maior impacto na redução de falhas ou aumento da eficiência operacional?”_

---

### 2. 💡 Recomendações Executivas

Monte um **relatório ou apresentação** com os principais achados e recomendações. Seu público são os tomadores de decisão, seja claro, visual e objetivo.

Você pode abordar:

- Segmentação de clientes mais problemáticos
- Indicadores operacionais críticos
- Sugestões para triagem automática de solicitações de risco
- Propostas para ajustes de SLA, alertas ou políticas de substituição de parceiros

---

### 3. 🤖 (Opcional) Modelagem Preditiva

Construa um modelo simples para prever falha na execução da audiência, como:

- Probabilidade de revelia
- Probabilidade de má atuação
- Probabilidade de troca de parceiro

O foco aqui é mais interpretabilidade e aplicabilidade do que performance bruta.

---

### 4. 🛠️ (Opcional) Pipeline de Transformação

Caso deseje, entregue também um script que trate, limpe ou enriqueça os dados brutos e gere uma base analítica consolidada.

---

## 📄 Documentação Técnica

Consulte a descrição completa da tabela e o glossário de campos no arquivo:

📄 [`docs/solicitacoes_audiencias_logistica.md`](docs/solicitacoes_audiencias_logistica.md)

---

## ✅ Critérios de Avaliação

- Clareza e objetividade na análise
- Relevância e aplicabilidade dos insights
- Estrutura e organização do projeto
- Boas práticas de programação e documentação
- Capacidade de gerar valor para as áreas de negócio

---

## 🕒 Prazo

Você terá até **7 dias corridos** para concluir o desafio. Envie um link para o seu repositório público para rhuam.estevam@doc9.com.br

---

## 💬 Dúvidas?

Abra uma [issue](https://github.com/doc9-whom/data-challenge-doc9/issues) no repositório ou envie um e-mail para rhuam.estevam@doc9.com.br.

Boa sorte. Estamos ansiosos para conhecer sua forma de pensar com dados! 🚀

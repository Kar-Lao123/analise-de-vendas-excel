# 📊 Análise de Vendas — BrightMart Retail Co.

## 🎯 O objetivo do projeto

Este projeto foi desenvolvido para analisar o desempenho de uma empresa fictícia de varejo e transformar dados de vendas em informações que poderiam apoiar decisões comerciais.

A principal pergunta que guiou a análise foi:

> **Onde estão os principais pontos positivos e oportunidades de melhoria nas vendas da empresa?**

Em vez de analisar apenas o faturamento, procurei observar diferentes aspectos dos pedidos, como **categorias, regiões, margem e status das vendas**.

---

## 🧠 Como eu pensei o problema

Antes de começar a montar o dashboard, defini algumas perguntas que gostaria de responder:

1. **Quais categorias geram mais vendas e qual é o comportamento de suas margens?**
2. **Quais regiões apresentam melhor e pior desempenho?**
3. **O que acontece com os pedidos que são cancelados ou devolvidos?**
4. **Existe algum padrão que possa indicar uma oportunidade de melhoria?**

Essas perguntas ajudaram a definir quais métricas e análises seriam utilizadas no projeto.

---

## 📊 O que os dados mostraram

A base possui **6.000 transações**, representando aproximadamente **$1,86 milhão em vendas**, com uma **margem de 39,9%**.

### 💻 Electronics representa grande parte das vendas

A categoria **Electronics** apresentou o maior volume de vendas, com aproximadamente **$935 mil**, representando cerca de metade do faturamento analisado.

**Home & Kitchen** apresentou aproximadamente **$327 mil**, enquanto **Sports & Outdoors** ficou em torno de **$283 mil**.

Isso mostra a forte participação de **Electronics** no faturamento, mas também levanta a necessidade de observar outros indicadores além das vendas, como **margem e devoluções**.

### 🌎 Midwest apresenta o menor faturamento entre as regiões

A região **Northeast** apresentou aproximadamente **$547 mil** em vendas, seguida por **West ($504 mil)** e **South ($455 mil)**.

Já a região **Midwest** apresentou aproximadamente **$355 mil**, ficando consideravelmente abaixo das demais.

Esse resultado indica uma oportunidade para investigar fatores como **mix de produtos, desempenho das lojas e comportamento dos pedidos** nessa região.

### 📦 Cancelamentos e devoluções representam uma parcela relevante dos pedidos

Foram identificados **510 pedidos devolvidos** e **303 pedidos cancelados**, totalizando **813 pedidos** nessas duas situações.

Esses pedidos merecem atenção porque representam operações que não tiveram o mesmo resultado de uma venda concluída e podem indicar **custos operacionais ou oportunidades de melhoria no processo**.

---

## 🔎 Um dos principais aprendizados

No início da análise, minha atenção estava muito concentrada nas vendas por categoria.

Por exemplo, ao observar que **Electronics** possuía um faturamento muito superior às outras categorias, a primeira impressão era de que esse era simplesmente o melhor resultado.

Porém, ao cruzar diferentes indicadores, percebi que:

> **Faturamento sozinho não conta toda a história.**

Foi necessário observar também **margem, status dos pedidos e outros indicadores** para conseguir interpretar melhor o desempenho.

Esse foi um dos principais aprendizados do projeto: **uma análise não deve ser baseada em apenas uma métrica.**

---

## 🛠️ Ferramentas utilizadas

* **Microsoft Excel**
* **Power Pivot**
* **DAX**
* **Tabelas Dinâmicas**
* **Dashboard e visualização de dados**

No desenvolvimento do projeto, utilizei medidas DAX, incluindo funções como:

```DAX
COUNTROWS()
DIVIDE()
```

Essas medidas foram utilizadas para criar indicadores e realizar cálculos sobre os dados.

O **Power Pivot** foi utilizado para trabalhar com o **modelo de dados** e as medidas utilizadas no dashboard.

---

## 📁 Dataset

Os dados utilizados são **fictícios e foram gerados para fins de portfólio**, utilizando uma estrutura baseada em um cenário de varejo.

O objetivo do projeto não é representar uma empresa real, mas sim demonstrar o processo de **análise, tratamento e visualização de dados** utilizando Excel.

---

## 🎯 Objetivo profissional

Este projeto faz parte do meu processo de aprendizado em **Análise de Dados e Business Intelligence**.

Meu objetivo é desenvolver cada vez mais minha capacidade de **transformar dados em informações úteis para tomada de decisão**, utilizando ferramentas como:

`Excel` · `Power Pivot` · `DAX` · `Power BI`

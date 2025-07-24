# 🧹 Projeto: Pré-processamento de Dados Empresariais

**Autor:** Alexandre Teixeira  
**Data da última atualização:** Julho de 2025

## 📌 Descrição

Este notebook tem como objetivo realizar o **pré-processamento de múltiplos datasets empresariais**, preparando-os para análises exploratórias, modelagens preditivas ou integrações posteriores. O foco está na **limpeza, normalização, transformação temporal, renomeação de colunas, codificação categórica** e **tratamento de valores ausentes**.

---

## 📂 Datasets Utilizados

Os arquivos utilizados estão localizados em uma pasta de dados e incluem:

- `order_products.csv`
- `orders.csv`
- `products.csv`
- `prices.csv`
- `discounts.csv`
- `special_prices.csv`
- `users.csv`
- `companies.csv`
- `products_approval.csv`
- `homologated_products.csv`

---

## ⚙️ Principais Etapas Realizadas

- 🔍 **Exploração inicial**: análise de tipos, estatísticas descritivas e nulos.
- 🧼 **Remoção de colunas irrelevantes** por dataset.
- 🕓 **Separação de colunas de data e hora**.
- ✏️ **Renomeação padronizada** de colunas para facilitar merges e interpretação.
- 🚫 **Tratamento de valores nulos** com preenchimento adequado (e.g. `cpf`, medianas).
- 🧠 **One-Hot Encoding** de variáveis categóricas como `status`, `tipo_preco` e `tipo_empresa`.
- 🔢 **Conversão de tipos de dados** para inteiros onde necessário.
- 🧩 **Preparação para merges e análises futuras**.

---

## 🧪 Tecnologias e Bibliotecas

- Python 3
- [Pandas](https://pandas.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/) (`SimpleImputer`, `get_dummies`)


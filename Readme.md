# 📊 Projeto M13 EBAC Cientista de Dados: Fundamentos da Descoberta de Dados

Este projeto foi desenvolvido como parte do \*\*Módulo 13 - Fundamentos da Descoberta de Dados\*\* do curso \*\*Profissão Cientista de Dados\*\*. O objetivo principal é aplicar os conceitos estatísticos, de visualização e de análise exploratória de dados (EDA) para extrair insights de uma base de dados real de produtos de um supermercado chileno.

## 🎯 Objetivo do Projeto

O objetivo principal deste projeto é:

1. **Realizar Análise Exploratória de Dados (EDA):** Entender a estrutura do dataset, identificar dados faltantes, tipos de variáveis e realizar limpezas necessárias.
1. **Aplicar Conceitos Estatísticos:** Calcular e interpretar medidas de tendência central, dispersão e distribuição das variáveis.
1. **Gerar Visualizações de Dados:** Criar gráficos relevantes (distribuições, dispersões, etc.) utilizando `Matplotlib` e `Plotly` para facilitar a interpretação dos dados.
1. **Extrair Insights:** Responder a perguntas sobre o catálogo de produtos, preços, distribuição de categorias e outras características relevantes para a gestão do supermercado.

## 💾 Dados

O dataset utilizado contém informações detalhadas sobre o catálogo de produtos de um supermercado, com foco na precificação e nos descontos aplicados.

| Coluna | Descrição |

\| :--- | :--- |

| **Title**| Nome completo do produto. |

| **Marca**| A marca do produto. |

| **Preco_Normal** | O preço em que o produto costuma ser vendido quando não há desconto. |

| **Preco_Desconto** | O preço vendido após o desconto ser aplicado. |

| **Preco_Anterior** | Preço em que era comercializado o produto antes do desconto aplicado |

| **Desconto** | O valor total ou percentual do desconto aplicado. |

---

## 🛠 Tecnologias Utilizadas

O projeto foi implementado em Python e utilizando um ambiente de notebook (Jupyter/Colab).

**Python**
**Pandas**: Para manipulação e análise de dados.
**Matplotlib**: Para visualizações estáticas.
**Plotly Express**: Para visualizações interativas.

---

## 💡 Principais Insights e Descobertas

* Nas categorias com maior desvio padrão ('laticínios', 'beleza e cuidado pessoal', 'congelados'), a média tende a ser maior que a mediana. Isso sugere que, nessas categorias, os preços mais altos puxam a média para cima, indicando uma possível presença de outliers de preços mais elevados.

---

## 🚀 Como Executar o Projeto

Para replicar esta análise, siga os passos abaixo:

1. **Clone o repositório:**

\```bash

git clone https://github.com/pedrosiqueira000/Exercicio-M13-EBAC-Cientista-de-Dados

\```

2. **Instale as dependências necessárias:**

\```bash

pip install pandas matplotlib plotly

\```

3. **Abra o Notebook:**

O projeto principal está contido no arquivo `Profissao\_Cientista\_de\_Dados\_M13\_Projeto.ipynb`. Abra-o em um ambiente Jupyter ou Google Colab.

\```bash

jupyter notebook Profissao\_Cientista\_de\_Dados\_M13\_Projeto.ipynb

\```

## ✒️ Autor

* **Pedro Siqueira de Freitas** - https://www.linkedin.com/in/pedro-siqueira-de-freitas/




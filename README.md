# 🏎️ Porsche Sales Performance Dashboard

[![D3.js](https://img.shields.io/badge/D3.js-v7.0-F9A03F?logo=d3.js&logoColor=white)](https://d3js.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![HTML5/CSS3](https://img.shields.io/badge/HTML5_/_CSS3-Premium_Dark-E34F26?logo=html5&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Um dashboard corporativo interativo e elegante de inteligência de vendas automotivas de alto padrão. O design e a experiência do usuário (UI/UX) foram totalmente inspirados na identidade visual oficial da **Porsche**, adotando uma abordagem *Premium Dark Mode*, minimalista e com alto contraste para proporcionar uma imersão executiva sofisticada.

O projeto resolve do início ao fim o tratamento, a filtragem e a renderização dinâmica de dados transacionais de veículos de luxo (como os lendários 911 Turbo S, GT3, Taycan, Cayenne e Macan) integrando **D3.js** nativo para animações e plotagem de gráficos de alto desempenho.

---

## Link GitHub Pages

https://carlos1681.github.io/dashboard-porsche-ai/

## 📌 Perguntas de Negócio Respondidas

O dashboard foi projetado de forma analítica para sanar dores reais de gestão de frotas e concessionárias, respondendo de imediato a três pilares de BI (*Business Intelligence*):

1. **Principais Modelos Vendidos por Cidade:** Onde estão concentrados os maiores volumes de saída de cada veículo (ex: demanda por SUVs como *Cayenne* vs. Esportivos puros como *911 GT3*).
2. **Ciclo de Distribuição por Ano de Modelo (Model Year):** Identificação de qual ano de modelo teve a maior saída no período histórico analisado, auxiliando na precificação e depreciação de estoque.
3. **Tendências de Consumo Local (Insight de Populares):** Análise de correlação direta entre o método de pagamento preferido, quilometragem média e tíquete médio transacionado por região.

---

## ⚙️ Funcionalidades Operacionais

* **Filtros Multi-Eixo Combinatórios:** Altere dinamicamente qualquer um dos 4 dropdowns superiores e veja o ecossistema de dados se recalcular na hora:
  * 🔀 **Porsche Model** (Modelo específico)
  * 📅 **Model Year** (Ano de fabricação)
  * 📍 **City** (Cidade consumidora)
  * 💳 **Pay Method** (Forma de pagamento)
* **Gráficos Dinâmicos com D3.js:** Gráficos interativos que utilizam escalas reativas, eixos matemáticos e transições fluidas sem a necessidade de bibliotecas pesadas de terceiros (como wrappers baseados em Canvas).
* **Tabela de Insights Granulares:** Uma tabela detalhada que atua como um relatório direto do banco de dados, mostrando Cidade, Modelo, Ano, Método e Preço Formatado no padrão contábil internacional.
* **Layout 100% Responsivo:** Adaptável tanto para telas UltraWide de salas de reunião de diretoria quanto para dispositivos móveis através de um motor de grade CSS fluido.

---

## 🚀 Como Executar o Projeto Localmente

O dashboard é **totalmente auto-contido**, o que significa que ele possui toda a inteligência e os dados embutidos dentro de um único arquivo estático. Não há necessidade de instalar Node.js, NPM ou servidores Apache/Nginx para vê-lo funcionar.

1. Clone este repositório:
   ```bash
   
   git clone git@github.com:Carlos1681/dashboard-porsche-ai.git

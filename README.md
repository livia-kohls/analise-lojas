# Análise de Desempenho de Lojas - Challenge Alura
Este projeto tem como objetivo analisar o desempenho de quatro lojas, identificando qual delas apresenta os piores resultados e deve ser vendida.  
A análise considera indicadores financeiros, operacionais e logísticos obtidos a partir de bases de dados reais.

---

## 📋 Objetivo
O estudo visa determinar, com base em dados, qual loja apresenta menor rentabilidade e menor potencial de crescimento.  
Foram considerados fatores como faturamento, avaliações de clientes, produtos vendidos, custos de frete e padrões geográficos de vendas.

---

## 🧠 Tecnologias Utilizadas
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Google Colab

---

## 📊 Análises Realizadas
1. **Faturamento Total por Loja**  
   - Loja 1: R$ 1.534.509,12 (26,1%)  
   - Loja 2: R$ 1.488.459,06 (25,4%)  
   - Loja 3: R$ 1.464.025,03 (24,9%)  
   - Loja 4: R$ 1.384.497,58 (23,6%)  

2. **Categorias de Produtos**  
   - Todas as lojas possuem maior volume de vendas na categoria **móveis**, indicando falta de diversificação.

3. **Avaliações dos Clientes**  
   - Médias variam entre **3,97** e **4,05**, mostrando boa satisfação geral, mas sem diferenciais expressivos.

4. **Produtos Mais e Menos Vendidos**  
   - Loja 1: Mais — Guarda-roupas / Menos — Celular ABXY  
   - Loja 2: Mais — Iniciando em Programação / Menos — Jogo de Tabuleiro  
   - Loja 3: Mais — Kit Banquetas / Menos — Blocos de Montar  
   - Loja 4: Mais — Cama Box / Menos — Guitarra  

5. **Frete Médio por Loja**  
   - Loja 1: R$ 34,69  
   - Loja 2: R$ 33,62  
   - Loja 3: R$ 33,07  
   - Loja 4: R$ 31,27  

6. **Análise Geográfica**  
   - As vendas se concentram em regiões semelhantes, com leve predominância da Loja 1 em áreas de maior densidade.  
   - Não foram observadas diferenças geográficas relevantes que expliquem o desempenho inferior da Loja 4.

---
 

## 🖼️ Gráficos
Os principais gráficos gerados incluem:
- Gráfico de pizza (faturamento)
- Gráfico de barras (frete médio)
- Mapa de calor (distribuição geográfica)

## 🧾 Conclusão
Após a consolidação dos dados e visualizações, a **Loja 4** foi identificada como a unidade com **pior desempenho geral**.  
Apesar de apresentar o menor custo de frete e uma avaliação razoável de clientes, ela se destacou negativamente em todos os outros aspectos avaliados:

- **Menor faturamento absoluto e percentual**, indicando baixa eficiência operacional.  
- **Dependência excessiva da categoria de móveis**, com pouca variedade de produtos.  
- **Portfólio limitado**, com apenas um item de destaque (Cama Box).  
- **Ausência de vantagens competitivas** em comparação com as demais lojas.  

Com base nesses fatores, recomenda-se que a  **Loja 4** seja vendida, concentrando investimentos nas lojas 1, 2 e 3, que demonstram desempenho financeiro mais sólido e potencial de crescimento superior.

## 📂 Estrutura do Projeto
├── analise_lojas.ipynb
└── README.md

# Elasticidade de Preço e Elasticidade Cruzada com Python

## Sobre o Projeto

Este projeto tem como objetivo analisar o comportamento da demanda de produtos com base em suas variações de preço (**elasticidade-preço**) e também como a variação de preço de um produto pode afetar a demanda de outros (**elasticidade cruzada**). A análise foi feita com dados reais de vendas e preços médios semanais de produtos eletrônicos. O e-commerce escolhido foi Best buy e os produtos analisados são da categoria  "Speaker, Portable, and Bluetooth".

## Objetivos

- Calcular a **elasticidade-preço** dos produtos para entender a sensibilidade da demanda a variações no preço.
- Calcular a **elasticidade-preço cruzada** para identificar relações entre produtos.
- Simular cenários com variações no preço (ex.: desconto de 10%) e estimar o **impacto no faturamento**.
- Gerar um dashboard em Power BI para apresentar os resultados.

## Funcionalidades

- Cálculo da elasticidade-preço com filtro de significância estatística (`p-value < 0.05`);
- Simulação de variações de preço com impacto estimado no faturamento;
- Cálculo da elasticidade cruzada entre pares de produtos;
- Matriz de elasticidade cruzada filtrada por relevância estatística;

## 🛠️ Tecnologias Utilizadas

- Python 3
- Pandas
- NumPy
- Statsmodels
- Matplotlib & Seaborn
- Jupyter Notebook
- Power BI

## Estrutura do Projeto
📁 notebook/

│   ├── elastic_price.ipynb       # Análise da elasticidade-preço

📁 data/

│   ├── dataset.csv               # Dataset com preços e produtos 

📁 result/

│   ├── business_performance      
│   └── cross_price.py  
│   └── df_elasticity.py 
README.md

## Autora

Desenvolvido por @marianaliraf

Este projeto foi desenvolvido exclusivamente para fins educacionais.

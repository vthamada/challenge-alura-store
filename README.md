# Desafio: Análise de Desempenho – Lojas da Alura Store

O Sr. João é proprietário de uma rede fictícia chamada Alura Store, composta por quatro lojas. Ele pretende iniciar um novo empreendimento, mas para isso precisa vender uma de suas lojas atuais. Para tomar uma decisão estratégica baseada em dados, foi conduzida uma análise completa de desempenho das lojas, utilizando métricas como faturamento, avaliações de clientes, produtos vendidos e custo médio de frete. A análise foi realizada utilizando Python, com apoio das bibliotecas Pandas, Matplotlib e Folium.

Este projeto foi desenvolvido como parte do desafio prático do curso de Modelagem de Dados com Python da [Alura + Oracle Next Education](https://www.oracle.com/br/education/oracle-next-education/).

---

## Objetivos do Projeto

- Avaliar o faturamento total de cada loja
- Identificar as categorias de produtos mais e menos vendidas
- Analisar a avaliação média dos clientes
- Apontar os produtos mais e menos vendidos
- Comparar o frete médio por loja
- Visualizar a dispersão geográfica das vendas via mapas de calor

---

## Ferramentas Utilizadas

- [Python 3.x](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Folium](https://python-visualization.github.io/folium/)
- [Google Colab](https://colab.research.google.com/)

---

## Como Executar o Projeto

1. Clone o repositório ou baixe os arquivos.
2. Acesse o notebook [`AluraStoreBr.ipynb`](./AluraStoreBr.ipynb).
3. Abra o notebook no [Google Colab](https://colab.research.google.com/) ou ambiente Jupyter.
4. Execute as células do notebook em ordem.
> Todos os gráficos e mapas serão gerados automaticamente durante a execução.

---

## Estrutura do Projeto

```
├── AluraStoreBr.ipynb # Notebook principal com toda a análise
└── README.md # Documentação do projeto
```
---

## Gráficos dos Dados

- **Faturamento Total por Loja**: Visualização do desempenho financeiro de cada loja.

![Faturamento Total](https://github.com/user-attachments/assets/d821d970-7f9d-40f5-9010-0463b2381c80)


- **Média de Avaliação por Loja**: Comparativo da percepção dos clientes.

![Média de Avaliação](https://github.com/user-attachments/assets/d7ecc0a3-a2bc-40ce-a0ee-bd41fcf9b84d)


- **Mapa de Calor das Vendas**: Distribuição geográfica dos pedidos realizados pelas lojas.

![Mapa de Calor](https://github.com/user-attachments/assets/67efadf8-1263-469e-ace3-e4de556c68ea)

---

## Resultados

Após a análise dos dados, concluiu-se que a Loja 4 é a que apresenta o menor desempenho geral, com destaque negativo nos seguintes critérios:

- Menor faturamento total
- Avaliação média inferior à maioria das lojas

Apesar de possuir o frete médio mais barato, isso não resultou em vantagem competitiva ou maior volume de vendas. Os demais critérios analisados (produtos, categorias, dispersão) não mostraram diferenças significativas entre as lojas.

---

## Conclusão

A recomendação final é que o Senhor João considere vender a Loja 4, pois ela representa a menor performance entre as quatro lojas e possui o menor potencial de crescimento comparado às demais.

---

## Aprendizados Técnicos

- Manipular dados com pandas a partir de múltiplos arquivos CSV
- Construir visualizações com `matplotlib` para tomada de decisão
- Criar mapas interativos com `folium` para análise espacial
- Aplicar lógica de negócios com base em dados estruturados

---

## Autor

Desenvolvido por [Ricardo Hamada](https://github.com/vthamada).

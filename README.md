# Procurement Analytics — Nexa Distribuição Ltda.

## Visão geral

Projeto de análise de dados aplicado à área de Procurement, desenvolvido para investigar gastos com compras, desempenho de fornecedores, oportunidades de economia e riscos de abastecimento.

O projeto utiliza dados simulados de uma empresa fictícia, com o objetivo de demonstrar competências em SQL, Python, análise exploratória e comunicação de resultados de negócio.

## Objetivos

- Analisar a evolução mensal dos gastos com compras.
- Avaliar o desempenho dos fornecedores por meio de indicadores de entrega.
- Identificar oportunidades teóricas de negociação de preços.
- Investigar concentração de gastos e dependência de fornecedores.
- Transformar dados transacionais em recomendações para a gestão de compras.

## Escopo dos dados

- **Período:** janeiro de 2024 a dezembro de 2025.
- **Pedidos de compra:** 8.000.
- **Fornecedores:** 50.
- **Produtos:** 300.
- **Categorias:** 10.
- **Itens de pedidos:** 20.022.
- **Registros de entrega:** 10.367.

Os dados são simulados para fins educacionais e de portfólio.

## Tecnologias utilizadas

- Python
- SQL
- SQLite
- Pandas
- Plotly
- Google Colab

## Principais resultados

- **Gasto analisado:** R$ 142,98 milhões.
- **Pedidos válidos:** 7.772, após excluir pedidos cancelados das análises pertinentes.
- **OTIF global:** 71,69%.
- **Pedidos atrasados:** 23,01%.
- **Economia potencial teórica:** R$ 62,81 milhões.
- **Produtos fora da classificação de baixo risco:** 24, associados a 4,66% do gasto total.

## Metodologia

1. Preparação e validação dos dados.
2. Modelagem e consulta das tabelas com SQL e SQLite.
3. Criação de views analíticas para consolidar indicadores.
4. Análise de gastos, desempenho de fornecedores e pontualidade.
5. Estimativa de oportunidades de economia por produto.
6. Classificação inicial de risco de abastecimento.
7. Construção de gráficos e consolidação das recomendações executivas.

## Principais análises

### Gastos e compras
Evolução mensal dos gastos, volume de pedidos e ticket médio.

### Desempenho de fornecedores
Análise de OTIF, pontualidade, completude, atrasos e fornecedores prioritários.

### Oportunidades de economia
Comparação entre preços médios e menores preços observados por produto.

### Risco de abastecimento
Identificação de produtos com poucos fornecedores e maior exposição financeira.

## Limitações

A economia potencial é uma estimativa exploratória baseada em preços observados. Ela não representa economia garantida e depende da validação de condições comerciais, volumes, especificações, frete e outros fatores.

A classificação de risco é uma triagem inicial baseada nos critérios definidos para a simulação. Ela não substitui uma avaliação completa da criticidade operacional, dos prazos de reposição e da disponibilidade de alternativas.

## Como executar

1. Abra o notebook no Google Colab.
2. Disponibilize os arquivos CSV necessários na estrutura de pastas esperada pelo notebook.
3. Execute as células de preparação dos dados e criação do banco SQLite.
4. Execute as consultas, análises e visualizações na ordem apresentada.

## Autor

Projeto desenvolvido para demonstrar competências em análise de dados aplicada a Procurement Analytics.
# Dashboard Power BI - Vendas Multicanal

Projeto de análise de vendas utilizando Power BI, SQL e DAX, integrando dados de múltiplos canais de venda.
- **Fonte dos dados:** MySQL (phpMyAdmin) | Power BI Desktop
- **Indicadores:** Receita, Ticket Médio, Vendas por Produto, Origem, Seguro, etc.

## Como usar
1. Execute o script `/sql/criacao_tabela_vendas.sql` no seu banco.
2. Importe os dados de vendas (CSV) via phpMyAdmin.
3. Abra o arquivo `dashboard.pbix` no Power BI e conecte à sua base.
4. Consulte as medidas DAX em `/powerbi/medidas_dax.txt`.

## Estrutura dos dados

| Campo     | Descrição              |
|-----------|-----------------------|
| CONSULTOR | Nome do consultor      |
| DATA      | Data da venda         |
| CLIENTE   | Nome do cliente       |
| CPF       | CPF do cliente        |
| ORGAO     | Orgão do cliente      |
| PRODUTO   | Produto vendido       |
| BANCO     | Banco da operação     |
| VALOR     | Valor da venda        |
| ORIGEM    | Canal de origem       |
| EQUIPE    | Equipe do consultor   |
| SEGURO    | Seguro associado      |

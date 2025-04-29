
# Exercicio 02 de Power BI

📊 Projeto de dashboard no Power BI – Exercício 02

---

## Objetivo

Expandir o relatório anterior (Exercício 01) com novas visualizações e funcionalidades no Power BI, utilizando dados de **Produtos** e **Vendas** com informações de **Data de Venda** e **Região**.

---

## Visuais Criados

- **Gráfico de Colunas** – Vendas por Categoria de Produto
- **Gráfico de Pizza** – Percentual de Vendas por Categoria
- **Tabela Dinâmica** – Produtos, Categoria e Total de Vendas (com formatação condicional)
- **Cartão** – Total Geral de Vendas
- **Cartão** – Ticket Médio de Vendas
- **Gráfico de Linhas** – Evolução das Vendas por Data
- **Gráfico de Barras** – Total de Vendas por Região
- **Segmentador de Produto** – Filtro por Nome do Produto
- **Segmentador de Data** – Filtro por Intervalo de Datas (Entre)

---

## Medidas Criadas (DAX)

```DAX
Total_Vendas = SUM(Vendas[Valor_Venda])

Ticket_Medio = AVERAGE(Vendas[Valor_Venda])
```

---

## Instruções

- Baixe o arquivo **Exercicio02.pbix**.
- Abra com o Power BI Desktop.
- Navegue pelo relatório para visualizar as diferentes análises de vendas.

---

## Arquivos

- `Exercicio02.pbix` — Relatório completo do Exercício 02.

---

## Observações

- As tabelas de dados (`Produtos` e `Vendas`) foram importadas diretamente para dentro do `.pbix`.
- O relacionamento foi feito via campo `ID_Produto`.
- Todas as medidas e visuais foram desenvolvidos conforme enunciado do exercício.

---

📚 Projeto desenvolvido como parte do curso de Power BI.

# Portfólio Power BI 📊

Este repositório reúne dashboards desenvolvidos para estudo e prática da ferramenta Power BI, aplicados em cenários reais.  
Cada projeto contém o arquivo `.pbix`, gifs ilustrativos e link para visualização interativa no Power BI Service.

---

## 📈 Dashboard Financeiro
![Financeiro](https://i.imgur.com/lZW7rfJ.gif)

**Objetivo:** Analisar movimentações financeiras, fluxo de caixa e comparativo de receitas e despesas.  
**Base de dados:** 2.725 registros em Excel.  
[🔗 Acesse o dashboard completo](https://app.powerbi.com/view?r=eyJrIjoiYjVlZDRlZDEtYzY4Yi00YTRmLWEwNmItOTI4OWJhNDU4YTVlIiwidCI6IjI5NjM1NGU5LTk1MmItNDgwNC05NDE0LTA3N2MzZmVjNTg5NSJ9&pageName=ReportSection)

#### Estrutura da base de dados
| Coluna              | Descrição                  |
|---------------------|----------------------------|
| Número Movimentação | Identificador da transação |
| Nome                | Cliente ou fornecedor      |
| Município           | Local da operação          |
| Valor Movimentação  | Montante em R$             |
| Banco               | Instituição financeira     |

---

## 🚚 Dashboard de Logística - V1
![Logística V1](https://i.imgur.com/ICBtVVR.gif)

**Objetivo:** Monitorar entregas, veículos e status de pedidos.  
**Base de dados:** 23.888 registros (CadastroVeiculos.xlsx + Fretes.xlsx).  
[🔗 Acesse o dashboard completo](https://app.powerbi.com/view?r=eyJrIjoiMDhhYTk1ZWMtMDBjZi00NzI0LTk2ZmUtNTQ2MWQ1MGZmZmEzIiwidCI6IjI5NjM1NGU5LTk1MmItNDgwNC05NDE0LTA3N2MzZmVjNTg5NSJ9&pageName=ReportSection1cd0e1a90b7cb2308a4c)

#### Estrutura da base de dados
| Coluna             | Descrição                  |
|--------------------|----------------------------|
| Código Veículo     | Identificador do veículo   |
| Placa              | Placa registrada           |
| Marca              | Fabricante                 |
| Data Pedido        | Data do pedido             |
| Valor Frete Líquido| Valor do frete             |
| Status             | Situação da entrega        |

---

## 🚚 Dashboard de Logística - V2
![Logística V2](https://i.imgur.com/L9VI3fl.gif)

**Objetivo:** Acompanhar pedidos, motoristas e devoluções.  
**Base de dados:** 4.282 registros (DB_Logistica.xlsx).  
[🔗 Acesse o dashboard completo](https://app.powerbi.com/view?r=eyJrIjoiZWEwODY1YTMtYWVlYi00NDkwLWFhOWItOTZhYmI4ZDk0OTVjIiwidCI6IjI5NjM1NGU5LTk1MmItNDgwNC05NDE0LTA3N2MzZmVjNTg5NSJ9)

#### Estrutura da base de dados
| Coluna             | Descrição                  |
|--------------------|----------------------------|
| N° Pedido          | Identificador do pedido    |
| Cliente-Motorista  | Relação cliente e motorista|
| Data Entrega Prev. | Prazo previsto             |
| Status             | Situação da entrega        |
| Motivo Devolução   | Razão da devolução         |

---

## 👥 Dashboard de RH
![RH](https://i.imgur.com/YUPUzbN.gif)

**Objetivo:** Acompanhar dados de colaboradores, contratações e avaliações.  
**Base de dados:** 234 registros em Excel.  
[🔗 Acesse o dashboard completo](https://app.powerbi.com/view?r=eyJrIjoiNzQ2NGQ3ZWMtZDk1ZC00NDAzLWJkNTMtYmMyZGVmODI4ZjlmIiwidCI6IjI5NjM1NGU5LTk1MmItNDgwNC05NDE0LTA3N2MzZmVjNTg5NSJ9)

#### Estrutura da base de dados
| Coluna           | Descrição                  |
|------------------|----------------------------|
| ID RH            | Identificador do colaborador|
| Nome Completo    | Nome do funcionário        |
| Cargo            | Função exercida            |
| Salário          | Remuneração                |
| Avaliação        | Nota de desempenho         |

---

## 🏭 Dashboard de Produção
![Produção](https://i.imgur.com/ma2ezFI.gif)

**Objetivo:** Monitorar ordens de produção, rejeições e eficiência.  
**Base de dados:** 31.617 registros em Excel.  
[🔗 Acesse o dashboard completo](https://app.powerbi.com/view?r=eyJrIjoiNGU3NGViNWUtZjM3MS00ODdhLWExMjMtOWY3NTAxZDJkM2QxIiwidCI6IjI5NjM1NGU5LTk1MmItNDgwNC05NDE0LTA3N2MzZmVjNTg5NSJ9&pageName=ReportSection)

#### Estrutura da base de dados
| Coluna              | Descrição                  |
|---------------------|----------------------------|
| Número Ordem        | Identificador da ordem     |
| Produto             | Item produzido             |
| Quantidade Produzida| Total produzido            |
| Quantidade Rejeitada| Total rejeitado            |
| Ocorrência          | Tipo de evento             |

---

## 🛒 Dashboard de Vendas
![Vendas](https://i.imgur.com/19mRZpY.gif)

**Objetivo:** Analisar vendas por categoria, cliente e região.  
**Base de dados:** 203.883 registros em Excel.  
[🔗 Acesse o dashboard completo](https://app.powerbi.com/view?r=eyJrIjoiODQyZmQwM2MtMGNkYS00ZDY2LTk1M2YtOTlmOThkY2I4YjIxIiwidCI6IjI5NjM1NGU5LTk1MmItNDgwNC05NDE0LTA3N2MzZmVjNTg5NSJ9)

#### Estrutura da base de dados
| Coluna           | Descrição                  |
|------------------|----------------------------|
| Categoria        | Tipo de produto            |
| Marca            | Fabricante                 |
| Quantidade Vendida| Volume de vendas           |
| Localidade       | Cidade/Estado              |
| Continente       | Região geográfica          |

---

💡 **Sugestões de melhoria?** Abra uma issue 😉

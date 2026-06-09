
# 🛒 Dashboard de Planejamento - Black Friday & Matriz BCG

Dashboard interativo desenvolvido no Power BI Desktop para análise inteligente de portfólio de produtos e automação de estratégias promocionais para campanhas de Black Friday.

## 📊 Páginas do Relatório

1. **Black Friday Overview:** Indicadores macro de desempenho (Faturamento Geral, Quantidades Vendidas, Ticket Médio), gráfico de vendas mensais e rankings de produtos.
2. **Análise de Produto:** Detalhamento do mix de produtos, participação percentual de receita utilizando agrupamento dinâmico ("Outros") para limpeza visual.
3. **Planejamento Black Friday (Matriz BCG):** Gráfico de dispersão dinâmico dividindo produtos por quadrantes (Destaque, Alto Giro, Alto Valor e Baixo Desempenho) com aplicação automatizada de margens de desconto via DAX.

## 🛠️ Tecnologias e Recursos Utilizados

- **Power Query (M):** Tratamento de dados, remoção de duplicidades ocultas, padronização de textos de categorias (*Trim* e *Capitalize*) e tratamento de erros de tipo em colunas financeiras.
- **DAX Avançado:** Criação de métricas de médias móveis/gerais utilizando `ALLSELECTED`, inteligência de contexto e travas de segurança com `ISINSCOPE` para limpar linhas de totais em tabelas matriciais.
- **UI/UX Design:** Estrutura em modo escuro (*Dark Mode*), menu de navegação lateral nativo (*Page Navigator*) com efeito retrátil e cartões de KPI integrados ao fundo.

## 📸 Demonstração Visual

![Overview]("DashboardBF/image/1-bfoverview.png")
![Analise]("DashboardBF/image/2-analisedeproduto.png")
![Matriz BCG]("DashboardBF/image/3-planejamentobf.png")


## 📁 Como Executar o Projeto

1. Baixe o arquivo `.pbix` disponível neste repositório.
2. Abra no Power BI Desktop para navegar interativamente utilizando o menu lateral (Segure `Ctrl` + Clique nos botões).


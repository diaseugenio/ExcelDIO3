# Dashboard Interativo em Excel

Este repositório apresenta a estrutura de dados e os componentes essenciais para um **Dashboard Interativo** desenvolvido no Microsoft Excel. O objetivo deste projeto é fornecer uma solução robusta para visualização e análise de dados, permitindo um acompanhamento eficiente de métricas e indicadores-chave de desempenho (KPIs) em diversas áreas, como finanças, gestão de projetos, vendas ou operações.

## Visão Geral do Projeto

O dashboard é concebido para consolidar informações de diferentes fontes, processá-las através de cálculos definidos e apresentá-las de forma visualmente atraente e intuitiva. A sua natureza interativa permite que os usuários explorem os dados dinamicamente, obtendo insights rápidos para auxiliar na tomada de decisões estratégicas.

## Estrutura do Repositório

O projeto é organizado em arquivos CSV, que representam as abas ou as fontes de dados primárias de uma planilha Excel master (`Dashboard.xlsx`). Embora o arquivo `.xlsx` completo não esteja diretamente neste repositório (pois o foco é a estrutura de dados), os CSVs fornecem a base para sua recriação ou integração:

* **`Dashboard.xlsx - A̳ssets.csv`**: Contém dados detalhados sobre os ativos, recursos ou itens tangíveis/intangíveis que são monitorados. Pode incluir informações como valor, status, localização, proprietário e data de aquisição. Este arquivo serve como a base para o acompanhamento patrimonial ou de recursos específicos.
* **`Dashboard.xlsx - B̳ases.csv`**: Armazena tabelas de referência, configurações mestre ou dados base que são utilizados em todo o dashboard. Isso pode incluir listas de categorias, regras de classificação, parâmetros de cálculo, ou dados históricos que não mudam frequentemente, garantindo consistência e padronização das informações.
* **`Dashboard.xlsx - C̳álculos.csv`**: Representa a saída de processamentos ou as fórmulas complexas aplicadas aos dados brutos. Este arquivo armazena os resultados de métricas calculadas, KPIs, agregações, e análises de tendências, sendo o elo entre os dados brutos e as visualizações finais.
* **`Dashboard.xlsx - D̳ashboard.csv`**: Reflete o layout e os dados que são exibidos diretamente na interface principal do dashboard. Inclui as informações que alimentam gráficos, tabelas resumidas, e outros elementos visuais que o usuário final irá interagir para obter uma visão consolidada e dinâmica dos dados.

## Funcionalidades Principais

* **Centralização de Dados:** Consolida informações de diversas origens em um único ambiente.
* **Cálculos Automatizados:** Realiza cálculos complexos e gera KPIs automaticamente com base nos dados fornecidos.
* **Visualização Interativa:** Apresenta dados através de gráficos, tabelas dinâmicas e filtros, permitindo uma exploração aprofundada.
* **Monitoramento de Performance:** Ajuda a acompanhar o desempenho de ativos, projetos ou áreas de negócio em tempo real.
* **Tomada de Decisão Otimizada:** Fornece insights claros e acionáveis para embasar decisões estratégicas.

## Tecnologias Envolvidas

* **Microsoft Excel:** A plataforma principal para o desenvolvimento e utilização do dashboard, aproveitando suas capacidades de fórmulas, tabelas dinâmicas e visualização.
* **CSV (Comma Separated Values):** Formato padrão para intercâmbio dos dados entre as abas do Excel ou para exportação e importação em outros sistemas.

## Como Utilizar (Conceptual)

Para utilizar o Dashboard, a planilha original do Excel (`Dashboard.xlsx`) seria o ponto central. Os arquivos CSV presentes neste repositório funcionam como um blueprint da estrutura de dados. Em um cenário prático:

1.  **Obtenha o arquivo `Dashboard.xlsx` completo:** O dashboard funcionaria plenamente com o arquivo `.xlsx` original (não incluído diretamente neste repositório).
2.  **Importe/Atualize os dados:** Os dados das abas (representados pelos CSVs) seriam atualizados manualmente ou através de funcionalidades de importação de dados do Excel.
3.  **Explore o Dashboard:** A aba "Dashboard" seria o ponto de interação principal, onde gráficos e tabelas dinâmicas seriam atualizados automaticamente conforme os dados de "Assets", "Bases" e "C̳álculos" fossem alterados.

## Contribuição

Contribuições para a melhoria da estrutura de dados, aperfeiçoamento de cálculos, ou sugestões de novas visualizações são bem-vindas. Para contribuir:

1.  Faça um fork deste repositório.
2.  Crie uma nova branch para suas alterações (`git checkout -b feature/sua-melhoria`).
3.  Implemente suas modificações e faça os commits (`git commit -m 'Descreve sua melhoria'`).
4.  Faça o push para a sua branch (`git push origin feature/sua-melhoria`).
5.  Abra um Pull Request descrevendo suas mudanças.

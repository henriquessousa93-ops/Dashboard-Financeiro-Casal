# Dashboard-Financeiro-Casal
Projeto de controle financeiro para casais, com tratamento de dados, consolidação de extratos e dashboard interativo.

*Sobre o Projeto*

O HenriTan é um projeto de controle financeiro para casais, desenvolvido com o objetivo de centralizar informações financeiras individuais e compartilhadas em uma única estrutura de análise.

A proposta surgiu de uma necessidade prática: facilitar o acompanhamento das despesas, proporcionar transparência financeira e permitir que duas pessoas compreendam melhor seus hábitos de consumo e planejamento financeiro.

O projeto contempla diferentes etapas de um processo analítico:

Importação de extratos bancários

Extração, tratamento e transformação dos dados (ETL)

Padronização de informações de diferentes instituições financeiras

Consolidação de uma base histórica

Categorização de lançamentos

Construção de indicadores

Design e desenvolvimento do dashboard

Análise comparativa dos gastos

O objetivo é transformar movimentações financeiras em informações que ajudem o casal a tomar decisões mais conscientes.

Demonstração

Prévia do dashboard:



Os dados apresentados nas demonstrações visuais são fictícios e utilizados exclusivamente para fins ilustrativos.

Páginas do Dashboard

Visão Geral

Resumo financeiro do casal

Acompanhamento das despesas

Comparação entre os gastos individuais

Visão consolidada da movimentação financeira

Controle Individual

Acompanhamento dos gastos de cada pessoa

Distribuição das despesas por categoria

Identificação dos principais grupos de consumo

Comparação do Casal

Comparativo de despesas entre as duas pessoas

Análise da participação individual nos gastos

Identificação de diferenças nos hábitos de consumo

Análise de Despesas

Distribuição dos gastos por categoria

Evolução das despesas ao longo do tempo

Identificação dos principais pontos de consumo

Tecnologias Utilizadas

Microsoft Excel

Power Query

ETL (Extract, Transform, Load)

Tratamento e organização de dados

Categorização de transações

Data Visualization

Dashboard Design

Estrutura do Projeto

HenriTan/
│
├── README.md
│
├── Dashboard/
│   └── arquivo-do-dashboard
│
├── Imagens/
│   ├── capa.png
│   ├── visao-geral.png
│   ├── controle-individual.png
│   ├── comparacao-casal.png
│   └── analise-despesas.png
│
└── Documentacao/
    ├── PowerQuery.md
    ├── ETL.md
    └── Indicadores.md

Estrutura e Organização dos Dados

O projeto utiliza uma estrutura centralizada para reunir movimentações financeiras de diferentes pessoas e instituições bancárias.

As fontes consideradas incluem:

Henrique — Itaú (PDF)

Henrique — Bradesco (PDF, importação histórica)

Natan — Santander (Excel)

A estrutura de dados busca padronizar os lançamentos em campos comuns, como:

Arquivo

Data

Descrição

Valor

Pessoa

Banco

Categoria

Essa padronização permite consolidar diferentes origens em uma única base para análise.

ETL — Extração, Transformação e Carga

O tratamento dos dados é realizado utilizando Power Query.

Principais etapas do processo:

Importação de arquivos bancários

Extração de tabelas dos extratos

Padronização dos nomes das colunas

Conversão dos tipos de dados

Tratamento de créditos e débitos

Remoção de informações desnecessárias

Organização dos lançamentos por pessoa e banco

Categorização das movimentações

Consolidação das informações em uma base histórica

A estrutura foi planejada para facilitar a atualização dos dados conforme novos extratos são adicionados às pastas de entrada.

Indicadores Desenvolvidos

Visão Geral

Total de despesas

Comparação dos gastos individuais

Movimentação financeira consolidada

Controle Individual

Despesas por pessoa

Distribuição por categoria

Evolução dos gastos

Comparação do Casal

Participação individual nas despesas

Diferença entre os gastos

Comparação por categoria

Os indicadores e suas regras de cálculo serão documentados conforme a evolução do projeto.

Storytelling

O dashboard foi pensado para responder perguntas práticas sobre a organização financeira do casal.

Quanto cada pessoa está gastando?

Quais são as principais categorias de despesas?

Como os gastos individuais se comparam?

Onde estão concentradas as maiores despesas?

Como está evoluindo a movimentação financeira?

A proposta é transformar os dados em uma visão compartilhada, facilitando conversas e decisões financeiras sem comprometer a autonomia individual.

Principais Aprendizados

O desenvolvimento deste projeto permite aprofundar conhecimentos em:

ETL e automação de dados

Power Query

Consolidação de diferentes fontes de dados

Padronização e categorização de informações

Organização de bases históricas

Indicadores financeiros

Data Visualization

Design de dashboards

Resolução de problemas reais utilizando dados

Autor

Henrique Sousa

Tecnologia em Análise e Desenvolvimento de Sistemas | Dados e Business Intelligence

LinkedIn

GitHub

⭐ Se gostou do projeto, deixe uma estrela no repositório!

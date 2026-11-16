# Dashboard-Financeiro-Casal
Projeto de controle financeiro para casais, com tratamento de dados, consolidação de extratos e dashboard interativo.


# 📊 HenriTan | Dashboard Financeiro para Casais

<p align="center">

![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-742774?style=for-the-badge)
![ETL](https://img.shields.io/badge/ETL-Data%20Preparation-2563EB?style=for-the-badge)
![Financial Analytics](https://img.shields.io/badge/Financial-Analytics-0F766E?style=for-the-badge)
![Data Visualization](https://img.shields.io/badge/Data-Visualization-5B5BD6?style=for-the-badge)

</p>

---

## 📌 Sobre o Projeto

O **HenriTan** é um projeto de controle financeiro para casais, desenvolvido no **Microsoft Excel**, utilizando **Power Query** para automatizar a importação, o tratamento e a consolidação de movimentações bancárias.

A proposta surgiu de uma necessidade prática: proporcionar uma visão organizada das finanças individuais e compartilhadas, permitindo que duas pessoas acompanhem seus gastos, comparem hábitos de consumo e planejem seus objetivos financeiros em conjunto.

O projeto contempla diferentes etapas de um processo analítico:

- Extração de dados de diferentes instituições financeiras
- Tratamento e transformação dos dados (ETL)
- Padronização de informações bancárias
- Consolidação de uma base histórica
- Categorização de movimentações financeiras
- Desenvolvimento de indicadores
- Storytelling
- Design de Dashboard
- Geração de Insights

O objetivo é transformar movimentações financeiras em informações que facilitem a organização, a transparência e a tomada de decisão financeira a dois.

---

## 🎥 Demonstração

![Dashboard Preview](./Images/dashboard-preview.png)

> ⚠️ **Aviso:** Os valores e dados apresentados nos gráficos são fictícios e utilizados exclusivamente para fins demonstrativos. Nenhuma informação financeira real é exibida.

---

## 🖼️ Páginas do Dashboard

### 📊 Visão Geral

- Resumo das movimentações financeiras
- Acompanhamento das despesas
- Visão consolidada das finanças do casal
- Comparação dos gastos individuais

---

### 👤 Controle Individual

- Acompanhamento financeiro por pessoa
- Distribuição das despesas por categoria
- Identificação dos principais grupos de consumo
- Análise dos hábitos financeiros individuais

---

### ❤️ Comparação do Casal

- Comparativo dos gastos entre as duas pessoas
- Participação individual nas despesas
- Análise das diferenças de consumo
- Visão compartilhada da organização financeira

---

### 💰 Análise de Despesas

- Distribuição dos gastos por categoria
- Identificação das maiores despesas
- Evolução das movimentações financeiras
- Comparação dos gastos ao longo dos períodos

---

## 🛠 Tecnologias Utilizadas

- Microsoft Excel
- Power Query
- ETL (Extract, Transform, Load)
- Tratamento e transformação de dados
- Consolidação de bases de dados
- Categorização de transações
- Data Visualization
- Dashboard Design
- Storytelling com Dados

---

## 📂 Estrutura do Projeto

```text
📁 HenriTan
│
├── README.md
│
├── 📁 Dashboard
│   └── Dashboard.xlsx
│
├── 📁 Images
│   ├── dashboard-preview.png
│   ├── visao-geral.png
│   ├── controle-individual.png
│   ├── comparacao-casal.png
│   └── analise-despesas.png
│
├── 📁 Documentacao
│   ├── PowerQuery.md
│   ├── ETL.md
│   ├── Categorizacao.md
│   └── Indicadores.md
│
└── 📁 Video
    └── dashboard-demo.mp4
```

---

## 📐 Organização e Estrutura dos Dados

O projeto reúne movimentações financeiras provenientes de diferentes instituições bancárias, considerando duas pessoas e suas respectivas contas.

### Fontes de Dados

| Pessoa | Instituição | Formato |
|---|---|---|
| Henrique | Itaú | PDF |
| Henrique | Bradesco | PDF |
| Natan | Santander | Excel |

O Bradesco foi utilizado como fonte de importação histórica, enquanto o Itaú e o Santander compõem as fontes de atualização recorrente.

### Estrutura da Base Histórica

Após o processo de transformação, os dados são organizados em uma estrutura padronizada:

| Campo | Descrição |
|---|---|
| Arquivo | Identificação do arquivo de origem |
| Data | Data da movimentação |
| Descrição | Histórico do lançamento |
| Valor | Valor da movimentação |
| Pessoa | Identificação do responsável |
| Banco | Instituição financeira |
| Categoria | Classificação da movimentação |
| ID_Lancamento | Identificador do lançamento |

Essa estrutura permite reunir diferentes fontes em uma única base, facilitando análises individuais e consolidadas.

---

## 🔄 ETL — Extração, Transformação e Carga

O processo de ETL foi desenvolvido utilizando **Power Query**, permitindo automatizar a leitura e o tratamento dos arquivos financeiros.

### 1. Extração (Extract)

- Importação de extratos bancários em PDF e Excel
- Leitura de arquivos armazenados em pastas específicas
- Separação das fontes por pessoa e instituição financeira

### 2. Transformação (Transform)

- Padronização dos nomes das colunas
- Conversão dos tipos de dados
- Tratamento de créditos e débitos
- Organização dos lançamentos por pessoa e banco
- Remoção de informações desnecessárias
- Categorização automática das movimentações
- Criação de identificadores para os lançamentos

### 3. Carga (Load)

- Consolidação das diferentes fontes
- Construção de uma base histórica
- Preparação dos dados para alimentar os indicadores
- Atualização das informações a partir dos novos arquivos de entrada

### Fluxo do Processo

```text
       EXTRATOS BANCÁRIOS
                │
                ▼
        EXTRAÇÃO DOS DADOS
                │
                ▼
       POWER QUERY (ETL)
                │
                ▼
       TRATAMENTO E PADRONIZAÇÃO
                │
                ▼
       CATEGORIZAÇÃO DOS DADOS
                │
                ▼
       BASE HISTÓRICA DO CASAL
                │
                ▼
        DASHBOARD FINANCEIRO
                │
                ▼
        ANÁLISE E INSIGHTS
```

---

## 📊 Indicadores Desenvolvidos

### Visão Geral

- Despesas consolidadas
- Comparação dos gastos individuais
- Movimentação financeira do casal

### Controle Individual

- Despesas por pessoa
- Distribuição dos gastos por categoria
- Participação individual nas despesas

### Comparação do Casal

- Comparativo de gastos
- Diferença entre despesas individuais
- Análise das categorias de consumo

### Análise de Despesas

- Distribuição por categoria
- Identificação dos principais gastos
- Evolução das movimentações financeiras

---

## 📈 Storytelling

O dashboard foi desenvolvido com foco em **Storytelling com Dados**, buscando transformar informações financeiras em análises de fácil compreensão.

A navegação foi pensada para conduzir o usuário de uma visão consolidada até uma análise mais detalhada dos gastos.

```text
        VISÃO GERAL
             ↓
     CONTROLE INDIVIDUAL
             ↓
    COMPARAÇÃO DO CASAL
             ↓
     ANÁLISE DE DESPESAS
             ↓
        INSIGHTS
```

Além do acompanhamento financeiro, o projeto busca responder perguntas importantes para a organização de um casal:

- Quanto cada pessoa está gastando?
- Quais são as principais categorias de despesas?
- Como os hábitos de consumo se comparam?
- Onde estão concentrados os maiores gastos?
- Como podemos planejar nossos objetivos financeiros em conjunto?

A proposta é utilizar dados para promover mais transparência financeira, sem comprometer a autonomia individual de cada pessoa.

---

## 💡 Principais Aprendizados

Durante o desenvolvimento deste projeto, os principais conhecimentos trabalhados envolvem:

- ETL e automação de dados
- Power Query
- Consolidação de múltiplas fontes
- Tratamento de arquivos PDF e Excel
- Padronização e categorização de informações
- Organização de bases históricas
- Indicadores financeiros
- Storytelling com Dados
- UX para Dashboards
- Data Visualization
- Resolução de problemas reais utilizando dados

---

## 🚀 Próximas Etapas

O HenriTan é um projeto em evolução. Entre os próximos passos estão:

- Aprimoramento das regras de categorização
- Expansão dos indicadores financeiros
- Evolução da estrutura de automação
- Melhorias na experiência de navegação
- Documentação detalhada de cada etapa do desenvolvimento

As atualizações serão documentadas neste repositório, desde o tratamento dos dados até a construção dos indicadores e evolução do dashboard.

---

## 👨‍💻 Autor

**Henrique Sousa**

Análise e Desenvolvimento de Sistemas | Dados e Business Intelligence

🔗 **GitHub:** [henriquessousa93-ops](https://github.com/henriquessousa93-ops)

🔗 **LinkedIn:** [Henrique Sousa](https://www.linkedin.com/in/henriquesousaa/)

---

## ⭐ Se gostou do projeto

Deixe uma ⭐ no repositório e acompanhe a evolução do HenriTan!

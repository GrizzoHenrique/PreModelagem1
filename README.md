# Pré-processamento de dados: Churn Telecom

### Objetivo:
**Realizar a limpeza, tratamento e estruturação de uma base de dados de clientes de telecomunicações (serviços de internet, telefone e TV). O foco é preparar os dados para entender o Churn (taxa de cancelamento).**

### O Dataset
**Os dados contêm informações detalhadas de clientes, tais como:**
* **Identificação e Perfil:** ID do cliente, Gênero, Idoso (>= 60 anos), Casado e Dependentes.
* **Serviços Contratados:** Serviço de telefone, Internet (DSL, Fibra ótica), Segurança, Suporte Técnico e Streaming de TV.
* **Informações de contrato:** Tempo como Cliente, tipo de contrato(mensal,anual etc...) e forma de pagamento
* **Valores Financeiros:** Pagamento Mensal e total pago
* **Target(churn):** indicador se o cliente abandonou ou não a empresa

### Etapas do projeto:
1. **Exploração de tipos de Dados**: Verificação se as colunas estão com os tipos corretos(int,float,object)
2. **Tratamento de dados Faltantes**:
   * Análise de percentagem de valores nulos por coluna.
   * Exclusão estratégica de linhas com baixa representatividade de Nulos(ex: Gênero e Idoso)
   * Substituição de valores nulos em variáveis numéricas(como pagamento mensal), utilizando métricas como média, mediana ou moda
3. **Padronização e limpeza**: Renomeação de colunas para manter um padrão coeso de nomenclatura

### Tecnologias Utilizadas:
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat&logoColor=white)

### Como Executar:
1. Clone o repositório
2. Cerfique de ter o arquivo CHURN_TELECON_MOD08_TAREFA.csv no diretório correto.
3. Execute o notebook rofissao Cientista de Dados M14 Pratique (2).ipynb.

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
| Tecnologia | Versão | Propósito |
|-----------|--------|----------|
| ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) | 3.7+ | Linguagem principal |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) | Latest | Manipulação de dados |
| ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?logo=seaborn&logoColor=white) | Latest | Gráficos estatísticos |

##  Como Executar

### Pré-requisitos
- Python 3.7+
- pip ou conda

### Instalação

```bash
# Clone o repositório
git clone https://github.com/GrizzoHenrique/PreModelagem1.git
cd PreModelagem1

# Crie um ambiente virtual (recomendado)
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt

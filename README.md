# megaline-plan-analysis
Análise de dados de clientes da Megaline para comparar o comportamento de uso dos planos Surf e Ultimate e apoiar decisões de negócio.

## Visão Geral

Este projeto analisa dados de usuários da operadora fictícia **Megaline** com o objetivo de compreender o comportamento de consumo dos clientes e comparar o desempenho comercial de dois planos pré-pagos: **Surf** e **Ultimate**.

A análise considera o uso de chamadas, mensagens de texto, internet móvel e receita gerada por usuário, buscando identificar diferenças relevantes entre os planos e gerar insights úteis para decisões estratégicas.

## Problema de Negócio

A Megaline deseja entender qual dos planos gera melhores resultados e como os clientes utilizam os serviços incluídos em cada opção. A partir dessa análise, a empresa pode tomar decisões mais informadas sobre posicionamento, marketing e oferta de planos.

## Conjunto de Dados

O projeto utiliza dados relacionados a clientes, uso de serviços e planos da Megaline, incluindo informações como:

- identificação dos usuários
- cidade e região
- plano contratado
- duração das chamadas
- quantidade de mensagens enviadas
- volume de dados móveis consumidos
- receita mensal por cliente

Os arquivos utilizados no projeto estão organizados na pasta `datasets/`:

- `megaline_calls.csv`
- `megaline_internet.csv`
- `megaline_messages.csv`
- `megaline_plans.csv`
- `megaline_users.csv`

## Objetivos da Análise

Este projeto busca responder perguntas como:

- Como os clientes dos planos Surf e Ultimate se comportam em relação ao uso de chamadas, mensagens e internet?
- Qual plano tende a gerar maior receita média?
- Existem diferenças relevantes entre os perfis de consumo dos usuários?
- Há evidências estatísticas de diferença entre as receitas dos planos?
- A receita média de determinadas regiões difere do restante da amostra?

## Etapas do Projeto

O projeto foi desenvolvido nas seguintes etapas:

1. carregamento e inspeção inicial dos dados
2. tratamento e preparação das tabelas
3. agregação do consumo mensal por usuário
4. cálculo de receita mensal
5. análise exploratória dos padrões de uso
6. comparação entre os planos Surf e Ultimate
7. testes de hipótese
8. conclusões finais de negócio

## Ferramentas e Bibliotecas

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Estrutura do Repositório

```text
megaline-plan-analysis/
├── .gitignore
├── README.md
├── requirements.txt
├── megaline_plan_analysis.ipynb
└── datasets/
    ├── megaline_calls.csv
    ├── megaline_internet.csv
    ├── megaline_messages.csv
    ├── megaline_plans.csv
    └── megaline_users.csv
````

## Como executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/IagoZanquetta/megaline-plan-analysis.git
   ```

2. Acesse a pasta do projeto:

   ```bash
   cd megaline-plan-analysis
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

4. Abra o arquivo `megaline_plan_analysis.ipynb` no Jupyter Notebook, JupyterLab ou VS Code.

5. Execute as células em ordem.

## Principais Pontos Analisados

Entre os principais focos da análise, estão:

* comportamento de consumo por tipo de serviço
* diferenças de uso entre os planos Surf e Ultimate
* distribuição de chamadas, mensagens e internet
* cálculo de receita mensal por usuário
* comparação de médias entre grupos
* testes estatísticos aplicados ao contexto de negócio

## Resultados

O notebook inclui:

* preparação e integração dos dados
* análise exploratória com visualizações
* comparação entre os planos
* cálculo de receita por cliente
* testes de hipótese
* conclusões com foco em negócio

## Conclusão

Este projeto demonstra como a análise de dados pode ser utilizada para compreender o comportamento de clientes de telecomunicações e comparar o desempenho de diferentes planos. A combinação entre análise exploratória e testes estatísticos permite identificar padrões de consumo, diferenças entre grupos e possíveis implicações para decisões estratégicas da empresa.

## Autor

**Iago Zanquetta**

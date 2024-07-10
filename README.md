# Python Insights - Analisando Dados com Python

## Case - Cancelamento de Clientes

### Introdução

Você foi contratado por uma empresa com mais de 800 mil clientes para um projeto de Dados. Recentemente, a empresa percebeu que uma grande parte de sua base total de clientes são inativos, ou seja, já cancelaram o serviço. Para melhorar seus resultados, a empresa quer entender os principais motivos desses cancelamentos e identificar as ações mais eficientes para reduzir esse número.

### Estrutura do Projeto

O projeto está organizado da seguinte forma:

- `cancelamentos.csv`: Contém os dados completos dos clientes e informações sobre o cancelamento.
- `cancelamento_sample.csv`: Uma versão mais leve do dataset principal para facilitar o desenvolvimento em máquinas com menos capacidade.
- `inicial.ipynb`: O notebook Jupyter contendo todo o processo de análise e visualização de dados.

### Dados

Os dados estão contidos em dois arquivos CSV:

1. `cancelamentos.csv`
2. `cancelamento_sample.csv`

**Estrutura dos Dados:**

- `CustomerID`: Identificação do cliente
- `idade`: Idade do cliente
- `sexo`: Sexo do cliente
- `tempo_como_cliente`: Tempo como cliente em meses
- `frequencia_uso`: Frequência de uso do serviço
- `ligacoes_callcenter`: Número de ligações para o call center
- `dias_atraso`: Dias de atraso no pagamento
- `assinatura`: Tipo de assinatura do cliente
- `duracao_contrato`: Duração do contrato
- `total_gasto`: Total gasto pelo cliente
- `meses_ultima_interacao`: Meses desde a última interação do cliente
- `cancelou`: Indicador se o cliente cancelou o serviço (Sim/Não)

### Objetivos do Projeto

- Importar e visualizar os dados
- Tratar os dados, incluindo a remoção de colunas e linhas desnecessárias
- Analisar os padrões de cancelamento dos clientes
- Utilizar visualizações de dados para identificar as causas dos cancelamentos
- Retirar insights que possam ajudar a empresa a reduzir o número de cancelamentos

### Ferramentas Utilizadas

- **Pandas**: Para manipulação e análise de dados.
- **Plotly**: Para criação de gráficos interativos e visualizações.

### Passos do Projeto

1. **Importação dos Dados**: Carregar os dados dos arquivos CSV para dataframes do Pandas.
2. **Visualização Inicial**: Analisar a estrutura dos dados e realizar uma limpeza inicial.
3. **Tratamento de Dados**: Remover colunas e linhas desnecessárias, tratar valores nulos e ajustar tipos de dados.
4. **Análise de Cancelamentos**: Explorar os dados para identificar padrões e tendências nos cancelamentos.
5. **Visualizações com Plotly**: Criar gráficos interativos para analisar as causas dos cancelamentos e outras métricas relevantes.
6. **Retirada de Insights**: Utilizar as análises e visualizações para identificar ações que a empresa pode tomar para reduzir os cancelamentos.

### Como Executar o Projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/Htmluna/Extracao-de-dados-com-python.git

2. Navegue até o diretório do projeto:

   ```bash
   cd Extracao-de-dados-com-python


3. Instale as dependências:

   ```bash
   pip install -r requirements.txt


4. Abra o notebook Jupyter:

   ```bash
   jupyter notebook inicial.ipynb


5.Siga as etapas no notebook para reproduzir a análise.

# Conclusão

Este projeto fornece uma análise detalhada dos motivos pelos quais os clientes estão cancelando seus serviços, utilizando técnicas de análise de dados e visualização. Os insights retirados podem ajudar a empresa a tomar decisões informadas para melhorar a retenção de clientes.


# Análise financeira ClearBank

Projeto de análise de dados desenvolvido como desafio prático da Rocketseat. O sistema realiza a leitura, validação e limpeza de transações bancárias em formato CSV, processando métricas mensais (crédito, débito, saldo e estatísticas) e identificando movimentações suspeitas.

## Funcionalidades
- Leitura e tratamento de arquivos CSV com módulo nativo do Python.
- Validação de dados (formatos de data, tipos de valores, campos obrigatórios).
- Geração de relatório financeiro mensal com métricas de saldo e média.
- Identificação e listagem de transações suspeitas acima de R$ 10.000,00 (configurável).
- Exportação de resultados em formato JSON estruturado.
- Análise opcional com a biblioteca pandas e visualização com matplotlib.

## Como executar
1. Certifique-se de que o arquivo `transacoes.csv` está no diretório configurado no código.
2. Abra o arquivo `Análise_Financeira_com_Python.ipynb` no Google Colab ou em um ambiente Jupyter.
3. Execute todas as células em ordem sequencial.
4. Caso queira rodar a análise opcional, execute também o arquivo `analise_pandas.ipynb`.

## Saídas geradas
Ao executar o notebook principal, o projeto gera as seguintes saídas:
- **Resumo de limpeza:** Exibido no terminal com a contagem de registros válidos e inválidos.
- **Relatório financeiro:** Exibido no terminal com o resumo mensal e a lista de transações suspeitas.
- **relatorio.json:** Arquivo salvo contendo os dados processados para futuras integrações.
- **Gráficos (opcional):** Arquivos como `grafico.png` gerados pelo script opcional para visualização de tendências.

## Tecnologias utilizadas
- Python 3.10+
- Pandas (opcional)
- Matplotlib (opcional)
- JSON/CSV

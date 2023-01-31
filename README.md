# Desafio Cientista de Dados

O objetivo do desafio é identificar quais máquinas apresentam potencial de falha tendo como base dados extraídos através de sensores durante o processo de manufatura.  Para isso são fornecidos dois datasets: um dataset chamado desafio_manutencao_preditiva_treino composto por 6667 linhas, 9 colunas de informação (features) e a variável a ser prevista (“failure_type”). 

O segundo dataset chamado de desafio_manutencao_preditiva_teste possui 3333 linhas e 8 colunas e não possui a coluna “failure_type”. O objetivo é prever essa coluna a partir dos dados enviados.

# Itens a serem entregues
1. Descrição gráfica dos dados disponíveis e principais estatísticas descritivas; :white_check_mark:
2. Explicação de como a previsão foi feita, quais variáveis e/ou transformações foram utilizadas, qual o tipo de previsão (regressão, classificação) e qual foi o modelo escolhido, além de seus prós e contras. Por fim, deve ser apresentada a performance do modelo e a razão da escolha; :white_check_mark:
3. Documento *predicted.csv* com apenas duas colunas (rowNumber, predictedValues); :white_check_mark:
4. README explicando como rodar o projeto; :white_check_mark:
5. Arquivo requirements com todos os pacotes utilizados; :white_check_mark:
6. Relatório de EDA em PDF, Jupyter Notebook ou semelhante conforme passo 1 e códigos de modelagem utilizados no passo 2. :white_check_mark:


# Como rodar este projeto?
1. O presente projeto foi desenvolvido usando Python 3.9.12, sendo essencial tê-lo instalado nesta versão ou superior para conseguir executar o arquivo.
2. No terminal, rode o seguinte comando para conseguir utilizar o notebook:
```conda install -n test ipykernel --update-deps --force-reinstall```
3. Por fim, deve-se também fazer a instalação dos pacotes referenciados no arquivo *requirements.txt*, usando o comando ```pip install -r requirements.txt```, disponível na primeira célula executável do notebook.
4. Todas as explicações e discussões referente ao desafio, assim como o modelo escolhido e o código para gerar a predição estão presentes no arquivo *Relatório_desafio.ipynb*.
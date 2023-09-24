# Projeto Transtornos mentais
## Projeto para a matéria Prática em ciência de dados 2023/2


### Alunos
Eduardo Zaffari Monteiro - eduardozaffarimonteiro@usp.br  
Paloma Botto de Medeiros Serrão - palomabotto@usp.br  
Pedro Henrique de Freitas Maçonetto - pedromaconetto@usp.br  

### Descrição do projeto
Análise de dados de internações de hospitais especializados em transtornos mentais da região de Ribeirão preto

### O que foi feito antes do primeiro commit 
![Alt text](https://github.com/ImagineDogs/TranstornosMentais/blob/main/prior_to_git.jpg "a title")

### Guia de reprodutividade:

#### Limpeza dos dados:
dados brutos(total_dataset.csv) --> Limpeza.ipynb --> df_limpo.csv

#### Obtenção de rótulos CID10:
df_limpo.csv,CID_10_familias.csv,Tabela CID10.csv --> CID10.ipynb --> df_cid10.csv

#### Demais análises
df_cid10.csv --> Exploracao.ipynb  
df_cid10.csv --> Associacoes_Correlacoes.ipynb

## Sobre o desenvolvimento deste trabalho

O desafio está composto em 3 partes, sendo elas:

1. Criar conta na Azure
2. Processo de Criação, Comunicação, Integração do Banco de Dados MYSQL com Power BI
3. Processo de ETL/ELT, com como apresentar algumas análise para prática e entendimento do módulo 3 do curso da DIO

<p style="text-align: justify;">Para criação do banco de dados foi utilizado o script.sql aplicando conceitos de acesso via terminal e acesso direto pelo link publico do servidor.
para população do banco de dados, devido a criação gerar um integrigade via constraints foi necessário desabilitar a verificação de foreing keys ```SET FOREIGN_KEY_CHECKS=0```, e 
após a inserção dos dados, habilitar novamente, para manter a consistência e integridade através do comando ```SET FOREIGN_KEY_CHECKS=1```.</p>

> São esperados como artefatos para entregas a saídas a seguir:

* Tratar os dados incompatíveis;
* Carregar somente as colunas das tabelas que foram utilizadas;
* Carregar a fonte de dados a partir de uma conexão com o banco de dados hospedado na Azure;
* Criar script para nova fonte de dados utilizando o Direct Query;
* Criar algumas análises para demonstrar o conhecimento adquirido.
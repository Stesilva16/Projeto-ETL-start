# Projeto-ETL-start
Esse é um projeto de aquecimento feito no bootcamp. 

<h2>Resumo do Projeto:</h2>

O objetivo é realizar um processo de ETL que consolide as bases de dados disponibilizadas em somente uma base consolidada.
A base de dados é obtida a partir da Comunicação de Acidentes do Trabalho do INSS (CATWEB) e pode ser informada por sistema, telefone ou presencial.
O arquivo original e tratado deve ser salvo em MongoDB Atlas e em uma bucket do CloudStorage.
É necessário realizar a extração dos dados para um dataframe, verificar a existência de dados inconsistentes e realizar a limpeza.
Além disso, agregar todos os dataframes em um único dataframe tratado e gerar pelo menos 3 insights dos dados.
É necessário montar a estrutura do dataframe utilizando o StructType, verificar a existência de dados inconsistentes e realizar a limpeza.
É necessário mudar o nome de pelo menos 2 colunas, criar pelo menos duas novas colunas com informações relevantes e utilizar filtros, ordenação e agrupamento.
Além disso, utilizar pelo menos duas Window Functions e gerar pelo menos 5 insights utilizando SparkSQL.
As ferramentas utilizadas serão Colab ou algum IDES e Google Cloud.
O projeto deve ser entregue com o certificado no Mongo Atlas e uma key de autenticação para acesso ao Mongo Atlas. O código também deve ser enviado juntamente com o link Colab.

# Exercício shp2pgsql

1. Utilizando o ficheiro de municípios disponibilizado para download, use o shp2pgsql para
   gerar uma ficheiro sql de saída. Use as opções -s e -W para controlar o encoding de
   entrada e a projecção.

2. Faça a carga do ficheiro sql gerado em municípios utilizando o utilitário psql ou o
   pgAdmin.

3. Exporte o ficheiro utilizando o utilitário pgsql2shp. Use uma query específica para
   saída dos dados, caso deseje.

4. Crie três tabelas geométricas: uma com o tipo ponto, outra do tipo linha e a outra do
   tipo polígono e insira alguns dados nas mesmas (INSERTS e a função ST_GeomFromText).
   No fim, faça um dump de cada tabela com o utilitário pgsql2shp.

5. Crie três tabelas geográficas: uma com o tipo ponto, outra do tipo linha e a outra do
   tipo polígono e insira alguns dados nas mesmas (INSERTS e a função ST_GeogFromText).
   No fim, faça um dump de cada tabela com o utilitário pgsql2shp.

6. Utilizando o QuantumGIS, tente visualizar seus dados (criados nos exercícios 4 e 5). 

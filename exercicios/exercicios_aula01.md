# Exercício shp2pgsql

1. Utilizando o ficheiro de municípios disponibilizado para download, use o shp2pgsql para
   gerar uma ficheiro sql de saída. Use as opções -s e -W para controlar o encoding de
   entrada e a projecção.

2. Faça a carga do ficheiro sql gerado em municípios utilizando o utilitário psql ou o
   pgAdmin. Quais são as dificuldades?

3. Tente visualizar o ficheiro importado no Quantum GIS. Quais foram as dificuldades?

4. Exporte o ficheiro utilizando o utilitário pgsql2shp. Use uma query específica para
   saída dos dados, caso deseje.

5. Crie três tabelas geométricas: uma com o tipo ponto, outra do tipo linha e a outra do
   tipo polígono e insira alguns dados nas mesmas (INSERTS e a função ST_GeomFromText).
   No fim, faça um dump de cada tabela com o utilitário pgsql2shp.

6. Crie três tabelas geográficas: uma com o tipo ponto, outra do tipo linha e a outra do
   tipo polígono e insira alguns dados nas mesmas (INSERTS e a função ST_GeogFromText).
   No fim, faça um dump de cada tabela com o utilitário pgsql2shp.

7. Utilizando o QuantumGIS, tente visualizar seus dados (criados nos exercícios 5 e 6). 
   Quais foram as dificuldades? Houve alguma tabela que o QuantumGIS não abriu?

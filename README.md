# Tabela De Prazos
Uma pequena tabela que mostra os dados com data em até 6 meses comparado com o mês atual.


## Objetivo:
O objetivo do projeto é pegar tabelas de excel, filtrar os dados e mostrar apenas os dados com data igual ou inferior aos próximos 6 meses.

## Detalhes:
A tabela do excel é formada por 12 colunas, sendo a 5° e 6° sendo data.  
O excel costuma ter códigos para data, por exemplo: 14/09/2013 seria 41689.  
Por esses motivos tive que fazer algumas funções para transformar desse "cod" em excel para uma data;  
Verificar se a data tava no formato Brasileiro: DIA/MES/ANO;  
Usar split para pegar o mês e para filtrar apenas os dados com tempo de até 6 meses (comparado com o atual).


## Finalidade:
O programa será utilizado temporariamente no Estágio para lidar com datas e documentos.

## Exemplo de Documento:
A seguir mostrarei um exemplo de um documento que seria lido por esse programa.

| CÓDIGO | DESCRIÇÃO  | MODO       | NOME    | DATA INICIO | DATA FIM   | PREÇO  | RESPONSAVEL | OBS     | STATUS | SETOR | OBJETIVO |
|--------|------------|------------|---------|-------------|------------|--------|-------------|---------|--------|-------|----------|
| 007    | Dado 2     | Presencial | RAFAEL  | 15/06/2014  | 17/03/2025 | R$ 200 | Sr Antonio  | Sem obs | FEITO  | t.i   | --       |




## Ferramentas Usadas:
[Bootstrap4](https://datatables.net/examples/styling/bootstrap4)
[DataTables JS](https://datatables.net/)
[DataTables JS do Zero com Sourabh- Playlist](https://www.youtube.com/watch?v=cir1LMHnTNU&list=PLuHZvo2PtROGEAiJ1K3VGizvjBjklZIOD)
[Tela Home Tutorial](https://youtu.be/v0IgI8vYD_o?si=UIve2uWz4LiIt4Jt)


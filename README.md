# go-zdb-api

#Sintaxe

1-create table table_name (id int not_null, nome varchar(50), observacao text, saldo numeric(10,2));

2-create sequence(seq_table_name_id);

3-create unique(unique_table_name_id) table(table_name) column(id)

4-create index(index_table_name_id) table(table_name) column(id)

5-insert table table_name (id = get_sequence('seq_table_name_id'), nome = 'izaque');

6-select table_teste (id, nome) where (nome = 'izaque') order (nome) limit 100

7-delete from table_teste where (nome='izaque')

8-update table_teste (nome='izaque') where(id=1)

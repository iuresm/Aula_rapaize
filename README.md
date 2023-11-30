# Aula_rapaize

No dia 30/11

Data Persistence = Database
SQL -> search query language
Biblioteca SQlite

Usuário : 
[id]   [login]   [email]         [tel]          [permissões_id]
1      joao      joao@gmail.com  (12)34567890        1
2      josé      jose@gmail.com   ...                2
3      maria     maria@gmail.com  ...                2
4      etc       ...              ...                3


Permissões:
[id]    [com.]
1       Admin
2       Moderador
3       Comum
...     ...

estrutura do sql:
[usuario_id]      [rua]                [número]  ...
      1           Rua XV de Novembro     123     ...

select rua, número, cep from usuario, endereço where login ='joao' and usuario_id = usuario.id



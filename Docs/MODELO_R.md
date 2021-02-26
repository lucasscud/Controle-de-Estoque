# Modelo Relacional
Obs: __Chave_primária__, #Chave_estrangeira#

Produto(__Código__, Nome, Preço, #Compra#, Quantidade_Compra, #Estoque#, Quantidade_estoque, Repartição_estoque) R1,R4

Estoque(__Código__,) R1 

Compra(__Código__, #Estoque#, #Funcionario#, #Cliente#) R1,R4 

Funcionário(__Usuário__, Nome, Senha) R1

Cliente(__CPF__, Nome, Endereço) R1
 





# Sistema de lista de mercado
## Requisitos
- Seja capaz de gerenciar várias listas de mercado (e marcar seu status como concluida ou nao)
- Ser capaz de cadastrar produtos e consulta-los
- Ser capaz de incluir produtos nas listas e especificar suas quantidades, bem como marcar se item ja foi comprado ou nao
- Ser capaz de atribuir valores aos itens comprados para depois ter uma gestao dos custos da lista
- Ser capaz de adicionar quantidades (Kg, unidades, litros, etc)

## Casos de uso - produtos
### Cadastrar produtos 
Informar o nome de um determinado produto e o sistema  o armazena no banco de dados
### Consultar produtos 
Informar palvaras chaves para consulytar ou mesmo buscar produtos a partir de uma lista
### Alterar dados de prdodutos
Basicamente alterar o nome do produto e termos sua efetivacao no banco de dados
## Casos de uso - Lista
Criar uma nova lista inserindo a data e o local onde foi feita a compra (nome do supermercado/feira, etc)
### Apagar um lista
Remover uma lista criada por engano e todos os seus itens que foram criados
### Insercao de itens na lista
Criar um item associando a uma lista e a um produto, bem coomo deixar disponivel a possibilidade de modificar quantidade e preco que foi pago
### Alteracao de itens da lista
alterar apenas quantidadee e preco pago  e status
### Remocao de itens na lista
poder remover um item que foi foi cadastrado na lista
### Fechamento  da lista 
concluir a lista como sendo completa e gerir oseu custo total a partir dos itens comprados


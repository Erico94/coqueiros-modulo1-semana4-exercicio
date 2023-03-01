# coqueiros-modulo1-semana4-exercicio

Exercícios sobre POO com foco em Herança, Menu, Exception e Listar Dados

Criar um projeto console para executar os exercícios

Objetivo nesta semana é simular um sistema de venda de  bebidas

CLASSE PAI:
Exercício com foco em Herança, sendo classe pai
Detalhes da classe
Propriedades
Id  inteiro (int)
Tipo texto (string)
Refrigerante
Suco
MiliLitro decimal (decimal)
NomeBebida texto (string)
ValorCompra decimal (decimal)
Criar um método público chamado Comprar
Texto escrito no console, “Valor da compra do produto id {id} alterado para {valorcompra}”

CLASSE FILHA SUCO:
Exercício com foco em Herança, sendo classe filha da classe pai
Detalhes da classe
Propriedades
TipoCaixa texto (string)
Criar um método público chamado ImprimirDados
Texto escrito no console, “O produto id {id} é um suco é do tipo {tipoCaixa}  com quantidade de MiliLitros {miliLitros}”

CLASSE FILHA REFRI:
Exercício com foco em Herança, sendo classe filha da classe pai
Detalhes da classe
Propriedades
Vidro (bool)
Criar um método público chamado ImprimirDados
Se a propriedade Vidro for verdadeiro mostrar o texto
Texto escrito no console, “O produto id {id} com nome {nomeBebida} é um refrigerante MiliLitros {miliLitros} é um vidro”
Se a propriedade Vidro for falso mostrar o texto
Texto escrito no console, “O produto id {id} com nome {nomeBebida} é um refrigerante MiliLitros {miliLitros} é uma garrafa pet ”

REPOSITÓRIO:
Exercício com foco em classe static
Detalhes da classe
Propriedades static
Lista Propriedade Bebida
Lista Propriedade Suco
Lista Propriedade Refrigerante
Métodos
Adicionar Suco parametro suco
Adicionar Refrigerante parametro refrigerante
Adicionar Bebida parametro bebida
Alterar Bebida parametro bebida
Excluir Bebida com parametro Id
Listar todas bebidas

MENU PARA CONSOLE:
Exercício com foco em classe static
Classe de Menu da calculadora pode ser um exemplo a ser seguido.
Obs. As opções devem ser números para efetuar a validação conforme citado no exercício 6
Criar uma propriedade Lista do tipo Bebida
Criar classe Menu
Menu Inserir Bebida
Instanciar a classe e inserir no repositório
Menu Alterar Bebida
Selecionar o registro da propriedade lista da classe repositório
Alterar os dados da classe selecionada menos o id
Menu Excluir Bebida
Selecionar o registro da propriedade lista
Remover o item selecionado pelo id
Menu Listar Todas Bebida
Imprimir todas as propriedades da lista
Menu Listar todos os Sucos
Menu Listar todos os Refrigerantes
Menu Sair
Sair do Console
Assunto Exception
Na classe Menu criar as validações das opções digitadas
Caso de algum erro criar uma excetion e não fechar o console


Na classe repositório efetuar a seguinte ação
Criar método para executar todos os registros da propriedade Suco
Percorrer toda a lista e executar a ação ImprimirDados da classe Suco
Na classe repositório efetuar a seguinte ação
Criar método para executar todos os registros da propriedade Refrigerante
Percorrer toda a lista e executar a ação ImprimirDados da classe Refrigerante

@startuml
left to right direction

actor Usuario as U
rectangle "Sistema de Livraria" {
  U --> (Registro de Usuário)
  U --> (Login de Usuário)
  U --> (Recuperação de Senha)
  U --> (Visualizar Lista de Livros)
  U --> (Pesquisar Livros)
  U --> (Visualizar Detalhes do Livro)
  U --> (Adicionar ao Carrinho)
  U --> (Remover do Carrinho)
  U --> (Visualizar Carrinho)
  U --> (Realizar Compra)
  U --> (Informações de Entrega)
  U --> (Informações de Pagamento)
  U --> (Editar Perfil)
  U --> (Alterar Senha)
  U --> (Histórico de Compras)
  U --> (Avaliar Livro)
  U --> (Comentar em Livro)
}
@enduml


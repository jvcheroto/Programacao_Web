@startuml
left to right direction

actor Usuario as U

rectangle "Sistema de Livraria" {
  U --> (Registro)
  U --> (Login)
  U --> (Pesquisar Livros)
  U --> (Visualizar Detalhes do Livro)
  U --> (Finalizar Compra)
  U --> (Visualizar Histórico de Compras)
  U --> (Avaliar Livro)
  U --> (Comentar em Livro)
}

rectangle "Admin" {
  U --> (Adicionar Livro)
  U --> (Editar Livro)
  U --> (Remover Livro)
}

@enduml



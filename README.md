@startuml
left to right direction

actor Usuario as U
rectangle "Sistema de Livraria" {
  U --> (Pesquisar Livros)
  U --> (Visualizar Detalhes do Livro)
}

classDiagram
class Usuario {
  - nome: String
  - email: String
}

class SistemaDeLivraria {
  << (C, #FF7700) >> 
}

class PesquisarLivros {
  << (C, #FF7700) >>
}

class VisualizarDetalhesDoLivro {
  << (C, #FF7700) >>
}

Usuario "1" --* "1" SistemaDeLivraria
SistemaDeLivraria "1" --* "1" PesquisarLivros
SistemaDeLivraria "1" --* "1" VisualizarDetalhesDoLivro

@enduml


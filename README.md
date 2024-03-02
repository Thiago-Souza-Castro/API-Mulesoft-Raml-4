A API de Gerenciamento de Livros oferece funcionalidades para gerenciar uma coleção de livros. Desenvolvida em RAML 1.0, utiliza o media type application/json. O design da API foi realizado com MuleSoft, as configurações de fluxos foram feitas através do Anypoint Studio, e os dados são armazenados eficientemente no MySQL.

Tipos de Dados:

Livro:
Estrutura para representar informações sobre um livro.
Propriedades: id, título, autor, gênero, status.
Exemplo: Detalhes de um livro.

Endpoints

/livros
POST:

Adiciona um novo livro à coleção.

GET:
Lista todos os livros com filtragem opcional por autor ou gênero.

/livro/{Id}

GET:
Obtém um livro específico pelo seu ID.

PUT:
Descrição: Atualiza informações de um livro existente.

DELETE:
Descrição: Exclui um livro da coleção.

Explore esta API para adicionar, listar, visualizar, atualizar e excluir livros de sua coleção. Utilize as operações disponíveis de forma eficiente para gerenciar sua biblioteca pessoal, com o design feito no MuleSoft e configurações de fluxos no Anypoint Studio, garantindo um fluxo de dados consistente e seguro.






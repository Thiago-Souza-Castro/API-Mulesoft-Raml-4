A API de Gerenciamento de Livros oferece funcionalidades para gerenciar uma coleção de livros. Desenvolvida em RAML 1.0, utiliza o media type application/json. O design da API foi realizado com MuleSoft, as configurações de fluxos foram feitas através do Anypoint Studio, e os dados são armazenados eficientemente no MySQL.

Tipos de Dados:

Livro:
Estrutura para representar informações sobre um livro.
Propriedades: id, título, autor, gênero, status.
Exemplo: Detalhes de um livro.
Endpoints:

/livros

POST:

Descrição: Adiciona um novo livro à coleção.
Corpo: application/json - Tipo: Livro
Respostas:
201: {"mensagem": "Livro adicionado com sucesso."}

GET:
Descrição: Lista todos os livros com filtragem opcional por autor ou gênero.
Respostas:
200: Lista de livros (application/json: Livro[]).

/livro/{Id}

GET:
Descrição: Obtém um livro específico pelo seu ID.
Respostas:
200: Detalhes do livro (application/json: Livro).

PUT:
Descrição: Atualiza informações de um livro existente.
Corpo: application/json - Tipo: Livro
Respostas:
200: {"mensagem": "Livro atualizado com sucesso."}

DELETE:
Descrição: Exclui um livro da coleção.
Respostas:
204: {"mensagem": "Livro excluído com sucesso."}

Explore esta API para adicionar, listar, visualizar, atualizar e excluir livros de sua coleção. Utilize as operações disponíveis de forma eficiente para gerenciar sua biblioteca pessoal, com o design feito no MuleSoft e configurações de fluxos no Anypoint Studio, garantindo um fluxo de dados consistente e seguro.






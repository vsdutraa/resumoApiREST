# API REST e RESTful

A arquitetura REST (Representational State Transfer) é um conjunto de princípios de design para sistemas de comunicação baseados na web. É amplamente adotada na construção de APIs para serviços web, oferecendo uma abordagem simples e escalável para integração de sistemas distribuídos. Uma API RESTful é uma implementação de um serviço da web que segue os princípios da arquitetura REST.

## Diferenças entre REST e RESTFul

A principal diferença entre REST e RESTful é que REST é um conjunto de princípios de design para sistemas de comunicação, enquanto RESTful se refere à implementação desses princípios. Um serviço RESTful segue os princípios da arquitetura REST, incluindo a utilização de URIs para identificar recursos, utilização de verbos HTTP para operações em recursos, utilização de representações de recursos (como JSON ou XML) e a ausência de estado entre requisições.

## Verbos HTTP

Os verbos HTTP, como GET, POST, PUT, DELETE, entre outros, são utilizados para indicar a ação que deve ser realizada em um recurso específico. Por exemplo:
- **GET**: recupera um recurso.
- **POST**: cria um novo recurso.
- **PUT**: atualiza um recurso existente.
- **DELETE**: remove um recurso.

## Códigos de Status HTTP

Os códigos de status HTTP são retornados em resposta a uma requisição feita a um servidor. Eles indicam se a requisição foi bem-sucedida, falhou ou exigiu ações adicionais por parte do cliente. Alguns exemplos comuns são:
- **200 (OK)**: indica que a requisição foi bem-sucedida.
- **404 (Not Found)**: indica que o recurso solicitado não foi encontrado.
- **500 (Internal Server Error)**: indica um erro interno no servidor.

---

Victor S. Dutra de Amorim - 01515499

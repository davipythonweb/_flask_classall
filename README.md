# _flask_classall
class with flask


- sudo apt update
- sudo apt install curl
- curl --version
- python3 -m venv venv
- sudo apt update
- sudo apt install python3-venv
- python3 -m venv .venv
- source .venv/bin/activate
- pip install flask
- pip freeze > requirements.txt

| Pasta         | Responsabilidade                                                     |
| ------------- | -------------------------------------------------------------------- |
| **routes/**   | Receber requisições HTTP e encaminhá-las                             |
| **services/** | Implementar as regras de negócio                                     |
| **models/**   | Representar as entidades/tabelas do banco                            |
| **utils/**    | Funções auxiliares reutilizáveis (JWT, validações, formatação, etc.) |
| **database/** | Configuração da conexão com o banco de dados                         |


Essa separação segue o princípio da responsabilidade(Single Responsibility Principle - SRP): cada módulo faz uma coisa bem definida. Isso torna o código mais fácil de testar, reutilizar e evoluir à medida que a API cresce.

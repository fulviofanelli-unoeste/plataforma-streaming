# Atividade 3 - Plataforma de Streaming

Crie um backend para uma plataforma de streaming que será consumida por uma aplicação frontend onde os usuários poderão assistir os conteúdos. A solução deve ser construída utilizando Node/Express.
Para simularmos um repositório de conteúdos vamos  utilizar o YouTube, mas ao serem cadastrados na nossa base de dados, nós iremos acrescentar algumas informações a mais, por exemplo: título, categoria e disponibilidade. <br>
Para fazer o gerenciamento de conteúdos (CRUD) nosso backend utilizará o seguinte modelo de banco de dados:

![Image](bd.png)

## Endpoints a serem implementados
Para o gerenciamento de conteúdos a API deverá dispor dos seguintes endpoints:
- Consultar de conteúdos (/conteudos) [GET]
- Cadastrar conteúdo (/conteudos) [POST]
- Alterar conteúdo (/conteudos) [PUT]
- Deletar conteúdo (/conteudos/:id-exclusao) [DELETE]
- Obter um conteudo (/conteudos/:id-conteudo) [GET]

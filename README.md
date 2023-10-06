# consultas-sql
Projeto de consultas em SQL

**Objetivos:**
- Estudar tabelas
- Encontrar o número de livros lançados depois de 1 de janeiro de 2000
- Encontrar o número de avaliações e a classificação média para cada livro
- Identificar a editora que lançou o maior número de livros com mais de 50 páginas
- Identificar o autor com a média mais alta classificação de livros (livros com pelo menos 50 classificações)
- Encontrar o número médio de avaliações entre usuários que classificaram mais do que 50 livros

### Descrição dos dados:

**books — livros:** 

Contém dados sobre livros

- `book_id` — identificador do livro
- `author_id` — identificador do autor
- `title` — título
- `num_pages` — número de páginas
- `publication_date` — data de publicação
- `publisher_id` — identificador da editora

**authors — autores:**

Contém dados sobre os autores:

- `author_id` — identificador do autor
- `author` — autor

**publishers — editoras:** 

Contém dados sobre editoras:

- `publisher_id` — identificador da editora
- `publisher` — editora

**ratings — classificações:** 

Contém dados sobre classificação dos usuários:

- `rating_id` — identificador da classificação
- `book_id` — identificador do livro
- `username` — o nome do usuário que avaliou o livro
- `rating` — classificação

**reviews — avaliação:**

Contém dados sobre revisão dos clientes:

- `review_id` — identificador da revisão
- `book_id` — identificador do livro
- `username` — o nome do usuário que revisou o livro
- `text` — o texto da revisão

### Bibliotecas usadas:
- pandas
- sqlalchemy

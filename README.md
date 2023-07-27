# This is my first Golang Rest Api without database.

* [Get Book](README.md) : `GET /api/books/`
* [Get Books](README.md) : `GET /api/books/:id/`
* [Create Book](README.md) : `POST /api/books`
* [Update Book](README.md) : `PUT /api/books:id/`
* [Delete Book](README.md) : `DELETE /api/books:id/`

# Docker

#### Using docker-compose
 * ```docker compose up```

#### Using docker command
 * ```docker build -t crudapi-golang -f docker/multistage.Dockerfile .```
 * ```docker run -d -p 8000:8000 crudapi-golang```
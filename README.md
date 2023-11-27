# E-commerce API
## Getting Started

### Setup environment

```sh
cd ecommerce-api
docker-compose up
cp .env.example .env
sqlx database create
sqlx migrate run
cargo run
```

### Run dev server

```sh
cargo run
```

or

```sh
cargo install cargo-watch
cargo watch -x run
```

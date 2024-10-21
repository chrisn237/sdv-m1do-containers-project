
FROM rust:1.82 AS builder
WORKDIR /app
COPY . .
RUN cargo build --release
CMD ["cargo","run"]

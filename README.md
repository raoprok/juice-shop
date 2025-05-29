# Build container image
```bash
cd app
git clone https://github.com/juice-shop/juice-shop.git
docker build -t juice-shop:v1 .
docker run --rm -p 127.0.0.1:3000:3000 juice-shop:v1
```

# Run docker compose
```bash
cd modsecurity
docker-compose up -d
```
# portfolio

Portfolio Võ Hoàng Sơn · Store Detailing — trang một file (`index.html`).

## Chạy bằng Docker (cổng 3000)

```bash
docker compose up -d --build
```

Mở http://localhost:3000

Hoặc không dùng compose:

```bash
docker build -t portfolio .
docker run -d -p 3000:3000 --name portfolio portfolio
```

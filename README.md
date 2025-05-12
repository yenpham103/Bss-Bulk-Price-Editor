# Bss Bulk Price Editor

Đây là một ứng dụng Shopify sử dụng Next.js và Prisma để xây dựng backend linh hoạt và frontend hiện đại.

## 🚀 Hướng dẫn cài đặt & chạy app

```bash
npm install
npm run db:create
npx prisma db push
npm run cloudflare
npm run update:config
npm run dev
```

## ⚙️ Yêu cầu môi trường

- Node.js >= 18
- Database: MySQL
- Shopify Partner Account và một app đã tạo

## 📝 Ghi chú

Kiểm tra file `.env` và đảm bảo bạn đã cấu hình đúng các biến môi trường như:

```env
DATABASE_URL=
SHOPIFY_API_KEY=
SHOPIFY_API_SECRET=
SHOPIFY_SCOPES=
SHOPIFY_APP_URL=
```

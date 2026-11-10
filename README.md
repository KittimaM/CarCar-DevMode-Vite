# CarCar-DevMode-Vite

โคลนจาก `CarCar-DevMode` โปรเจกต์เดิมยังเป็น CRA ที่ `c:\xampp\htdocs\CarCar-DevMode` (ไม่แก้)

## รัน development

```bash
cd node-api && npm install && npm run dev
cd admin-web && npm install && npm run dev    # http://localhost:3000
cd customer-web && npm install && npm run dev # http://localhost:3001
```

## Environment

- Frontends ใช้ `VITE_*` (ดู `.env.example` ในแต่ละแอป)
- ใช้ API ร่วมกับโปรเจกต์เดิมได้ที่ `http://localhost:5000/`
- ถ้ารัน `node-api` สองตัวพร้อมกัน ตั้ง `PORT=5001` ใน `.env` ของ API ในโฟลเดอร์นี้ แล้วอัปเดต `VITE_NODE_API_URL`

## Build

```bash
npm run build   # ใน admin-web หรือ customer-web
npm run preview
```

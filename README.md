# Member Frontend - React + Vite + Tailwind CSS

โปรเจค Frontend สำหรับระบบจัดการข้อมูล Member, Products, Orders

Git Clone : Projects

```bash
[git clone <repository-url>
cd member-frontend](https://github.com/MarkRachChanon/make-api-call-sample-frontendPart.git)
```

## 🚀 เทคโนโลยีที่ใช้

- React 18
- Vite
- Tailwind CSS
- React Router DOM
- Axios

## 📦 การติดตั้ง

### 1. Clone โปรเจค
```bash
git clone <repository-url>
cd member-frontend
```

### 2. ติดตั้ง Dependencies
```bash
npm install
```

### 3. รันโปรเจค
```bash
npm run dev
```

เปิดเบราว์เซอร์ที่: http://localhost:5173

## 📁 โครงสร้างโปรเจค
```
member-frontend/
├── src/
│   ├── components/      # คอมโพเนนต์ที่ใช้ร่วมกัน
│   │   ├── Navbar.jsx   # เมนูด้านบน
│   │   └── Footer.jsx   # ส่วนท้าย
│   ├── pages/           # หน้าต่าง ๆ
│   │   ├── Home.jsx     # หน้าแรก
│   │   ├── Members.jsx  # หน้าจัดการสมาชิก
│   │   ├── Products.jsx # หน้าจัดการสินค้า
│   │   └── Orders.jsx   # หน้าจัดการคำสั่งซื้อ
│   ├── services/        # บริการ API
│   │   └── api.js       # Axios configuration
│   ├── App.jsx          # Component หลัก
│   ├── main.jsx         # Entry point
│   └── index.css        # Tailwind CSS
└── README.md
```

## 🎯 หน้าต่าง ๆ ในระบบ

- `/` - หน้าแรก
- `/members` - จัดการสมาชิก
- `/products` - จัดการสินค้า
- `/orders` - จัดการคำสั่งซื้อ

## 📝 หมายเหตุ

โปรเจคนี้เป็น **Part 1** สำหรับนักศึกษา Clone ไปใช้งาน

ใน **Part 2** จะเพิ่ม:
- การเชื่อมต่อกับ Backend API
- CRUD Operations
- การแสดงข้อมูล
- Form สำหรับเพิ่ม/แก้ไข/ลบข้อมูล

## 🔗 Backend API

Backend API: http://localhost:4000

- Members: http://localhost:4000/members
- Products: http://localhost:4000/products
- Orders: http://localhost:4000/orders
- API Docs: http://localhost:4000/api-docs

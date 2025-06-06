# Book-Website-Personal-Project
This is a passionate website that I created to sell book

Book-Website-Personal-Project/
├── public/
│   ├── index.html               # Trang chính (trang chủ)
│   ├── favicon.ico
│   ├── pages/                   # 📁 Thư mục chứa các trang con
│   │   ├── about.html
│   │   ├── products.html
│   │   └── contact.html
│   └── assets/
│       ├── favicon/            ← ✅ Thư mục favicon riêng
│       │   ├── favicon.ico
│       │   ├── favicon-32x32.png
│       │   ├── favicon-16x16.png
│       │   ├── apple-touch-icon.png
│       │   └── site.webmanifest
│       ├── images/
│       ├── fonts/
│       └── icons/
├── src/
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   ├── main.js              # Chèn header/footer cho mọi trang
│   │   ├── api.js               # Gọi API nếu cần
│   │   └── components/
│   │       ├── header.js
│   │       ├── footer.js
│   │       └── card.js          # Ví dụ component cho sản phẩm
├── dist/                        # (nếu dùng bundler: Vite/Webpack)
├── package.json                 # npm dependencies
├── tailwind.config.js           # (nếu dùng Tailwind)
└── README.md

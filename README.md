# TPIT Profile Website

Website profile cá nhân của Huỳnh Tấn Phát.

## Deploy lên Vercel

### Cách 1: Deploy qua Vercel Dashboard (Khuyến nghị)

1. **Tạo tài khoản Vercel**
   - Truy cập [vercel.com](https://vercel.com)
   - Đăng ký tài khoản mới hoặc đăng nhập bằng GitHub

2. **Import project**
   - Click "New Project"
   - Chọn "Import Git Repository"
   - Kết nối với GitHub repository chứa code này
   - Vercel sẽ tự động detect đây là static website

3. **Deploy**
   - Click "Deploy"
   - Website sẽ được deploy và có URL dạng: `https://your-project-name.vercel.app`

### Cách 2: Deploy qua Vercel CLI

1. **Cài đặt Vercel CLI**
   ```bash
   npm i -g vercel
   ```

2. **Login vào Vercel**
   ```bash
   vercel login
   ```

3. **Deploy**
   ```bash
   vercel
   ```

### Cách 3: Deploy trực tiếp từ thư mục

1. **Kéo thả thư mục**
   - Truy cập [vercel.com/new](https://vercel.com/new)
   - Kéo thả toàn bộ thư mục project vào
   - Vercel sẽ tự động deploy

## Cấu trúc Project

```
├── index.html          # Trang chính
├── assets/             # Thư mục chứa tài nguyên
│   ├── css/           # Stylesheets
│   ├── js/            # JavaScript files
│   ├── img/           # Images
│   ├── music/         # Audio files
│   └── video/         # Video files
├── vercel.json        # Cấu hình Vercel
└── README.md          # Hướng dẫn này
```

## Tính năng

- ✅ Responsive design
- ✅ Dark/Light mode
- ✅ Loading animation
- ✅ Smooth scrolling
- ✅ Modern UI/UX

## Liên hệ

- Facebook: [Phatdeptry.IT](https://facebook.com/Phatdeptry.IT)
- Location: Ho Chi Minh City, Vietnam

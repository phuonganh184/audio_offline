# Truyện Audio (PWA + Firebase)

## 1. Firebase
1. console.firebase.google.com → tạo dự án → thêm **Web app** → copy `firebaseConfig` vào `firebase-config.js`.
2. Build → **Authentication** → Sign-in method → bật **Google**.
3. Authentication → Settings → **Authorized domains** → thêm `TENBAN.github.io`.
4. Build → **Firestore Database** → Create (chế độ production) → tab **Rules** → dán nội dung `firestore.rules` → Publish.

## 2. GitHub Pages
1. Tạo repo, upload toàn bộ file trong thư mục này (đặt ở thư mục gốc repo).
2. Settings → Pages → Deploy from branch → `main` / root.
3. Mở `https://TENBAN.github.io/TEN-REPO/` → trình duyệt/điện thoại chọn **Cài đặt / Thêm vào màn hình chính**.

## Khi sửa code
Đổi `V='ta-v1'` trong `sw.js` thành `ta-v2`… để máy cũ nhận bản mới.

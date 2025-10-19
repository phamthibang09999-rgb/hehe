HƯỚNG DẪN TRIỂN KHAI NHANH (GitHub + Vercel)
1) Tạo repository mới trên GitHub: https://github.com/new
   - Repository name: hehe
   - Public
2) Upload toàn bộ nội dung thư mục 'hehe-website' vào repo (bấm Add file -> Upload files)
   - Đảm bảo có file index.html ở gốc repo.
3) Vào https://vercel.com/new
   - Click "Continue with GitHub", cho phép Vercel truy cập repo.
   - Chọn Git Namespace (tài khoản của bạn), tìm repo 'hehe' và bấm Import.
   - Framework Preset: chọn "Other". Rồi bấm Deploy.
4) Sau khi Deploy hoàn tất, site sẽ live tại https://<your-project-name>.vercel.app
   - Nếu bạn đặt tên project là 'hehe', link sẽ là: https://hehe.vercel.app
5) Mọi người mở link sẽ thấy ngay nội dung (đã embed data và YouTube autoplay cố gắng phát nhạc).

LƯU Ý:
- Một số trình duyệt chặn autoplay âm thanh: nếu không nghe nhạc tự động, người xem có thể cần nhấn play trong iframe nhỏ ở góc phải hoặc tương tác với trang trước.
- Bạn có thể chỉnh sửa nội dung bằng cách cập nhật file index.html trong repo trên GitHub, Vercel sẽ tự deploy bản mới.

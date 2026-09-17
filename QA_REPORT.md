# HSK Go V4.6 – QA Report

- Font giao diện: Nunito (mềm, bo tròn, thân thiện) với fallback hệ thống.
- Font Hán tự: Noto Sans SC, fallback Microsoft YaHei / PingFang SC.
- Giữ nguyên kiểm tra dữ liệu HSK: 2.245 từ.
- Giữ nguyên 310 thuật ngữ Điện – Tự động hóa.
- Giữ nguyên phần Lượng từ 163 cách dùng.
- Không có ID HTML trùng.
- Toàn bộ JavaScript inline đã qua `node --check`.
- Service Worker đổi cache sang `hsk-go-v4-6-font` để tránh giữ giao diện cũ.
- Khi offline và font web chưa từng được tải, ứng dụng tự dùng font fallback trên thiết bị; chức năng học không bị ảnh hưởng.

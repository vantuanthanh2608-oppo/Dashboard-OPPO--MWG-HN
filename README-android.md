# App Android OPPO HN

Vỏ Android (Trusted Web Activity) mở `https://hn.oppovn.com/trungtamdieuhanhOPPOHN/` bằng Chrome:
thông báo đẩy, định vị, tải / mở file Excel chạy như trên web. Cập nhật `index.html` trên máy chủ là app có bản mới, không phải cài lại.

- `android-app/`: project Android (package `com.oppohn.dieuhanh`).
- `.github/workflows/android-apk.yml`: GitHub Actions tự build khi đẩy lên nhánh `android-app`, lưu bản chưa ký vào `release/`.
- Khoá ký **không** để trên GitHub: bản chưa ký được ký bằng khoá riêng của OPPO HN rồi mới phát cho nhân sự.

# HUMAN — trang giới thiệu và chính sách quyền riêng tư

Repo này **chỉ** chứa trang tĩnh. Mã nguồn ứng dụng nằm ở repo riêng, không công khai.

- Trang giới thiệu: https://mittohoa.github.io/human-app/
- Chính sách riêng tư: https://mittohoa.github.io/human-app/privacy/
- Ứng dụng: `com.humanapp.human`

## Đừng sửa tay `privacy/index.html`

Nó được **sinh tự động** từ `docs/PRIVACY.md` trong repo mã nguồn:

```bash
python tool/build_privacy_page.py
```

CI của repo mã nguồn chạy `--check` mỗi lần đẩy mã, nên hai bản lệch nhau là
build đỏ. Sửa nội dung ở file gốc, đừng sửa ở đây.

## File APK

Đính kèm trong phần Releases, không nằm trong lịch sử git.

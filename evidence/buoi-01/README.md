# Minh chứng Buổi 1

Thư mục này dùng để nộp minh chứng thiết lập môi trường lab.

---

## Sinh viên điền thông tin

* **Họ tên:** Trương Hữu Vinh
* **Mã sinh viên:** 1771020759
* **Nhóm:** 6B
* **Vai trò dự kiến trong nhóm:** Backend Developer (phụ trách Core Business Service)
* **Hệ điều hành:** Windows 10 (PowerShell + Docker Desktop)
* **Ghi chú:** Đã cài đặt đầy đủ Git, Docker, Docker Compose, Node.js và Python. Docker hoạt động bình thường (đã test với hello-world).

---

## Các file minh chứng

Sau khi chạy script, thư mục `evidence/buoi-01/` bao gồm:

* `tool-versions.txt` → Thông tin phiên bản Git, Docker, Node.js, Python
* `docker-version.txt` → Thông tin Docker Engine
* `compose-version.txt` → Thông tin Docker Compose
* `hello-world.txt` → Kết quả chạy container hello-world
* `smoke-test-result.txt` → Kết quả kiểm tra môi trường lab
* `image-list.txt` → Danh sách Docker image đã tải
* `git-log.txt` → Lịch sử commit gần nhất
* `checklist.md` → Checklist tự đánh giá
* `known-issues.md` → Các lỗi (nếu có)

---

## Cách sinh file minh chứng

### Windows (PowerShell)

```powershell
.\scripts\collect_session01_evidence.ps1
```

---

### macOS / Linux

```bash
./scripts/collect_session01_evidence.sh
```

---

## Trạng thái hoàn thành

* [x] Cài đặt Git
* [x] Cài đặt Docker & Docker Compose
* [x] Cài đặt Node.js
* [x] Cài đặt Python
* [x] Chạy thành công `docker run hello-world`
* [x] Tải Docker images cần thiết
* [x] Chạy smoke test môi trường
* [x] Sinh đầy đủ thư mục `evidence/buoi-01/`
* [x] Sẵn sàng commit và push lên GitHub

---

## Kết luận

Môi trường đã được thiết lập hoàn chỉnh và sẵn sàng cho các buổi học tiếp theo.
Docker hoạt động ổn định, các công cụ cần thiết đã được cài đặt đầy đủ và kiểm tra thành công.

---

# Lê Bảo Tú - Sản phẩm AI

Bộ sưu tập sản phẩm dạy học của **Lê Bảo Tú**, giáo viên Tin học, Trường Tiểu học Huỳnh Ngọc Huệ (158 Hà Huy Tập, Phường Thanh Khê, Thành phố Đà Nẵng).

Kho này là **nguồn lưu trữ** và **bản dự phòng** trên GitHub Pages. Bản đang dùng hằng ngày vẫn chạy trên sharehtml.org. Nếu trang đó gặp sự cố, mở link GitHub Pages bên dưới — mỗi sản phẩm vẫn chạy được, kể cả khi không có mạng (trừ vài tính năng cần Internet, xem ghi chú).

- Bản dự phòng (GitHub Pages): https://lebaotu.github.io/baotu-ai/
- Sân chơi tri thức (bản chính): https://3w7n68w.sharehtml.org/

## Danh sách sản phẩm

| STT | Tên | Bản chính | Bản dự phòng |
| ---: | --- | --- | --- |
| | [Sân chơi tri thức](https://lebaotu.github.io/baotu-ai/) (trang chủ bộ sưu tập) | [sharehtml](https://3w7n68w.sharehtml.org/) | [GitHub](https://lebaotu.github.io/baotu-ai/) |
| 1 | Phi thuyền vũ trụ | [sharehtml](https://rfti9mv.sharehtml.org/) | [GitHub](https://lebaotu.github.io/baotu-ai/001-phi-thuyen-vu-tru/) |
| 2 | Hái quả tri thức | [sharehtml](https://s1nzd90.sharehtml.org/) | [GitHub](https://lebaotu.github.io/baotu-ai/002-hai-qua-tri-thuc/) |
| 3 | Vũ điệu tri thức | [sharehtml](https://ikldoug.sharehtml.org/) | [GitHub](https://lebaotu.github.io/baotu-ai/003-vu-dieu-tri-thuc/) |
| 4 | Đua thuyền tri thức | [sharehtml](https://7h0h3x6.sharehtml.org/) | [GitHub](https://lebaotu.github.io/baotu-ai/004-dua-thuyen-tri-thuc/) |
| 5 | Kéo co tri thức | [sharehtml](https://rnuhf7t.sharehtml.org/) | [GitHub](https://lebaotu.github.io/baotu-ai/005-keo-co-tri-thuc/) |
| 6 | Chuyến đò tri ân | [sharehtml](https://s1j6i7m.sharehtml.org/) | [GitHub](https://lebaotu.github.io/baotu-ai/006-chuyen-do-tri-an/) |
| 7 | Ngôi Sao Lớp Em | [sharehtml](https://rqlxac9.sharehtml.org/) | [GitHub](https://lebaotu.github.io/baotu-ai/007-ngoi-sao-lop-em/) |
| 8 | Sổ Tay Phòng Tin Số | [sharehtml](https://7y5mw9a.sharehtml.org/) | [GitHub](https://lebaotu.github.io/baotu-ai/008-so-tay-phong-tin-so/) |

Trên Sân chơi tri thức, mỗi thẻ có nút **Bản dự phòng** để chuyển nhanh sang bản còn lại.

## Ghi chú khi dùng bản dự phòng

- Đây là các trang HTML chạy ngay trên trình duyệt. Dữ liệu (danh sách lớp, nhật ký phòng máy, điểm sao…) được lưu **trong trình duyệt** (`localStorage` / IndexedDB) theo từng địa chỉ trang. Bản GitHub và bản sharehtml là hai địa chỉ khác nhau, nên dữ liệu **không tự chuyển** sang nhau.
- **Ngôi Sao Lớp Em** và **Sổ Tay Phòng Tin Số** vẫn đồng bộ được qua cầu nối Google Drive (Apps Script) hoặc tệp sao lưu thủ công. Lần đầu mở trên GitHub, hãy dán lại địa chỉ cầu nối (mã NSLB1 / STPS1 hoặc tài khoản dự phòng) rồi đồng bộ từ Drive, hoặc khôi phục từ tệp đã sao lưu.
- **Vũ điệu tri thức** cần Internet để tải thư viện nhận diện động tác (TensorFlow) và cần quyền camera. **Phi thuyền vũ trụ** / **Hái quả tri thức** chỉ cần Internet khi nhập file Word hoặc chơi ghép máy qua mạng. Các trò còn lại chạy offline sau khi trang đã mở.
- Kho này **không** chứa khóa quản lý trang sharehtml, địa chỉ quản trị, hay tệp `publish.json`.

## Cập nhật kho

Khi một sản phẩm được cập nhật trên bản chính, chạy script:

`/workspace/github-mirror/sync.sh`

Script tải lại đúng bản đang chạy trên sharehtml.org (không lấy bản chưa duyệt trên máy), kiểm tra không lẫn khóa, rồi đẩy lên GitHub Pages.

---

Tác giả: Lê Bảo Tú · Giáo viên Tin học · Trường Tiểu học Huỳnh Ngọc Huệ

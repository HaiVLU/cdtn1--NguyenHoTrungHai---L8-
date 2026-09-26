# <Tên phạm vi bằng một câu>
Sinh viên: Nguyễn Hồ Trung Hải - 2374802010125 - Track SE, DA
Học phần:
Chuyên đề Tốt nghiệp 1, HK1 2026-2027
Luồng nghiệp vụ:
L8 – Khảo sát hài lòng CSAT / NPS
# L8 - Khảo sát hài lòng CSAT/NPS

## 1. Mục tiêu

Hệ thống hỗ trợ theo dõi mức độ hài lòng của khách hàng sau khi phiếu bảo hành được đóng thông qua khảo sát CSAT/NPS.

Hệ thống tổng hợp kết quả theo trung tâm, kỹ thuật viên và thời gian, phục vụ Marketing, Quản lý trung tâm và Ban giám đốc.

Dữ liệu được phân quyền theo vai trò và đảm bảo lưu giữ lịch sử khảo sát.

## 2. Yêu cầu môi trường

- Python 3.11
- PostgreSQL 16
- Git

Biến môi trường: xem file `.env.example`.

## 3. Hướng dẫn chạy

Hiện tại project đang ở giai đoạn khởi tạo.

Các bước dự kiến:

1. Sao chép `.env.example` thành `.env` và điền thông tin cần thiết.
2. Cài đặt các thư viện phụ thuộc.
3. Khởi tạo/cập nhật cơ sở dữ liệu.
4. Chạy ứng dụng và kiểm tra endpoint `/health`.

## 4. Cấu trúc thư mục

```text
L8/
├── .env.example       # Mẫu biến môi trường
├── .gitignore         # Các file/thư mục không đưa lên Git
├── README.md          # Tài liệu hướng dẫn project
├── p/                 # Tài liệu hoặc tài nguyên phục vụ project
├── data/              # Dữ liệu mẫu/dữ liệu mô phỏng
├── docs/              # Tài liệu đặc tả và tài liệu liên quan
│   ├── ai-disclosure.md
│   └── srs.md
├── src/               # Mã nguồn chính của hệ thống
└── tests/             # Các test case của hệ thống




## 5. Kiểm thử
Hiện tại project đang ở giai đoạn khởi tạo.

Sau khi hoàn thành phần mã nguồn và test, sử dụng lệnh kiểm thử của project để kiểm tra số lượng test PASS/FAIL.

Các quy tắc nghiệp vụ chính cần kiểm thử:

QT-10: Chỉ gửi khảo sát cho phiếu đã đóng và mỗi phiếu chỉ được khảo sát một lần.
QT-13: Không xóa vật lý phiếu bảo hành, đơn hàng hoặc hồ sơ khách hàng.
QT-14: Người dùng chỉ được xem dữ liệu theo phạm vi quyền của mình.
QT-15: Số điện thoại khách hàng được che theo vai trò.

## 6. Trạng thái hiện tại
☑ Khởi tạo project và cấu trúc thư mục (buổi 2)
☑ Tạo .gitignore và .env.example
☑ Tạo tài liệu SRS
☑ Tạo tài liệu AI Disclosure
 Thiết kế cơ sở dữ liệu khảo sát CSAT/NPS
 Xây dựng chức năng khảo sát
 Xây dựng chức năng tổng hợp CSAT/NPS
 Phân quyền dữ liệu theo vai trò
 Kiểm thử QT-10, QT-13, QT-14, QT-15

📊 Dự án: Phân Tích Dữ Liệu COVID-19 với Pandas
📝 Mô tả
Dự án này sử dụng thư viện Pandas trong Python để xử lý và phân tích dữ liệu dịch bệnh COVID-19 trên toàn cầu. Mục tiêu chính là làm sạch dữ liệu, tính toán các chỉ số quan trọng (như tỷ lệ tử vong), và xác định những quốc gia bị ảnh hưởng nặng nề nhất.

🧰 Công nghệ sử dụng
Python

Pandas

(Tuỳ chọn mở rộng: Matplotlib, Seaborn)

📁 Dữ liệu đầu vào
File CSV có cấu trúc gồm các cột:

quoc_gia: tên quốc gia

so_ca_nhiem: tổng số ca nhiễm

so_tu_vong: tổng số ca tử vong

ngay: ngày cập nhật (nếu có)

🔍 Các bước thực hiện
Đọc dữ liệu từ file CSV bằng pandas.read_csv()

Kiểm tra và làm sạch dữ liệu (loại bỏ giá trị thiếu)

Tính toán tỷ lệ tử vong = (tử vong / ca nhiễm) × 100

Lọc những quốc gia có hơn 1 triệu ca nhiễm

Sắp xếp và hiển thị top 10 quốc gia có tỷ lệ tử vong cao nhất

📌 Kết quả đầu ra
Danh sách top các quốc gia có tỷ lệ tử vong cao, giúp người xem hiểu rõ hơn về mức độ ảnh hưởng của đại dịch.

🚀 Hướng phát triển tiếp theo
Trực quan hóa dữ liệu bằng biểu đồ

Phân tích theo thời gian (nếu dữ liệu có theo ngày)

So sánh theo từng châu lục hoặc khu vực

📬 Liên hệ
Nguyễn Đăng Khoa – Sinh viên CNTT – FPT Polytechnic
📧 khoa.nguyen@example.com (thay bằng email thật của bạn)

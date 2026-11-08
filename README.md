# Mid-term 2 – Project 2: Bank Marketing Dataset (Nhóm 16)

Phân tích dữ liệu tiếp thị của một ngân hàng để tìm yếu tố làm tăng khả năng khách hàng đăng ký tiền gửi kỳ hạn (`deposit`).

- **Dữ liệu:** [Bank Marketing Dataset – Kaggle (janiobachmann)](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset), file `bank.csv` (11.162 dòng × 17 cột).
- **Quy trình:** 4 giai đoạn: (1) thu thập và đánh giá dữ liệu, (2) tiền xử lý và làm sạch, (3) phân tích và trực quan hóa, (4) đánh giá tác động và khuyến nghị.

## Nội dung repo

| File | Mô tả |
|---|---|
| `NHOM16_PRJ2_MID_TERM_FINAL.ipynb` | Notebook chính, đã chạy sẵn kết quả (hình và bảng nằm ngay trong notebook) |
| `bank.csv` | Dữ liệu gốc |
| `NHOM16_PRJ2_BaoCao.pdf` | Báo cáo PDF |

## Cách chạy lại trên Google Colab

1. Vào [colab.research.google.com](https://colab.research.google.com), chọn **File → Upload notebook**, rồi chọn file `NHOM16_PRJ2_MID_TERM_FINAL.ipynb`.
2. Chọn **Runtime → Run all**. Notebook tự đọc `bank.csv` từ repo GitHub này, không cần sửa code.
3. Nếu Colab không kết nối được GitHub, hãy upload `bank.csv` vào Colab (biểu tượng thư mục bên trái) rồi chạy lại; notebook sẽ đọc file đó.

Ghi chú: khi chạy, notebook tự tạo thư mục `figures/` chứa các hình PNG. Ô cuối cùng nén thư mục này thành `figures.zip` và tự tải về máy khi chạy trên Colab.

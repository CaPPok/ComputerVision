# HCMUT - Xử lý ảnh số và Thị giác máy tính

## Module 1: Biểu diễn ảnh màu và ảnh xám
- Chuyển đổi giữa ảnh màu (RGB) và ảnh xám  
- Tách và kết hợp các kênh màu R, G, B  
- Phân tích vai trò của từng kênh màu trong ảnh  

## Module 2: Lọc ảnh với Low-pass và High-pass Filter
- Low-pass filter để làm trơn và giảm nhiễu  
- High-pass filter để phát hiện biên và chi tiết ảnh  
- So sánh và đánh giá kết quả trên nhiều ảnh khác nhau  

## Hướng dẫn chạy chương trình

### Tạo môi trường Python
```bash
python -m venv venv
source venv/bin/activate      # Linux / MacOS
venv\Scripts\activate         # Windows

### Cài thư viện cần thiết
```bash
pip install numpy opencv-python matplotlib jupyter

### Chạy jupyter
```bash
jupyter notebook

Mở các file .ipynb trong từng module để chạy chương trình.
# HCMUT - Xử lý ảnh số và Thị giác máy tính

## [Module 1: Biểu diễn ảnh màu và ảnh xám](module1.ipynb)
Module 1 được chạy trong script "module1.ipynb"
- Chuyển đổi giữa ảnh màu (RGB) và ảnh xám  
- Tách và kết hợp các kênh màu R, G, B  
- Phân tích vai trò của từng kênh màu trong ảnh  

## [Module 2: Lọc ảnh với Low-pass và High-pass Filter](module2.ipynb)
Module 2 được chạy trong script "module2.ipynb"
- Low-pass filter để làm trơn và giảm nhiễu  
- High-pass filter để phát hiện biên và chi tiết ảnh  
- So sánh và đánh giá kết quả trên nhiều ảnh khác nhau  

## Thay đổi ảnh đầu vào
Trong mỗi file `.ipynb`, đường dẫn ảnh đầu vào được khai báo thông qua biến `img_path`.

Người dùng có thể **thay đổi giá trị của `img_path`** để thử nghiệm với các ảnh khác trong repository, ví dụ:

```python
img_path = "flower.jpg"
# hoặc
img_path = "noise.jpg"
# hoặc
img_path = "scenery.jpg"
# hoặc
...
```

## Git clone repository
```bash
git clone https://github.com/CaPPok/ComputerVision.git
cd ComputerVision
```

## Hướng dẫn chạy chương trình

### Tạo môi trường Python
```bash
python -m venv venv
source venv/bin/activate      # Linux / MacOS
venv\Scripts\activate         # Windows
```

### Cài thư viện cần thiết
```bash
pip install numpy opencv-python matplotlib jupyter
```

### Chạy jupyter
```bash
jupyter notebook
```

Mở các file .ipynb của từng module để chạy chương trình.
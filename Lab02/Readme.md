#  Basic Image Manipulation with OpenCV

##  Mô tả

Bài thực hành này giới thiệu các thao tác cơ bản trong xử lý ảnh số bằng thư viện **OpenCV** và **NumPy** trong Python. Nội dung tập trung vào việc thao tác trực tiếp trên ma trận ảnh (image array) như sao chép ảnh, lật ảnh, cắt ảnh và thay đổi pixel.

---

##  Mục tiêu

Sau khi hoàn thành bài thực hành, người học có thể:

* Hiểu cách lưu trữ ảnh dưới dạng mảng NumPy
* Tránh hiện tượng aliasing khi sao chép ảnh
* Lật ảnh theo trục x và trục y
* Cắt (crop) ảnh theo vùng xác định
* Thay đổi pixel, vẽ hình và chèn chữ lên ảnh

---

##  Công nghệ sử dụng

* Python 3
* OpenCV (`cv2`)
* NumPy
* Matplotlib

---

##  Dữ liệu sử dụng

Các ảnh mẫu:

* `baboon.png`
* `cat.png`
* `lenna.png`
* `messi.png` (ảnh tự chọn)

---

##  Nội dung chính

### 1. Copy ảnh

* Sử dụng `copy()` để tránh aliasing
* So sánh vùng nhớ giữa các biến ảnh

### 2. Lật ảnh (Flipping)

* Lật dọc ảnh theo trục x (`flipcode = 0`)
* Lật ngang ảnh theo trục y (`flipcode = 1`)
* Lật cả hai trục (`flipcode = -1`)

### 3. Crop ảnh

* Cắt ảnh theo chiều dọc và chiều ngang bằng slicing NumPy

### 4. Thay đổi pixel

* Gán giá trị pixel về 0
* Vẽ hình chữ nhật bằng `cv2.rectangle()`
* Chèn chữ lên ảnh bằng `cv2.putText()`

---

##  Question 4 – Flip & Mirror Image

* Đọc ảnh (`messi.png`)
* Chuyển từ BGR sang RGB
* Lật ảnh theo trục x (vertical flip)
* Lật ảnh theo trục y (horizontal mirror)
* Hiển thị kết quả bằng matplotlib

---

##  Cách chạy

1. Cài đặt thư viện cần thiết:

```bash
pip install opencv-python numpy matplotlib
```

2. Mở file notebook và chạy lần lượt các cell.

---

##  Tài liệu tham khảo

* OpenCV Documentation: [https://opencv.org/](https://opencv.org/)
* Digital Image Processing – Gonzalez & Woods
* IBM Skills Network – Computer Vision

---



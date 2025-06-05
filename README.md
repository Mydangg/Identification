 Nhận Diện Cảm Xúc & Giới Tính Khuôn Mặt
Dự án này là một ứng dụng sử dụng học sâu (deep learning) để nhận diện cảm xúc và giới tính từ hình ảnh hoặc video thời gian thực bằng mạng nơ-ron tích chập (CNN) và OpenCV. Các mô hình đã được huấn luyện trên các bộ dữ liệu công khai (ví dụ: FER2013) và được lưu ở định dạng .h5.

 Công Nghệ Sử Dụng
Python
TensorFlow / Keras
OpenCV
Jupyter Notebook
NumPy, Pandas, Matplotlib

 Chi Tiết Mô Hình
Nhận Diện Cảm Xúc
Dataset: FER2013
Lớp phân loại: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral
Kiến trúc mô hình: CNN với các lớp Conv2D, MaxPooling và Dropout

Phân Loại Giới Tính
Lớp phân loại: Nam, Nữ
Kiến trúc mô hình: CNN tối ưu cho khuôn mặt cắt nhỏ

 Cách Chạy Ứng Dụng
1. Clone repository
git clone https://github.com/Mydangg/Identification.git
cd Identification
2. Cài đặt thư viện cần thiết
pip install -r requirements.txt
3. Chạy ứng dụng nhận diện khuôn mặt thời gian thực
python face_app.py
Ứng dụng sẽ mở webcam và bắt đầu nhận diện cảm xúc và giới tính theo thời gian thực.

 Hướng Phát Triển Tương Lai
Cải thiện độ chính xác với các mô hình sâu hơn (ResNet, MobileNet)
Thêm tính năng ước lượng tuổi
Triển khai ứng dụng trên web với Flask hoặc Streamlit
Tạo phiên bản di động với TensorFlow Lite

# Project-time-series

# 🧠 Data Science & Machine Learning
## 📌 Mục tiêu / Vấn đề
Dự đoán số lượng users trên trang web theo thời gian từng ngày

## 🛠 Các bước thực hiện chính
1.  Trực quan hóa bằng matplotlip để khám phá dữ liệu
2.  Tạo các features mới với độ trễ giảm dần từ target gốc bằng kỹ thuật sliding window
3.  Xử lý dữ liệu, chọn mô hình với lazy predict và huấn luyện các mô hình tối ưu
4.  Đánh giá mô hình và trực quan hóa lượng users mô hình dự đoán
   
## 📈 Kết quả
- Mô hình KNeighborsRegressor hoạt động tốt nhất
- R^2 đạt mức 89%

## 🔧 Công nghệ sử dụng
- Python, Pandas, Scikit-learn, Matplotlib, Pickle, LazyPredict

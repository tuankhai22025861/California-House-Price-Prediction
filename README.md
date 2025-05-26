# 🏡 California House Price Prediction

## 📋 Mô tả
Dự án này nhằm mục tiêu **dự đoán giá nhà tại bang California** dựa trên một số đặc điểm như vị trí địa lý, mật độ dân cư, thu nhập trung bình, số phòng, số hộ dân,... Dữ liệu được lấy từ tập **California Housing Dataset** thuộc thư viện `sklearn.datasets`.

## 🎯 Mục tiêu
- Xây dựng mô hình dự đoán giá nhà một cách hiệu quả.
- So sánh hiệu suất giữa **mô hình học máy có sẵn** (Linear Regression) và **mô hình tuyến tính được xây dựng thủ công** bằng cách tính toán trực tiếp các hệ số (coefficient).
- Rút ra bài học về tầm quan trọng của việc hiểu rõ bản chất mô hình toán học trong học máy, thay vì chỉ áp dụng thư viện có sẵn.

## 🔍 Các bước chính trong dự án
1. **Tiền xử lý dữ liệu**: xử lý dữ liệu bị thiếu, chuẩn hóa đặc trưng.
2. **Trực quan hóa**: khảo sát tương quan giữa các biến, phân tích phân bố dữ liệu.
3. **Huấn luyện mô hình Linear Regression** sử dụng thư viện `sklearn`.
4. **Tự tính toán hệ số hồi quy tuyến tính** bằng công thức đại số tuyến tính (Normal Equation).
5. **So sánh hiệu suất giữa 2 mô hình** dựa trên các chỉ số đánh giá như MAE, MSE, RMSE và R².
6. **Kết luận**: đánh giá tính hiệu quả và ý nghĩa của việc hiểu mô hình toán học cơ bản trong thực tế.

## 🌟 Điểm nổi bật của dự án
- **Tự xây dựng mô hình hồi quy tuyến tính từ đầu**, không sử dụng thư viện học máy — qua đó củng cố kiến thức về đại số tuyến tính và hiểu sâu cơ chế hoạt động của mô hình.
- **So sánh định lượng** giữa mô hình có sẵn và mô hình tự tính để minh chứng cho tính đúng đắn và hiệu quả của thuật toán thủ công.
- Giúp người học **nâng cao tư duy thuật toán**, thay vì chỉ áp dụng mô hình như một “hộp đen”.

## 🛠️ Công nghệ sử dụng
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## 📚 Kết luận
Dự án không chỉ cung cấp một ứng dụng thực tế trong lĩnh vực bất động sản, mà còn mang lại góc nhìn sâu sắc về cách các mô hình học máy hoạt động phía sau. Đây là một bước chuẩn bị hữu ích cho những ai muốn theo đuổi lĩnh vực **AI Engineer** hoặc **Data Scientist**, nơi không chỉ quan trọng việc sử dụng công cụ, mà còn cần hiểu rõ bản chất thuật toán để tối ưu và sáng tạo trong giải quyết vấn đề.

## 🔗 Liên kết Google Drive
Bạn có thể truy cập toàn bộ nội dung dự án tại:  
👉 [https://colab.research.google.com/drive/1_PyeJ1wryoxyXIq9_O44f8q7c8dTHwSG?usp=sharing)

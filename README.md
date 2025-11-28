I. Tiền xử lý dữ liệu
1. Thu thập dữ liệu và chuẩn hóa dữ liệu:
- Đọc dữ liệu -> kiểm tra cấu trúc (columns, type, unique values)
- Làm sạch dữ liệu 

2. Feature Engineering : Tạo thêm cột (hoặc nhóm) phù hợp

3. EDA:
- Lập biểu đồ phân bố
- Heatmap
- Biểu đồ thể hiện tăng trưởng EV

4.Bàn giao:
- file clean_ev_population.csv
- Notebook: EDA.ipynb
- Mô tả dữ liệu (Data Dictionary)


II.Phân loại & hồi quy
1. Phân loại BEV & PHEV
- train/test
- Train model
- Đánh giá 

2. Hồi quy phân tích yếu tố ảnh hưởng:
- Xây mô hình
- Tính (R^2, p-value, kiểm định độ quan trọng biến)

3. Xuất kết quả
- Biểu đồ quan trọng của biến 
- Bảng so sánh mô hinh 

4. Bàn giao
- Notebook Classification_Model.ipynb
- Notebook Regression_Analysis.ipynb
- Kết quả, bảng đánh giá


III. Dự báo tương lai
1. Chuẩn bị dữ liệu chuỗi thời gian
- Tạo series EV_Count theo: Năm, (tùy chọn) Theo khu vực
- Resample/aggregate nếu cần

2. Huấn luyện mô hình dự báo : ARIMA, Prophet

3. Đánh giá mô hình: 
- MAE
- RMSE
- So sánh mô hình

4. Trực quan hóa: 
- Biểu đồ và dự báo 
- Dự báo 5-10 năm tiếp theo

5.Bàn giao:
- Notebook EV_Forecasting.ipynb
- Biểu đồ dự báo
- File dự báo forecast.csv


IV. Phân cụm & demo:

1. Phân cụm khu vực
-Chuẩn hóa dữ liệu
- Áp dụng:
    - K-Means
    - (tùy chọn) DBSCAN
- Xác định số cụm bằng:
    - Elbow Method
    - Silhouette Score
    - Davies-Bouldin Index
    
2. Trực quan hóa
- Biểu đồ scatter
- Map chart (nếu có tọa độ hoặc state-level)

3. Xây ứng dụng Demo
- Ứng dụng có tính năng:
- Tải dữ liệu lên
- Hiển thị biểu đồ EDA
- Phân loại BEV/PHEV (dùng model của Người 2)
- Dự báo số lượng EV (dùng model của Người 3)
- Hiển thị bản đồ phân cụm (của Người 4)
- Xuất báo cáo PDF
- Ứng dụng xây bằng:
- Streamlit / Flask / Dash / React

4. Bàn giao
- Folder app/
- File run_app.py



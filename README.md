I. Data Preprocessing + EDA + Feature Engineering
1. Tiền xử lý dữ liệu:
- Làm sạch dữ liệu, xử lý missing, duplicates
- Chuẩn hóa kiểu dữ liệu

2. EDA:

3. Feature Engineering:
   - Tạo EV_Count theo Year
   - Tạo EV_Count theo State/City
4. Bàn giao clean dataset cho cả nhóm

II. Classification (BEV/PHEV) + Report đánh giá
1. Chuẩn bị dữ liệu cho classification
2. Huấn luyện các mô hình:
   - Logistic Regression
   - Decision Tree
   - Random Forest
3. Đánh giá:
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix
4. So sánh các model (prettytable)

III. Time-series Forecasting (EV Count vs Year)
1. Tạo chuỗi thời gian EV per year
2. Huấn luyện 2 mô hình
   - ARIMA
   - Prophet
3. Dự đoán 5-10 năm tiếp theo
4. Đánh giá
5. Vẽ biểu đồ actual và predicted

IV . Clustering + Visualization
1. Tạo dữ liệu EV_Count theo khu vực (từ dataset của Người 1)
2. Chuẩn hóa dữ liệu clustering
3. Huấn luyện K-Means 3–5 cụm
4. Đánh giá:
   - Silhouette Score
   - Davies-Bouldin Index
5. Trực quan hóa:
   - Scatter clustering

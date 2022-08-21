### Dataset

###### Some information

- visualize_location.ipynb: Hiện thị vị trí các trạm đo trên map
- predict_24.ipynb: Huấn luyện mô hình dự đoán 24h tiếp theo của 1 trạm với dữ liệu đã biết của trạm đó (11 trạm đã biết)
- model.py: Kết hợp model predict_24 để dự đoán 24h sắp tới của 11 trạm và mạng GCN để tổng hợp lại giá trị 24h sắp tới của trạm chưa biết dựa vào thông tin về tọa độ. Trong đó mô hình predict_24 được freezing trong vài epoch đầu.
### Evaluate
- Chạy file evalutate.ipynb để tạo ra thư mục predict
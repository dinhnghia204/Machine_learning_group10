
# Dự Báo Nhu Cầu Hàng Tồn Kho Sử Dụng Machine Learning

## Giới Thiệu
Dự báo nhu cầu hàng tồn kho là một yếu tố quan trọng trong việc quản lý chuỗi cung ứng và tối ưu hóa quy trình kinh doanh. Chương trình này sử dụng các kỹ thuật machine learning để dự đoán lượng hàng tồn kho cần thiết cho các sản phẩm khác nhau tại nhiều cửa hàng khác nhau. 

## Các Thư Viện Cần Thiết
Chương trình sử dụng các thư viện Python sau:
- **Pandas**: Để xử lý và phân tích dữ liệu.
- **NumPy**: Để thực hiện các phép toán số học nhanh chóng.
- **Matplotlib** và **Seaborn**: Để vẽ biểu đồ và trực quan hóa dữ liệu.
- **Scikit-learn**: Chứa nhiều thuật toán machine learning và công cụ tiền xử lý.
- **XGBoost**: Để triển khai thuật toán XGBoost cho việc dự đoán.

## Cách Chạy Chương Trình
1. **Cài Đặt Các Thư Viện Cần Thiết**:
 
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost


2. **Tải Dữ Liệu**: Đảm bảo bạn có tệp dữ liệu `train.csv` trong cùng thư mục với tệp mã nguồn.

3. **Chạy Chương Trình**: Sử dụng Python để chạy chương trình:

   python inventory_forecasting.py
  
## Nội Dung Chương Trình
1. **Nhập Thư Viện và Dữ Liệu**: Nhập các thư viện cần thiết và tải dữ liệu vào khung dữ liệu Pandas.
2. **Khám Phá Dữ Liệu**: Kiểm tra kích thước và cấu trúc của dữ liệu, thực hiện phân tích khám phá dữ liệu (EDA).
3. **Kỹ Thuật Kỹ Thuật Đặc Trưng**: Tạo các cột mới như năm, tháng, ngày, ngày trong tuần, và thông tin về ngày lễ.
4. **Chuẩn Hóa Dữ Liệu**: Chuẩn hóa dữ liệu để đảm bảo quá trình huấn luyện ổn định và hiệu quả.
5. **Huấn Luyện Mô Hình**: Huấn luyện và đánh giá một số mô hình machine learning để tìm ra mô hình tốt nhất cho dự đoán nhu cầu hàng tồn kho.

## Kết Quả
Chương trình cung cấp các dự đoán chính xác về nhu cầu hàng tồn kho, từ đó giúp tối ưu hóa việc quản lý hàng hóa và nâng cao hiệu quả kinh doanh.

## Nhóm Sinh viên
- 1671020227 Nguyễn Đào Phúc Nguyên 
- 1671020288 Nguyễn Tiến Thái 
- 1671020222 Phạm Đình Nghĩa
- 1671020137 Hồ Quang Huy


## ĐỀ 3. Dự báo nhu cầu hàng tồn kho bằng cách sử dụng máy học

## TÀI LIỆU THAM KHẢO
- https://www.geeksforgeeks.org/inventory-demand-forecasting-using-machine-learning-python/ 
- https://www.kaggle.com/datasets/subho117/inventory-demand-forecasting-using-ml 
- https://media.geeksforgeeks.org/wp-content/uploads/20240909120859/Inventory_Demand_Forecasting_using_Machine_Learning_Python.ipynb
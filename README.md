# 🔍 Dự đoán Khả năng Vỡ Nợ Thẻ Tín Dụng

Dự án cá nhân về phân tích dữ liệu và học máy nhằm dự đoán khả năng khách hàng sẽ vỡ nợ trong tháng tiếp theo, sử dụng bộ dữ liệu công khai từ UCI (trên Kaggle).

---

## 🎯 Mục tiêu dự án

Xây dựng một mô hình dự đoán xem khách hàng **có vỡ nợ thẻ tín dụng trong tháng tới hay không** dựa trên các thông tin nhân khẩu học, lịch sử tín dụng và hành vi thanh toán.

---

## 📊 Thông tin dữ liệu

- **Nguồn**: UCI Credit Card Dataset
- **Link Kaggle**: [Tại đây](https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset)
- **Kích thước**: 30.000 mẫu × 24 thuộc tính
- **Biến mục tiêu**: `default payment next month` (1 = Vỡ nợ, 0 = Không vỡ nợ)

---

## 🧰 Công cụ & Công nghệ sử dụng

- Python, Jupyter Notebook
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

---

## ⚙️ Quy trình thực hiện

1. Khám phá dữ liệu (EDA)
2. Tiền xử lý và làm sạch dữ liệu
3. Trực quan hoá bằng biểu đồ tiếng Việt
4. Huấn luyện mô hình (Random Forest)
5. Đánh giá mô hình (Accuracy, ROC-AUC, Confusion Matrix)
6. Rút ra insight và kết luận

---

## 📈 Một số kết quả chính

- **Biến `PAY_0` (lịch sử thanh toán)** có tương quan mạnh với khả năng vỡ nợ.
- Mô hình đạt **độ chính xác ~81.6%** và điểm **ROC-AUC ~0.84**
- Các đặc trưng quan trọng: Hạn mức tín dụng, số dư hóa đơn, độ tuổi, lịch sử trễ hạn.

---

## 📂 Cấu trúc thư mục đề xuất

credit-default-prediction/
├── data/ # Bộ dữ liệu gốc
├── notebooks/ # File notebook Jupyter
├── output/ # Hình ảnh, báo cáo, biểu đồ
├── models/ # (tuỳ chọn) mô hình đã lưu
└── README.md # Tài liệu mô tả dự án

---

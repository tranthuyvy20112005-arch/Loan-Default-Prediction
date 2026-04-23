# Dự đoán khả năng vỡ nợ của khách hàng (Loan Default Prediction)

Đồ án môn học Máy - Trường Đại học Ngân hàng TP.HCM (HUB). Dự án tập trung vào việc ứng dụng các thuật toán Machine Learning để dự báo rủi ro tín dụng, hỗ trợ ngân hàng trong việc thẩm định cho vay.

## 📊 Tổng quan dự án
- **Mục tiêu:** Xây dựng mô hình phân loại khách hàng có khả năng nợ xấu (vỡ nợ) dựa trên các biến số tài chính và hành vi.
- **Dữ liệu:** Bộ dữ liệu bao gồm các đặc trưng như thu nhập, dư nợ, lịch sử tín dụng và tài sản thế chấp.

## 🛠 Quy trình thực hiện
1. **Tiền xử lý dữ liệu (Pre-processing):** Xử lý giá trị thiếu (Missing values), xử lý dữ liệu mất cân bằng (Imbalanced Data) và chuẩn hóa dữ liệu.
2. **Phân tích đặc trưng (EDA):** Trực quan hóa mối quan hệ giữa các biến số để tìm ra các yếu tố ảnh hưởng lớn nhất đến rủi ro vỡ nợ.
3. **Huấn luyện mô hình:** Thử nghiệm và so sánh hiệu suất của nhiều thuật toán khác nhau:
   - Logistic Regression
   - Random Forest
   - XGBoost (Extreme Gradient Boosting)
4. **Đánh giá:** Sử dụng các chỉ số Precision, Recall, F1-score và biểu đồ AUC-ROC để lựa chọn mô hình tối ưu.

## 📈 Kết quả
- Ứng dụng kỹ thuật giải thích mô hình để xác định các đặc trưng quan trọng giúp minh bạch hóa quyết định tín dụng.

## 👤 Thành viên thực hiện
Nhóm 8 - Chuyên ngành Khoa học dữ liệu trong Kinh doanh.

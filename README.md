# Business Intelligence 9 - Round 01: Chessboard ♟️

[cite_start]Dự án này được thực hiện trong khuôn khổ Vòng 1 cuộc thi **Business Intelligence Season 9**. [cite_start]Mục tiêu trọng tâm là thực hiện quy trình BI toàn diện cho bài toán kinh doanh của **Highlands Coffee**, từ xử lý dữ liệu thô đến xây dựng mô hình dự báo và đưa ra các đề xuất chiến lược[cite: 142, 158, 220].

## 📋 Tổng quan dự án (Project Overview)
[cite_start]Dự án giải quyết 6 câu hỏi lớn (Questions) được đặt ra trong cuộc thi nhằm tối ưu hóa hoạt động kinh doanh và quản trị trải nghiệm khách hàng[cite: 15, 16]:

1.  [cite_start]**Data Quality Assessment:** Đánh giá và xử lý các vấn đề về chất lượng dữ liệu[cite: 42].
2.  [cite_start]**Data Modeling:** Thiết kế sơ đồ quan hệ thực thể (ERD) chuẩn hóa[cite: 61].
3.  [cite_start]**Data Access Control:** Thiết lập ma trận phân quyền truy cập (RBAC)[cite: 89].
4.  [cite_start]**Competitive Analysis:** Phân tích vị thế cạnh tranh và định vị thương hiệu[cite: 142].
5.  [cite_start]**Churn Analysis & Dashboard:** Trực quan hóa tỷ lệ khách hàng rời bỏ[cite: 158].
6.  [cite_start]**Segmentation & Prediction:** Phân đoạn khách hàng và dự báo rủi ro rời bỏ bằng Machine Learning[cite: 220].

## 🛠️ Quy trình thực hiện (Methodology)

### 1. Kỹ thuật Dữ liệu (Data Engineering)
* [cite_start]**Làm sạch dữ liệu:** Xác định và xử lý dữ liệu dư thừa, nhãn không nhất quán, vi phạm ràng buộc logic và giá trị thiếu[cite: 49, 50, 51, 52].
* [cite_start]**Mô hình hóa:** Xây dựng sơ đồ ERD/Class Diagram thể hiện mối quan hệ giữa các thực thể chính, xác định rõ Primary Key, Foreign Key và tính bản số (cardinality)[cite: 77, 79, 83].

### 2. Quản trị & Phân tích (Governance & Analytics)
* [cite_start]**Phân quyền (RBAC):** Thiết kế ma trận truy cập dữ liệu cho các phòng ban (BOD, HR, Finance, Marketing, Sales) dựa trên nguyên tắc đặc quyền tối thiểu[cite: 96, 117, 118].
* [cite_start]**Phân tích đối thủ:** Sử dụng Brand Funnel (từ nhận biết đến trung thành) và bản đồ định vị để tìm kiếm cơ hội thị trường cho Highlands Coffee[cite: 150, 341, 345].

### 3. Phân tích Churn & Machine Learning
* [cite_start]**Định nghĩa Churn:** Khách hàng có hoạt động trong 3 tháng gần nhất (P3M) nhưng không quay lại trong 1 tháng gần nhất (P1M)[cite: 175, 176].
* [cite_start]**Dashboard tương tác:** Hệ thống biểu đồ (Bar chart, Sunburst) cho phép drill-down theo nhiều chiều: NPS, phân khúc, nhân khẩu học và thói quen tiêu dùng[cite: 178, 187, 197].
* [cite_start]**Mô hình ML:** * **Clustering:** Phân cụm khách hàng dựa trên hành vi và cảm nhận thương hiệu[cite: 253, 259].
    * [cite_start]**Classification:** Xây dựng mô hình phân loại nhị phân để dự báo rủi ro rời bỏ và xác định các đặc trưng (features) quan trọng nhất[cite: 268, 272, 276].

## 📊 Kết quả bàn giao (Deliverables)
* [cite_start]**Dataset:** Tập dữ liệu sạch đã qua Feature Engineering[cite: 307, 378].
* [cite_start]**Diagrams:** Sơ đồ ERD và Ma trận phân quyền dữ liệu[cite: 317, 330].
* [cite_start]**Interactive Dashboards:** Hệ thống báo cáo về cạnh tranh và tỷ lệ churn[cite: 340, 367].
* [cite_start]**ML Models:** File mô hình phân cụm và dự báo churn kèm đánh giá hiệu suất[cite: 379, 380].


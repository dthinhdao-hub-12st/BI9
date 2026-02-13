[VIETNAMESE VERSION (ENGLISH VERSION BELOW)]
# **Business Intelligence 9 - Round 01: Chessboard ♟️**
Dự án này được thực hiện trong khuôn khổ Vòng 1 cuộc thi Business Intelligence Season 9. Mục tiêu trọng tâm là thực hiện quy trình BI toàn diện cho bài toán kinh doanh của Highlands Coffee, từ xử lý dữ liệu thô đến xây dựng mô hình dự báo và đưa ra các đề xuất chiến lược.

## **Tổng quan dự án (Project Overview)**
Dự án giải quyết 6 câu hỏi lớn (Questions) được đặt ra trong cuộc thi nhằm tối ưu hóa hoạt động kinh doanh và quản trị trải nghiệm khách hàng:
- Data Quality Assessment: Đánh giá và xử lý các vấn đề về chất lượng dữ liệu như dư thừa, không nhất quán và vi phạm logic.
- Data Modeling: Thiết kế sơ đồ quan hệ thực thể (ERD) chuẩn hóa để phản ánh cấu trúc dữ liệu sạch.
- Data Access Control: Thiết lập ma trận phân quyền truy cập dữ liệu (RBAC) cho các phòng ban (BOD, HR, Finance, Marketing, Sales).
- Competitive Analysis: Phân tích vị thế cạnh tranh của Highlands Coffee thông qua Brand Funnel và bản đồ định vị thương hiệu.
- Churn Analysis & Dashboard: Trực quan hóa tỷ lệ khách hàng rời bỏ theo nhiều chiều (NPS, phân khúc, nhân khẩu học).
- Segmentation & Prediction: Phân đoạn khách hàng bằng Clustering và xây dựng mô hình Machine Learning dự báo rủi ro rời bỏ.

## **Quy trình thực hiện (Methodology)**
1. Kỹ thuật Dữ liệu (Data Engineering)
- Làm sạch dữ liệu: Loại bỏ cột thừa, chuẩn hóa nhãn và xử lý các giá trị thiếu (Missing values).
- Mô hình hóa: Xây dựng sơ đồ ERD/Class Diagram xác định rõ Primary Key, Foreign Key và các mối quan hệ (1-1, 1-n).

2. Quản trị & Phân tích (Governance & Analytics)
- Phân quyền (RBAC): Xây dựng ma trận truy cập đảm bảo nguyên tắc đặc quyền tối thiểu cho từng vai trò trong doanh nghiệp.
- Phân tích cạnh tranh: Theo dõi hành trình khách hàng từ nhận biết đến trung thành và chẩn đoán các khoảng cách về cảm nhận thương hiệu.

3. Machine Learning & Dashboard
- Định nghĩa Churn: Khách hàng có hoạt động trong 3 tháng gần nhất (P3M) nhưng không có giao dịch trong 1 tháng gần nhất (P1M).
- Dashboard tương tác: Cung cấp khả năng drill-down sâu theo hành vi, nhu cầu (need states) và bối cảnh (weekday/daypart).
- Mô hình dự báo: Sử dụng Classification để tìm ra các tác nhân chính dẫn đến churn và đề xuất giải pháp giảm thiểu rủi ro.

## **Kết quả bàn giao (Deliverables)**
- Dataset: Tập dữ liệu sạch và các đặc trưng đã qua xử lý (Feature Engineering).
- Diagrams: Sơ đồ thực thể quan hệ và Ma trận phân quyền.
- Dashboards: Hệ thống báo cáo phân tích cạnh tranh và phân tích Churn.
- Models: Mô hình phân cụm khách hàng và mô hình dự báo tỷ lệ rời bỏ.

## **Hướng dẫn (Instructions)**
- Kết quả trả lời các câu hỏi được lưu trong file pdf FinalReport
- Chi tiết về các câu hỏi và yêu cầu được lưu trong file pdf BI9_Round1
- Tùy vào câu hỏi sẽ có các deliverables tương ứng được tạo, ví dụ như notebook, dashboards, ...
- Nếu cần file dữ liệu gốc hoặc đã xử lý, vui lòng liên hệ chủ sở hữu


[ENGLISH VERSION]
# **Business Intelligence 9 - Round 01: Chessboard ♟️**

This project was developed as part of Round 01 of the Business Intelligence Season 9 competition. The primary focus is to implement a comprehensive BI workflow for Highlands Coffee's business challenges, ranging from raw data processing to building predictive models and providing strategic recommendations.

## **Project Overview**
The project addresses six major questions set out in the competition to optimize business operations and customer experience management:
- Data Quality Assessment: Evaluating and resolving data quality issues such as redundancy, inconsistency, and logical violations.
- Data Modeling: Designing a standardized Entity-Relationship Diagram (ERD) to reflect a cleaned data structure. 
- Data Access Control: Establishing a Role-Based Access Control (RBAC) matrix for various departments (BOD, HR, Finance, Marketing, Sales). 
- Competitive Analysis: Analyzing the competitive landscape of Highlands Coffee through brand funnels and brand positioning maps.
- Churn Analysis & Dashboard: Visualizing customer churn rates across multiple dimensions (NPS, segmentation, demographics). 
- Segmentation & Prediction: Segmenting customers using Clustering and building Machine Learning models to predict churn risk. 

## **Methodology**
### 1. Data Engineering
- Data Cleaning: Removing redundant columns, standardizing labels, and handling missing values.
- Modeling: Developing an ERD/Class Diagram to define Primary Keys, Foreign Keys, and relationships (1-1, 1-n). 

### 2. Governance & Analytics
- Access Control (RBAC): Constructing an access matrix ensuring the principle of least privilege for each corporate role. 
- Competitive Analysis: Tracking the customer journey from awareness to loyalty and diagnosing brand perception gaps. 

### 3. Machine Learning & Dashboard
- Churn Definition: A customer is defined as churned if they were active in the past 3 months (P3M) but had no visit in the past 1 month (P1M). 
- Interactive Dashboard: Providing deep drill-down capabilities by behavior, need states, and context (weekday/daypart). 
- Predictive Modeling: Using Classification to identify key churn drivers and proposing risk mitigation solutions. 

## **Deliverables**
- Dataset: Cleaned dataset and engineered features. 
- Diagrams: Entity-Relationship Diagram and Data Access Matrix. 
- Dashboards: Competitive landscape analysis and Churn analysis reporting systems. 
- Models: Customer segmentation models and churn prediction models. 

## **Instructions**
- Answers to the questions are documented in the **FinalReport** PDF file. 
- Detailed questions and requirements are stored in the **BI9_Round1** PDF file. 
- Corresponding deliverables such as notebooks and dashboards are created based on each specific question.
- If you require original or processed data files, please contact the owner.

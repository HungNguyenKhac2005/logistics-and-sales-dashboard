# 🚚 Logistics & Sales Dashboard

Dự án thiết kế và phát triển báo cáo quản trị chuyên sâu về **Logistics và Doanh số bán hàng (Logistics & Sales)** trên công cụ **Power BI**. Báo cáo này giúp các nhà quản trị doanh nghiệp và bộ phận vận hành có cái nhìn toàn diện về hiệu quả kinh doanh, chi phí vận chuyển, hiệu suất giao hàng và phân bổ địa lý.

---

## ✒️ Giới thiệu về tác giả

- **Tên:** Nguyễn Khắc Hưng
- **Vị trí:** BI Developer
- **Học vấn:** Đang theo học chương trình kỹ sư ngành Khoa học Dữ liệu, chuyên ngành Phân tích Dữ liệu trong Kinh tế và Tài chính, thuộc Khoa Công nghệ Thông tin, Đại học Mỏ - Địa chất.

---

## 📊 Tổng quan dự án & Chỉ số KPI cốt lõi (Key Performance Indicators)

Bảng điều khiển được thiết kế tối giản, hiện đại và tập trung vào các chỉ số hiệu năng chính (KPIs) để hỗ trợ ra quyết định nhanh chóng:

- **Tổng số đơn hàng (Total Orders):** `100` đơn hàng.
- **Tổng doanh thu (Total Sales):** `117M` (Triệu đơn vị tiền tệ).
- **Tổng chi phí (Total Cost):** `23.47M` (Chiếm tỉ lệ chi phí khoảng **20%** doanh thu).
- **Tổng lợi nhuận (Total Profit):** `64.55M` (Đạt tỷ suất lợi nhuận biên - Profit Margin ấn tượng lên tới **55%**).

---

## 🔍 Các thành phần trực quan hóa & Phân tích chuyên sâu (Insights)

### 1. Phân tích Phương thức Vận chuyển (Delivery Method Analysis)

- **Số lượng đơn hàng:** Phương thức **Express (Hỏa tốc)** dẫn đầu với **56 đơn hàng**, theo sau là **Standard (Tiêu chuẩn)** với **44 đơn hàng**.
- **Tỷ trọng cơ cấu:** Được trực quan hóa thông qua biểu đồ tròn (Donut Chart) và biểu đồ cột dọc, cho thấy sự so sánh trực quan giữa hai hình thức giao hàng chính.

### 2. Xu hướng Doanh thu & Lợi nhuận theo ngày (Daily Trends)

- Sử dụng biểu đồ đường liên tục (**Total profit and Total Sales by Day**) và biểu đồ kết hợp cột-đường để theo dõi sự biến động của doanh thu và lợi nhuận trong chu kỳ 30 ngày.
- Giúp doanh nghiệp dễ dàng phát hiện các ngày có doanh số đột biến (ví dụ: ngày 9, 22, v.v.) và kiểm soát sự chênh lệch chi phí phát sinh.

### 3. Hiệu suất theo Danh mục Sản phẩm (Category Breakdown)

- Phân loại sản phẩm thành 5 danh mục cốt lõi: **A, B, C, D, E**.
- Đánh giá trạng thái phản hồi/hoàn thành (Yes/No) của từng danh mục:
  - **Danh mục B và D:** Chỉ ghi nhận trạng thái "No".
  - **Danh mục A, C, E:** Có sự xuất hiện của trạng thái "Yes", trong đó danh mục **E** có số lượng phản hồi "Yes" cao nhất (7 phản hồi).

### 4. Phân bổ Địa lý & Thị trường (Geographical Breakdown)

- **Bản đồ tương tác (Map Visual):** Trực quan hóa độ lớn của thị trường bằng các bong bóng (bubbles) trên bản đồ Việt Nam.
- **Biểu đồ vùng (Treemap Visual):** Xác định các khu vực đóng góp đơn hàng lớn nhất như **Cần Thơ**, **Bình Dương**, **TP. Hồ Chí Minh**, bên cạnh các thị trường tiềm năng khác như **Hà Nội**, **Đà Nẵng**, **Hải Phòng**, **Quảng Ninh**, **Nghệ An**.

---

## 🛠️ Công nghệ & Kỹ thuật áp dụng

- **Power BI Desktop**: Nền tảng chính thiết kế giao diện UI/UX và trực quan hóa dữ liệu.
- **Power Query (ETL)**: Làm sạch, chuyển đổi cấu trúc dữ liệu và xử lý các giá trị khuyết thiếu/dữ liệu lỗi.
- **DAX (Data Analysis Expressions)**: Xây dựng các thước đo (Measures) tính toán động cho doanh thu, chi phí, lợi nhuận và biên lợi nhuận.
- **Data Modeling**: Thiết lập mối quan hệ tối ưu giữa các bảng dữ liệu để đảm bảo báo cáo vận hành mượt mà với hiệu suất cao.

---

## 🚀 Hướng dẫn mở dự án

1.  Cài đặt ứng dụng **Microsoft Power BI Desktop** phiên bản mới nhất.
2.  Clone repository này về máy cá nhân:
    ```bash
    git clone https://github.com/HungNguyenKhac2005/Power-BI-Dashboard-Projects.git
    ```
3.  Di chuyển đến thư mục dự án và mở file [Logistics\_&_Sales_Dashboard.pbix](file:///C:/BI%20tool/Power%20BI/C%C3%A1c%20DashBoard%20%C4%91%C3%A3%20ho%C3%A0n%20thi%E1%BB%87n/Logistics_&_Sales_Dashboard.pbix).
4.  Trải nghiệm tương tác động bằng cách sử dụng các bộ lọc (Slicers) ở thanh công cụ bên trái.

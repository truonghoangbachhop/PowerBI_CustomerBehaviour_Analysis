# Marketing_Customer's Behaviour Analysis_PowerBI

## Executive Summary

**Bối cảnh:**

Trong thị trường kinh doanh cạnh tranh ngày nay, việc thấu hiểu hành vi khách hàng và xu hướng bán hàng là rất quan trọng để đưa ra các quyết định chiến lược hiệu quả. Dự án này tận dụng sức mạnh của Power BI để phân tích dữ liệu từ cơ sở dữ liệu AdventureWorks, một cơ sở dữ liệu mẫu giàu thông tin, nhằm mục đích khám phá các insight giá trị về hiệu suất bán hàng và hành vi khách hàng trong giai đoạn từ 2011 đến 2014.

**Giải pháp:**

1. **Kết nối và chuyển đổi dữ liệu:** Kết nối với cơ sở dữ liệu AdventureWorks và trích xuất các bảng dữ liệu liên quan như `DimCustomer`, `DimProduct`, `FactInternetSales`, `DimSalesTerritory`, v.v. Sau đó, dữ liệu được làm sạch và chuyển đổi để phù hợp với mục tiêu phân tích.
2. **Mô hình hóa dữ liệu:** Tạo mối quan hệ giữa các bảng dữ liệu, xây dựng các thước đo (measures) và chỉ số hiệu suất chính (KPIs) để hỗ trợ cho việc phân tích. Ví dụ, các thước đo như `Total Sales`, `Average Order Value`, `Number of Orders per Customer`, và các KPIs như `Customer Lifetime Value`, `Churn Rate` có thể được tính toán.
3. **Phân tích RFM:** Áp dụng kỹ thuật phân tích RFM (Recency, Frequency, Monetary) để phân khúc khách hàng dựa trên hành vi mua hàng của họ (thời gian mua hàng gần đây nhất, tần suất mua hàng, và tổng giá trị mua hàng).
4. **Trực quan hóa dữ liệu:** Sử dụng các biểu đồ trực quan đa dạng của Power BI như biểu đồ đường, biểu đồ cột, biểu đồ tròn, biểu đồ phân tán, v.v. để trình bày các thông tin chi tiết một cách rõ ràng và dễ hiểu.

**Kết quả:**

Báo cáo Power BI cung cấp các thông tin chi tiết quan trọng, bao gồm:

* **Xu hướng bán hàng:** Doanh số bán hàng theo từng danh mục sản phẩm, theo quý và theo năm, giúp xác định các sản phẩm bán chạy và các xu hướng tăng trưởng hoặc giảm sút.
* **Hành vi khách hàng:** Phân tích RFM cho thấy sự phân bố khách hàng theo các phân khúc khác nhau (Champions, Loyal Customers, Potential Loyalist, v.v.), từ đó hiểu rõ hơn về giá trị và hành vi của từng nhóm khách hàng.
* **Hiệu quả kinh doanh:** Các chỉ số như giá trị đơn hàng trung bình, số lượng đơn hàng trung bình của mỗi khách hàng, và doanh số bán hàng theo từng phân khúc khách hàng giúp đánh giá hiệu quả hoạt động kinh doanh.
* **Phân bố địa lý:** Phân bố khách hàng theo quốc gia và khu vực, giúp xác định thị trường tiềm năng và điều chỉnh chiến lược tiếp thị phù hợp.

**Tag:** Power BI, AdventureWorks, Phân tích dữ liệu, Trực quan hóa dữ liệu, Phân tích bán hàng, Phân tích khách hàng, Phân khúc khách hàng, Phân tích RFM, Xu hướng bán hàng, Tăng trưởng khách hàng


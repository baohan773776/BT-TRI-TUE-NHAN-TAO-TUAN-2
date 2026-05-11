# BT-TRI-TUE-NHAN-TAO-TUAN-2
Nguyễn Bảo Hân - 31251027458 - DA0001 - HOMEWORK WEEK 2
Dự án này chứa các bài tập thực hành về Fuzzy logic trong môn Trí tuệ nhân tạo. Các bài toán tập trung vào việc mô phỏng logic quyết định trong các lĩnh vực thương mại điện tử và vận tải.

### Công nghệ sử dụng
* **Ngôn ngữ:** Python 3
* **Thư viện:** `scikit-fuzzy`, `numpy`, `matplotlib`
* **Môi trường:** Google Colab / Jupyter Notebook

# Các bài tập

### 1. Bài 2.11: Hệ thống tính giá Grab-Bike
* **Mô tả:** Xác định giá cước xe dựa trên các yếu tố ngoại cảnh.
* **Biến đầu vào:** Khoảng cách (Distance), Lưu lượng giao thông (Traffic), Nhu cầu (Demand), Thời tiết (Weather).
* **Biến đầu ra:** Giá tiền (Price).

### 2. Bài 2.12: Chiến lược chiết khấu Shopee (Mặt hàng thông thường)
* **Mô tả:** Tính toán % giảm giá tối ưu cho sản phẩm dựa trên hiệu suất bán hàng và đối thủ.
* **Biến đầu vào:** Đánh giá (Rating), Khối lượng bán (Volume), Biên lợi nhuận (Margin), Mùa vụ (Seasonal), Đối thủ (Competitor).
* **Biến đầu ra:** % Chiết khấu (Discount).

### 3. Bài 2.13: Kế hoạch bán hàng Shopee (Mặt hàng đặc biệt)
* **Mô tả:** Tối ưu chiết khấu cho các mặt hàng xa xỉ/đặc biệt trong các dịp lễ lớn (11.11, 12.12).
* **Biến đầu vào:** Nhu cầu (Demand), Áp lực đối thủ (Pressure), Uy tín shop (Reputation), Biên lợi nhuận (Margin).
* **Biến đầu ra:** % Chiết khấu (Discount).

### 4. Bài 2.14: Tối ưu hóa trong Giao nhận (Logistics)
* **Mô tả:** Hệ thống hỗ trợ điều phối viên quyết định số lượng đơn hàng cần kết hợp và độ ưu tiên giao hàng.
* **Biến đầu vào:** Mật độ đơn (Density), Độ khẩn cấp (Urgency), Tải trọng (Load), Giao thông (Traffic), Lợi nhuận (Profit).
* **Biến đầu ra:** Số lượng đơn kết hợp (Combine), Độ ưu tiên (Priority).

## Cấu trúc Logic mờ
Tất cả các bài tập đều tuân thủ quy trình:
1.  **Fuzzification (Mờ hóa):** Sử dụng hàm tam giác (`trimf`) để định nghĩa các tập mờ cho biến vào/ra.
2.  **Inference (Suy luận):** Thiết lập hệ thống luật (Rules) dạng `IF... AND... THEN...` bám sát yêu cầu nghiệp vụ.
3.  **Defuzzification (Giải mờ):** Tính toán giá trị thực (Crisp value) bằng phương pháp trọng tâm (Centroid).

## Hướng dẫn chạy
Cài đặt thư viện:scikit-fuzzy
   pip install scikit-fuzzy

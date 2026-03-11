<img width="598" height="117" alt="image" src="https://github.com/user-attachments/assets/711ccdd6-d926-4934-bc46-a6bc05bd7df2" />

<img width="1466" height="410" alt="image" src="https://github.com/user-attachments/assets/fd751d1e-1674-4ddf-932f-7f116c7a5220" />

<img width="962" height="354" alt="image" src="https://github.com/user-attachments/assets/df3512f7-f13f-4c3d-a23b-4a5f89107454" />

Kẻ tấn công đang sử dụng cổng 55000 để giả mạo các nhà mạng lớn nhằm dụ dỗ điện thoại nạn nhân tự động kết nối vào:
Gói 1: Giả mạo Verizon (PLMN=310410, CELLID=25262).
Gói 2: Giả mạo AT&T (PLMN=310410, CELLID=25263).
Gói 3: Là mạng mục tiêu chính của bài này (UNAUTHORIZED-TEST-NETWORK).

Tiếp Theo sẽ xác định nạn nhân (IMSI Interception)
<img width="1082" height="213" alt="image" src="https://github.com/user-attachments/assets/a90b6f2b-9142-4f7a-958a-546b93a1a94e" />

-> Phát hiện hàng loạt truy vấn DNS đến tên miền lạ: device-310410337059687.network.com. xác định được số IMSI của nạn nhân là 310410337059687.

Tiếp : Trích xuất Payload bị đánh cắp (Data Exfiltration)

<img width="1156" height="151" alt="image" src="https://github.com/user-attachments/assets/ae9f5ddc-8ec4-40d2-bc15-632771e39886" />

Thu được một chuỗi Hex dài (51313554576e...). Đây chính là dữ liệu Flag đã bị mã hóa.

Cuối cùng: decode

<img width="1011" height="313" alt="image" src="https://github.com/user-attachments/assets/a33e591d-6116-4c43-afb4-fc7287c26dfc" />

<img width="332" height="30" alt="image" src="https://github.com/user-attachments/assets/fe2849a5-cac7-4a6b-8942-16c03bc00807" />

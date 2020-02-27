# CodeKeywordSpotting
Code training model Convolution neural network (CNN) - Keyword Spotting

<br>*** 4 file chính và 1 thư mục chính ***
<br>input_data.py : có tác dụng lấy dữ liệu để training
<br>models.py : cấu hình mạng nơ-ron nhân tạo
<br>train.py : để training mô hình học máy
<br>freeze.py : kết xuất model thành file output_model.pb

<br>Thư mục "data" chứa dữ liệu audio của "các lớp đào tạo" và 2 lớp: "_unknown_" và "_background_noise_"

<br>*** HƯỚNG DẪN CHẠY CODE:
<br>B1: Chỉnh sửa các chỉ số trong file train.py cho phù hợp với dữ liệu.
<br>Sau đó, chạy file train.py để training model.
<br>B2: Chỉnh sửa các chỉ số trong file freeze.py cho phù hợp với dữ liệu.
<br>Sau đó, chạy file freeze.py kết xuất model thành file output_model.pb

Hướng dẫn sử dụng:
- Tải hết folder này về
- Tải lên google drive *
- Vô folder vừa tải lên trên google drive, mở file nmt_with_attention.ipynb bằng google collab.
- Khuyến nghị nên chọn runtime type là GPU, sau đó chọn run all để program bắt đầu chạy từ đầu để train model (tốc độ train cũng khá nhanh)
- Sau đó có thể lưu hoặc test model ở gần cuối file.

Mọi thắc mắc về model, bạn có thể liên hệ mình qua email: dong.le0110@hcmut.edu.vn
Model này được dựa trên Seq2Seq với lớp attention
Nguồn tham khảo:
	- Trang chủ tensorflow về machine translation
	- https://arxiv.org/abs/1508.04025v5
Hướng phát triển:
	- Có thể đổi qua với mạng transformer, thu thập và augment data.
Chúc bạn thành công, thân ! :D

* : Nếu muốn chạy trên máy local, bạn có thể dùng trên Jupyter hoặc Jupyter trên VSCode. Lưu ý là python phải cài thêm notebook kernel thì file mới execute được.
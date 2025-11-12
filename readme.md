# Round Iron Counter - đếm sắt xây dựng

Repo này chứa dataset, notebook để training model Object Detection đếm số lượng cây sắt.

![](Images/steel3.jpg)

## Hướng dẫn cài đặt

- Python 3.10 x64
- CUDA 11.8
- cuDNN 8.6.0

Cài đặt pip package

`pip install -r requirements.txt`



## Hướng dẫn training

Mở notebook YOLODetect, chạy block **Train**, sau khi train xong kết quả là file **runs\iron\weights\best.pt**

## Hướng dẫn sử dụng

- Nếu bạn chạy với Python thì file best.pt là có thể chạy được trực tiếp
- Nếu bạn cần chạy với Windows application thì convert sang ONNX để sử dụng với chương trình YOLOLYTIC. Bạn có thể convert sang ONNX CPU hoặc CUDA để chạy với bản phù hợp.

## Link bài viết hướng dẫn

https://thigiacmaytinh.com/huong-dan-dem-sat-xay-dung-bang-yolo
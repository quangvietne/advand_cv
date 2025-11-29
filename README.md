# Phân công nhiệm vụ dự án


## 1. Nguyễn Hoàng Việt
- Tạo và quản lý cấu trúc dataset (train/val/test).
- Chuẩn bị dataloader, kiểm tra tính nhất quán của dữ liệu.
- Thử nghiệm Backbone EfficientNet cho YOLOv8.
- Thử nghiệm YOLOv11 trên bộ dữ liệu
- Làm report báo cáo 
## 2. Nguyễn Thừa Tuân 
- Thử nghiệm backbone MobileNet cho YOLOv8.
- Thử nghiệm backbone MobileNet cho YOLOv10.
- Thử nghiệm YOLOv8 trên bộ dữ liệu
- Hỗ trợ làm report báo cáo

## 3. Nguyễn Quang Việt
- Thử nghiệm backbone ConvNeXt cho YOLOv8.
- Xuất mô hình sang ONNX
- Làm slide thuyết trình
---

# Cacshs tải dữ liệu
## Dữ liệu đầy đủ: https://github.com/suojiashun/HIT-UAV-Infrared-Thermal-Dataset

## Dữ liệu trên kaggle: https://www.kaggle.com/datasets/pandrii000/hituav-a-highaltitude-infrared-thermal-dataset

# Kịch bản thực nghiệm
- chọn mô hình cần thử nghiệm (backbone + phiên bản yolov8/yolov10/yolov11)
- chuẩn bị dữ liệu (dataloader)
- huấn luyện mô hình trên bộ dữ liệu
- đánh giá mô hình (mAP, precision-recall)
- lưu kết quả huấn luyện và đánh giá
- so sánh kết quả giữa các mô hình
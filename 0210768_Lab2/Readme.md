Buổi thực hiện này sẽ luyện tập phân tích loại nhị phân, nhãn sẽ chỉ có 0, 1 . Header đã ẩn dữ liệu của mình, nên khi đọc dữ liệu thì sẽ đọc với tham số header = False.

 

Không "trộn" dữ liệu trên tệp test_feature_no_header vì sẽ làm mất dữ liệu thứ tự (không thể khớp với kết quả thực tế).

 

Tải xuống dữ liệu, trong đó

train_no_header là tệp chứa dữ liệu huấn luyện
test_feature_no_header là dữ liệu được sử dụng để đánh giá giá
submit_sample là mẫu dữ liệu, các tệp bạn phụ thuộc tương thích với định dạng tệp này (MSSV_TH2.xlsx)

Kết quả cuối cùng sẽ được tính bằng cách gửi tệp so sánh điểm F1 của bạn với bài kiểm tra riêng tư (nhãn dữ liệu kiểm tra trên máy mình)

## Cài đặt môi trường

### 1. Yêu cầu Python
Phiên bản khuyến nghị: **Python 3.9+**

### 2. Cài đặt thư viện cần thiết
Chạy lệnh sau trong môi trường ảo hoặc notebook:

```bash
pip install numpy pandas scikit-learn matplotlib openpyxl

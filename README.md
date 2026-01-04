# BlackBoxTesting
#### Đưa những tập hợp input đã được tính toán vào ứng dụng và quan sát phản ứng của nó để đưa ra những dự đoán nhằm kết luận có bị lỗi bảo mật hay không
#### Không có thông tin 
#### Bị cản trở, không thể truy cập nhiều tài nguyên 
#### Tự khám phá + thử sai 
#### Tìm ra lỗi bảo mật và chứng minh hậu quả 
#### Đỡ mệt hơn khi không phải hiểu hết một hệ thống 
#### Phát hiện ra được ứng dụng lên thực tế sẽ kết nối được với API, server khác 

# Quy trình 
#### Đánh giá sơ bộ, liệt kê các chức năng
#### Đặt giả thiết - Quan sát dấu hiệu
#### Tìm dấu hiệu ( 4 dấu hiệu cần lưu tâm)

#### 1. Erron Message (những dòng lỗi) 
#### 2. Unexpected Data (những dữ liệu không mong muốn sảy ra)
#### 3. Time Response (thời gian trả về kết quả)
#### 4. Unexpected Behavior (những dấu hiệu còn lại)

# Tip & Trick
#### Để ý tất cả các Untrusted_data vì có bệnh thì phải có nguồn lây.Các Untrusted_data phổ biến như GET,POST paramester,Cookie,Filename
#### Sợ nhất là những dấu hiệu không rõ ràng + dễ nhầm lẫn với cái khác
#### Không chỉ để ý những dấu hiệu của bug mà hãy cố gắng hình dung ra bức tranh tổng quan, quan sát input và output để phán đoán hành vi.Hack là khai thác hành vi->tìm hiểu hành vi->mới tìm được bug
#### Sẽ có những chức năng phức tạp, khó đoán. Nên hãy takenote có thời gian quay lại xem 
#### May mắn

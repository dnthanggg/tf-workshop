---
title : "Tạo Resource AWS EC2"
date :  "`r Sys.Date()`" 
weight : 3
chapter : false
pre : " <b> 2.1.2 </b> "
---

#### Tạo Private subnet

1. Mở file main.tf và code theo như sau:


+ *Các bạn không cần phải hiểu hết cú pháp mình sẽ giải phẩu tất tần tật về terraform ở bài lab sau.

+ *Lưu ý: Bạn nhớ dẫn đúng đường dẫn public key mà bạn đã tạo từ trước nhé
![VPC](/images/b4.png)


2. Gõ các câu lệnh để bắt đầu tạo EC2.

  + Tại terminal bạn gõ lệnh theo các thứ tự sau:
   - Terraform init
   - Terraform plan
   - Terraform apply
  + Mình sẽ được thông báo ec2 đang khởi tạo:

![VPC](/images/b6.png)

3. Kiểm tra thành quả.
+ Bây giờ chúng ta sẽ mở console chọn service EC2 lên để kiểm tra xem nó đã được khởi tạo chưa

![VPC](/images/b7.png)

+ Tới đây bạn đã tạo thành công EC2 bằng terraform cơ bản


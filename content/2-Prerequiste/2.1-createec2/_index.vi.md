---
title : "Chuẩn bị Keypair"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 2.1 </b> "
---

Trong bước này, chúng ta sẽ cần tạo một Keypair thông thường bạn sẽ tạo keypair bằng console aws. Ở đây mình sẽ hướng dẫn bạn tạo bằng cli.

Bạn mở vscode và tạo folder và file main.tf như sau:

![VSCODE](/images/b1.png)

Sau đó bạn mở terminal lên và gõ như sau :
  **ssh-keygen -t rsa -b 4096 -C "EmailCuaBan@gmail.com"**.


Gõ lệnh đó xong bạn sẽ dc báo như sau:
![VSCODE](/images/b2.png)
Bạn chỉ cần quan tâm tới thư mục bạn muốn lưu file keypair là được. Những dòng khác bạn bỏ trống.


Nếu bạn đã có 2 file này thì chúc mừng bạn đã thành công tạo keypair.
![VSCODE](/images/b3.png)

### Nội dung
  - [Tạo VPC](2.1.1-createvpc/)
  - [Tạo Public subnet](2.1.2-createpublicsubnet/)
  - [Tạo Private subnet](2.1.3-createprivatesubnet/)
  - [Tạo security group](2.1.4-createsecgroup/)
  - [Tạo máy chủ Linux public](2.1.5-createec2linux/)
  - [Tạo máy chủ Windows private](2.1.6-createec2windows/)

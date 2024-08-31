---
title : "Clean up resource"
date :  "`r Sys.Date()`" 
weight : 4
chapter : false
pre : " <b> 2.1.3 </b> "
---

#### Cuối cùng chúng ta sẽ xóa resource để tránh bị mất tiền oan.

+ Thông thường bạn sẽ phải dùng cách thủ công để xóa các resouce sau khi thực hành các bài lab để tránh aws tính phí ở console như khởi tạo các service khác ( ở bài lab này chúng ta tạo EC2). Và dĩ nhiên ta vẫn sẽ dùng code để clean up resouce mà ko cần phải vô console aws.

+ Bạn mở terminal và gõ:
 terraform destroy
![DES](/images/b8.png)

Terraform sẽ xóa tất cả các resource mà bạn đã tạo trước đó
+ Bạn kéo xuống cuối dòng và gõ YES để xác nhận xóa.
![DES](/images/b9.png)

+ Cuối cùng vô EC2 kiểm tra xem resouce đã thật sự xóa chưa.
![DES](/images/b10.png)
+ Như bạn thấy đấy nó đã bị terminated
+ Vậy là mình đã hướng dẫn bạn sử dụng terraform 1 cách cơ bản nhất, có thể bạn sẽ còn rất nhiều thắc mắc, mình giải phẩu terraform ở bài sau để bạn có thể hiểu sâu hơn về nó 
---
title : "Các bước set up"
date :  "`r Sys.Date()`" 
weight : 2 
chapter : false
pre : " <b> 2. </b> "
---

{{% notice info %}}
Bạn cần cài đặt aws-cli và terraform trước để thực hành bài lab này
{{% /notice %}}

Bạn có thể làm theo hướng dẫn dưới đây để cài đặt phù hợp với hệ điều hành của mình:
  - [AWS-CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)
  - [Terraform](https://developer.hashicorp.com/terraform/install?product_intent=terraform)

Để sử dụng System Manager để quản lý window instance nói riêng và các instance nói chung của chúng ta trên AWS, ta cần phải cung cấp quyền cho các instance của chúng ta có thể làm việc với System Manager.Trong phần chuẩn bị này, chúng ta cũng sẽ tiến hành tạo IAM Role để cấp quyền cho các instance có thể làm việc với System Manager.

### Nội dung
  - [Chuẩn bị VPC và EC2 Instance](2.1-createec2/)
  - [Tạo IAM Role](2.2-createiamrole/)

  

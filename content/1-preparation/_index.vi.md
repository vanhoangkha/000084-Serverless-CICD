---
title : "Chuẩn bị"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---
Trước khi thực hiện nội dung chính của workshop này, chúng ta chuẩn bị sam project và tải source của front-end về máy của bạn.
1. Tải source code của sam project dưới đây

{{%attachments title="SAM source" pattern=".*\.(zip)$"/%}}

2. Chạy câu lệnh dưới đây để build project
```
sam build
```

{{% notice note %}}
Bạn nên cài đặt python3.9 vì các hàm lambda sử dụng python3.9
{{% /notice %}}

3. Thực hiện câu lệnh dưới đây để tải code **fcj-serverless-frontend** về máy của bạn
```
git clone https://github.com/AWS-First-Cloud-Journey/FCJ-Serverless-Workshop
cd FCJ-Serverless-Workshop
npm install
npm install --global yarn
```

Chúng ta đã chuẩn bị xong source cần thiết cho các bước tiếp theo.

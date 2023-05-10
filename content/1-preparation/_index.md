---
title : "Preparation"
date :  "`r Sys.Date()`" 
weight : 1 
chapter : false
pre : " <b> 1. </b> "
---
Before doing the main content of this workshop, we prepare the SAM project and download the front-end source to your machine.
1. Download theh below source code of SAM project

{{%attachments title="SAM source" pattern=".*\.(zip)$"/%}}

2. Run the following command
```
sam build
```

{{% notice note %}}
You should install python3.9 because the lambda function uses python3.9
{{% /notice %}}

3. Run the following command to clone **fcj-serverless-frontend** code to your device
```
git clone https://github.com/AWS-First-Cloud-Journey/FCJ-Serverless-Workshop
cd FCJ-Serverless-Workshop
npm install
npm install --global yarn
```

We have prepared the necessary source for the next steps.
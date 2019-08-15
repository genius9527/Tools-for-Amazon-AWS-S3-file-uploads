# Tools-for-Amazon-AWS-S3-file-uploads
A tool for implementing S3 file uploads using aws sdk for Javascript

**工具功能**：
1.上传文件至亚马逊AWS S3中
2.可视化上传进度
3.获取最新上传文件的下载链接

**使用方法**：
1.获取你的accessKeyId与secretAccessKey，填进代码对应位置。
2.（可选，如已存在bucket，可忽略）在aws S3 中创建你的bucket，将bucket的名称填入代码对应位置。
3.设置桶的安全策略：

4.运行代码，选择文件上传。


**效果演示**：
![初始状态](https://github.com/genius9527/Tools-for-Amazon-AWS-S3-file-uploads/blob/master/%E5%88%9D%E5%A7%8B%E7%8A%B6%E6%80%81.png)

![中间状态](https://github.com/genius9527/Tools-for-Amazon-AWS-S3-file-uploads/blob/master/%E4%B8%AD%E9%97%B4%E7%8A%B6%E6%80%81.png)

![结束状态](https://github.com/genius9527/Tools-for-Amazon-AWS-S3-file-uploads/blob/master/%E7%BB%93%E6%9D%9F%E7%8A%B6%E6%80%81.png)


**Tips**：
1.本工具不可用于商用，仅可用于个人使用，请注意保护自己的账号与密码。
2.动态分配权限的版本尚未开发，待作者有时间会进行版本迭代。

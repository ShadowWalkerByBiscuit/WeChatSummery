##  核心概念  
阿里云对象存储服务（Object Storage Service，简称 OSS）  
存储类型（Storage Class）  
存储空间（Bucket）  
对象/文件（Object）  
地域（Region）  
访问域名（Endpoint）  
访问密钥（AccessKey）  
内容分发网络（CDN）：将源站资源缓存到各区域的边缘节点，供您就近快速获取内容。  
图片处理（IMG）：对存储在 OSS 上的图片进行格式转换、缩放、裁剪、旋转、添加水印等各种操作。  
云服务器（ECS）：提供简单高效、处理能力可弹性伸缩的云端计算服务。  


##  关键点
1 手册中提到的内外网是相对于阿里而言，内网是指ecs（阿里的云计算服务）所走的网络。  
2 数据具有强一致性，原子操作，成功代表着一系列操作（数据可用，备份冗余）都已经完成，不存在中间状态。  
3 使用图形化管理工具 ossbrowser。还有命令行ossutil,包括各种语言的api跟sdk。   
4 内网指的是阿里云产品之间的内网通信网络，例如您通过ECS云服务器访问OSS服务。内网产生的流入和流出流量均免费，但是请求次数仍会计费。

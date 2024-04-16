# DceRPC-OS-Info
`golang`实现通过`dcerpc`和`ntlmssp`获取`Windows`远程主机信息

由于某些原因需要把`komomon`师傅写的脚本转化成`golang`的形式，源仓库链接如下：

> https://github.com/komomon/Dcerpc_Find_OSInfo


简单实现，有需要的话请自行修改代码。
```powershell
go build dcerpc_os_info.go
```

扫描单独`ip`：

![](https://cdn.jsdelivr.net/gh/W01fh4cker/blog_image@main/image-20240416200622839.png)

扫描`C`段：

![](https://cdn.jsdelivr.net/gh/W01fh4cker/blog_image@main/image-20240416205535385.png)

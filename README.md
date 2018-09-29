# onlinePreview
文件在线预览解决方案
核心主要是kkFileView的代码，主要在其基础上增加了fastdfs相关内容 更加符合当前文件在线预览，kkFileView地址：https://github.com/kekingcn/kkFileView


在kkFileView基础上增加如下内容：
1.文件存储在fastdfs文件系统中

2.文件访问通过nginx-fastdfs module进行，效率更高，更符合实际使用环境

3.文件访问进行token权限控制

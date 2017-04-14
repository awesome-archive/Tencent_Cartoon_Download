# 腾讯漫画下载脚本

这是一个腾讯漫画的下载脚本..通过Python编写

目前实现的功能有:

- 通过名称查找漫画列表(目前只查找到了漫画的数目)
- 根据查找到的漫画列表显示漫画的一共有多少个章节
- 根据输入的章节索引下载漫画章节

目前存在的Bug有:

- 当下载章节较多时,会出现远程主机被关闭的问题

ToDo-Next:

- 实现多进程
- 显示出查找到漫画列表
- 目前下载的图片都下载到根目录中,需要生成一个文件夹来保存下载的图片
- 将下载的章节内容生成PDF供阅览

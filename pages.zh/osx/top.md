# top

> 显示运行进程的动态实时信息。
> 更多信息：<https://keith.github.io/xcode-man-pages/top.1.html>.

- 执行 top 命令，界面中提供所有选项：

`top`

- 按内部内存大小排序进程（默认顺序 - 进程 ID）：

`top -o mem`

- 首先按 CPU 启动顺序排序进程，然后按运行时间排序：

`top -o cpu -O time`

- 只显示给定用户拥有的进程：

`top -user {{用户名}}`

- 获取有关交互式命令的帮助（我测试并没看到这个功能）：

`<?>`

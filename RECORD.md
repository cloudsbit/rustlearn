#### 当前常用记录

WSL:

TUMX:
参考：[tmux简明快速教程](http://blog.kissdata.com/2014/07/29/tmux.html)

```shell
# 常用命令：
# 创建一个新的session joh:
tmux new -s joh
# 休眠 joh session
tmux detach -s joh  或者 {前缀} + d
# 恢复一个session
tmux attach -t joh
# 杀死整个joh session
tmux kill-session -t joh 或者 {前缀} + : kill-server

# 前缀： CTRL + B
{前缀} "     模向分隔面板
{前缀} %     纵向分隔面板
{前缀} x     关闭面板
{前缀} 上下键 上一个及下一个分隔面板(面板切换)
{前缀} 空格键 切换面板布局

{前缀} t      显示时钟

# 调整面板大小
Ctrl+B Alt+Arrow

# 窗口相关
{前缀} c      创建新窗口
{前缀} &      关闭窗口
{前缀} n      选择下一个窗口
{前缀} p      选择前一个窗口
{前缀} 0~9    选择几号窗口

```

VIM:

```shell
# 分屏大小的调节
Ctrl+W +/-  (水平)增加和减少
Ctrl+W >/<  (垂直)增加和减少
Ctrl+W _    水平最大化尺寸
Ctrl+W |    垂直最大化尺寸

```

Rust Tools:



#### 知识盲点：

疑惑用法1：在match中，这种"x if x < 1"的语法哪里有说明？

![image-20211022090839447](images\image-20211022090839447.png)

疑惑用法2： `core::result::Result` and `std::result::Result`有何不同？
**there are the same structure, std just reexport it. Like duplicate said, a lot of thing in core are just reexported in std**

疑惑用法3：


分散的知识点: 

1. [What does {:?} mean in a Rust format string?](https://stackoverflow.com/questions/38157335/what-does-mean-in-a-rust-format-string)


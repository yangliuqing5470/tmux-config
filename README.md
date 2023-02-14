# 安装(macos)
## 安装Tmux
```bash
brew install tmux
```
## 安装插件
```bash
git clone https://github.com/tmux-plugins/tpm.git ~/.tmux/plugins/tpm
```
# 使用方式
## 下载配置文件
```bash
git clone https://github.com/yangliuqing5470/tmux-config.git ~/.tmux-config
```
## 创建一个会话
```bash
tmux new -s <name>
```
## 激活配置文件
```bash
prefix + :
输入下面命令
source-file ~/.tmux-config/tmux.conf
// prefix 在tmux中的默认是 Ctrl+b, 配置文件中改为 Ctrl+a
```
## 在创建的会话中执行命令
```bash
安装插件
prefix + I
更新插件
prefix + U
// prefix 在tmux中的默认是 Ctrl+b, 配置文件中改为 Ctrl+a
```

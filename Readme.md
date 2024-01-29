# Introduction
This is my tmux configuration.

## Install
```shell
brew install tmux
git clone https://github.com/chaozwn/tmux.git ~/.config/tmux
```

Then
```shell
tmux
```
press `ctrl+t+I`

### 在.zshrc或者或者.bashrc中添加
```shell
export TERM="xterm-256color"
```

#Tmux的配置和使用

#### 创建session

```shell
tmux new -s session_name
```

#### 断开会话(不会关闭session)

```shell
prefix + d
tmux detach
```

#### 回到session

```shell
tmux a -t session_name
```

#### 关闭会话

```shell
tmux kill-session -t session_name
```

#### 切换会话

```shell
tmux switch -t session_name
```

#### 重命名会话

```shell
tmux rename-session -t session_name new_session_name
prefix $
```

#### 关闭服务器(全部关闭)

```shell
tmux kill-server
```

#### 查看所有会话

```shell
tmux ls
prefix s
```

#### 安装插件

```shell
prefix I
```

#### 创建新window

```shell
prefix c
```

#### 导航到指定窗口

```shell
prefix number
```

#### 关闭窗格

```shell
prefix x
```

#### 将当前窗格分为一个独立窗口

```shell
prefix !
```

#### 窗口重命名

```shell
prefix ,
```

#### 下一个上一个窗口

```
prefix n/prefix p
```

#### 选择窗口

```
prefix w
```


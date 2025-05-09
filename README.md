# proj150-Rust-ContainerOS
用Rust语言实现一个轻量级的全容器化OS

### 项目名称
proj150-Rust-ContainerOS

### 项目描述

用Rust语言实现一个轻量级的全容器化OS，可参考RancherOS的实现。
随着容器化的演进，业务app跑在容器里，对host OS的依赖已经非常小，传统linux host OS已经过于繁重，以及增加攻击面。
各大厂相继出现了containerOS，例如AWS bottlerocket，Google Container-Optimized OS，但这种路线还是采用的包裁剪，很难达到足够的精简。
而RancherOS则走的是从0-1的路线，Hos足够精小，仅有一个containerd，甚至没有glibc/bash等，所有的进程包括系统服务都跑在容器里。
请用rust重新写一个ContainerOS，架构参考rancherOS

https://github.com/rancher/os

### 所属赛道

2025全国大学生操作系统比赛的“OS功能挑战”赛道



### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2025全国大学生操作系统比赛”的章程和技术方案要求



### 项目导师

刘双

* github id：liushuang

* email： ls123674@antgroup.com



### 难度

中等



### 特征

偏系统虚拟化方面的技术。



### License

任意开源license都可


## 预期目标

### 注意：下面的内容是建议内容，不要求必须全部完成。选择本项目的同学也可与导师联系，提出自己的新想法，如导师认可，可加入预期目标

#### 第一题：
X86虚拟机能启动rust ContainerOS，并启动必要的系统服务（cron、syslog、audit等）
#### 第二题：
能通过docker启动一个标准镜像，以及OCI接口
#### 第三题：
能通过k8s接口运行一个标准镜像
#### 第四题：
支持arm64



<p align=center>
  <a href="https://github.com/EscapeLife/love_girlfriend.git">
    <img src="https://escapelife-1257414824.cos.ap-shanghai.myqcloud.com/never-forget-why-you-started.gif" width="680" height="120" alt="Raspi-X" >
  </a>
</p>

<p align=center>
  <b>awesome-builder 🐚 强大的docker构建器和相关脚本</b>
</p>

<p align="center">
  <a href="https://github.com/EscapeLife/awesome-builder.git"><img src="https://img.shields.io/badge/Project-awesome_builder-green.svg?style=for-the-badge&logo=ubuntu" alt="love_girlfriend"></a>
  <a href="https://github.com/EscapeLife/awesome-builder.git"><img src="https://img.shields.io/badge/Author-Escape-orange.svg?style=for-the-badge&logo=vim" alt="love_girlfriend"></a>
  <a href="https://github.com/EscapeLife/awesome-builder.git"><img src="https://img.shields.io/badge/Languages-Dockerfile-yellow.svg?style=for-the-badge&logo=docker" alt="love_girlfriend"></a>
</p>

<p align=center>
  <a href="https://github.com/EscapeLife/DotFiles.git">
    <img src="https://github.com/EscapeLife/awesome-builder/blob/master/images/awesome-docker.jpg" >
  </a>
</p>

## 1. DockerFiles

> **Best practices for writing Dockerfiles.**

| 编号 | 文件名称 | 功能说明 |
| :-----: | :-----: | :----- |
| 1 | [**`celery`**](https://github.com/EscapeLife/awesome-builder/tree/master/DockerFiles/celery) | 引用自Celery项目，用于编写Dockerfile借鉴模板 |
| 2 | [**`goaccess`**](https://github.com/EscapeLife/awesome-builder/tree/master/DockerFiles/goaccess) | 这是一款开源、实时、强大、具有交互视图界面的命令行Web日志分析工具 |
| 3 | [**`lsyncd`**](https://github.com/EscapeLife/awesome-builder/tree/master/DockerFiles/lsyncd) | 海量文件实时同步解决方案，支持主备切换使用 |
| 4 | [**`postgresql`**](https://github.com/EscapeLife/awesome-builder/tree/master/DockerFiles/postgresql) | 优秀的PostgreSQL数据库备份策略(热备) |

## 2. Compose

> **Best practices for writing compose files.**

| 编号 | 文件名称 | 功能说明 |
| :-----: | :-----: | :----- |
| 1 | [**`watchtower`**](https://github.com/EscapeLife/awesome-builder/blob/master/Compose/watchtower/docker-compose.yml) | 容器的自动更新解决方案  |
| 2 | [**`portainer`**](https://github.com/EscapeLife/awesome-builder/blob/master/Compose/portainer/docker-compose.yml) | 简化的自有化Docker容器管理工具(单机或多机)  |

## 3. Scripts

> **Best practices for writing shell and python scripts and so on.**

| 编号 | 文件名称 | 功能说明 |
| :-----: | :-----: | :----- |
| 1 | [**`kill_all_process.sh`**](https://github.com/EscapeLife/awesome-builder/blob/master/Scripts/kill_process/kill_all_process.sh) | 解决在Linux系统中程序意外退出删除进程树，防止孤儿进程的出现 |
| 2 | [**`/etc/ufw/after.rules`**](https://github.com/EscapeLife/awesome-builder/blob/master/Scripts/after_rules/after.rules) | 解决UFW无法管理Docker发布出来的端口问题 |
| 3 | [**`setup.py`**](https://github.com/EscapeLife/awesome-builder/blob/master/Scripts/setup/setup.py) | 一个Python程序打包的示例setup.py配置脚本文件 |
| 4 | [**`pyproject.toml`**](https://github.com/EscapeLife/awesome-builder/blob/master/Scripts/pyproject/pyproject.toml) | 一个Python程序打包的示例pyproject.toml配置脚本文件 |
| 5 | [**`image2run.sh`**](https://github.com/EscapeLife/awesome-builder/blob/master/Scripts/image2run/image2run.sh) | 将docker镜像导出的tar包转换成为压缩小/自解压/自导入的run包 |
| 6 | [**`wait_for_ready.sh`**](https://github.com/EscapeLife/awesome-builder/blob/master/Scripts/wait_for_ready/wait_for_ready.sh) | 解决运行Compose文件，服务启动依赖关系问题 |
| 7 | [**`docker_patch.py`**](https://github.com/EscapeLife/awesome-builder/blob/master/Scripts/docker_patch/docker_patch.py) | 一个快速迭代的Docker补丁包部署的小程序 |
| 8 | [**`gooey`**](https://github.com/EscapeLife/awesome-builder/blob/master/Scripts/gooey) | 将任何Python命令行程序转换为完整的GUI应用程序 |

## 4. Common

> **Best universal shell and python scripts.**

| 编号 | 文件名称 | 功能说明 |
| :-----: | :-----: | :----- |
| 1 | [**`find_big_file.sh`**](https://github.com/EscapeLife/awesome-builder/blob/master/Common/bash/find_big_file.sh) | 查找当前Linux操作系统中的大文件(可以指定文件大小范围) |

| 编号 | 文件名称 | 功能说明 |
| :-----: | :-----: | :----- |
| 1 | [**`walk_dir.py`**](https://github.com/EscapeLife/awesome-builder/blob/master/Common/python/) | 实现Linux下tree命令遍历文件目录夹的功能 |
| 2 | [**`random_passwd.py`**](https://github.com/EscapeLife/awesome-builder/blob/master/Common/python/random_passwd.py) | 自动生成随机密码(可以指定随即密码长度范围) |
| 3 | [**`collect_server_info.py`**](https://github.com/EscapeLife/awesome-builder/blob/master/Common/python/collect_server_info.py) | 收集Linux操作系统服务器相关信息(包含CPU/内存/磁盘) |
| 4 | [**`linux_tail_f.py`**](https://github.com/EscapeLife/awesome-builder/blob/master/Common/python/linux_tail_f.py) | 实现Linux下tail命令动态查看日志的功能 |
| 5 | [**`calculator.py`**](https://github.com/EscapeLife/awesome-builder/blob/master/Common/python/calculator.py) | 实现一个简单的计算器 |

## 5. Contact

> **Below is my personal contact information.**

<p align="center">
    <img src="https://escapelife-1257414824.cos.ap-shanghai.myqcloud.com/escape-wechat-qrcode-1.gif" width="280" height="280" alt="WX" align="left" />
</p>

- **💭 [Name] 💭**
  - 🐠 **[`EscapeLife`](https://escapelife.github.io)** 😏
- **💭 [Induction] 💭**
  - 🏦 **[`Focusing P.A.I`](https://paodingai.com/)** 😂
- **💭 [Email] 💭**
  - 📫 **[`wenpanhappy@gmail.com`](https://escapelife.github.io)** 🤔
- **💭 [Myblog] 💭**
  - 🍺 **[`https://escapelife.github.io`](https://escapelife.github.io)** 😚
- **💭 [License] 💭**
  - 🚧 [**`Apache License, Version 2.0`**](http://www.apache.org/licenses/LICENSE-2.0.html)😝

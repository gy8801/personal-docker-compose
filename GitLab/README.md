# 说明
> https://docs.gitlab.cn/jh/install/docker.html
## 设置数据卷映射
添加一个新的环境变量 `$GITLAB_HOME`，指向配置、日志和数据文件所在的目录。 确保该目录存在并且已授予适当的权限。
对于 Linux 用户，将路径设置为 `/srv/gitlab`：
```sh
export GITLAB_HOME=/srv/gitlab
```
环境变量配置文件为`~/.bashrc`或`/etc/profile`
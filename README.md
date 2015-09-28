# useful-command
```bash
# 显示磁盘使用容量
df -H /

# 显示端口占用情况
netstat -aptn

# 显示当前目录下文件夹大小
du -hx --max-depth=1 .

# 生成32位随机密码（openssl）
openssl rand -base64 32

# docker 启动容器并绑定 host 目录
docker run -t -i -v ~:/host ubuntu:14.04

# 显示 Linux 内核版本
uname -ir

# ssh 保持长连接
ssh -o ServerAliveInterval=100 user@host

# 查看所有用户
cat /etc/passwd

# 修改目录权限
sudo chown -R user /path/to/the/directory

```

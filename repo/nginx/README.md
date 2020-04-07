## nginx 官方源

### CentOS & RHEL

### Debian
安装先决条件
```bash
sudo apt install curl gnupg2 ca-certificates lsb-release
```
添加Nginx的官方密钥
```bash
curl -fsSL https://nginx.org/keys/nginx_signing.key | sudo apt-key add -
```
安装nginx
```bash
sudo apt update				# 更新可用软件包列表
sudo apt install nginx		# 安装Nginx
```
### Ubuntu
安装先决条件
```bash
sudo apt install curl gnupg2 ca-certificates lsb-release
```
添加Nginx的官方密钥
```bash
curl -fsSL https://nginx.org/keys/nginx_signing.key | sudo apt-key add -
```
安装nginx
```bash
sudo apt update				# 更新可用软件包列表
sudo apt install nginx		# 安装Nginx
```
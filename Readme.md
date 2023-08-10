# 使用教程

### 首先安装 nodejs

```shell
# nodejs 版本为 v14.9.0
wget https://nodejs.org/dist/v14.9.0/node-v14.9.0-linux-x64.tar.gz
tar zxvf node-v14.9.0-linux-x64.tar.gz
vim /etc/profile
export NODEJS_HOME=/usr/local/src/node-v14.9.0-linux-x64
export PATH=$NODEJS_HOME/bin:$PATH
source /etc/profile
```

### 安装所需依赖

```shell
npm install
```

### 编写 CSS 样式

```shell
# 构建项目
npm run build
```

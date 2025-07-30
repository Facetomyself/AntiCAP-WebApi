<div align="center">

# AntiCAP WebApi

</div>

## 🌍环境说明
```
python 3.10.6
```

<div align="center">

## 📁 安装

</div>

### 方式一：Docker部署（推荐）

#### 1. 克隆仓库
```
git clone https://github.com/81NewArk/AntiCAP-WebApi
cd AntiCAP-WebApi
```

#### 2. 配置环境变量
```
cp .env.example .env
# 编辑.env文件，设置用户名、密码等配置
```

#### 3. 使用Docker Compose启动
```
docker-compose up -d
```

#### 4. 或使用Docker命令构建
```
# 构建镜像（支持ARM架构）
docker build --platform linux/amd64,linux/arm64 -t anticap-webapi .

# 运行容器
docker run -d \
  --name anticap-webapi \
  -p 6688:6688 \
  --env-file .env \
  anticap-webapi
```

### 方式二：本地安装

#### 1.Git克隆仓库 或 手动下载

```
git clone https://github.com/81NewArk/AntiCAP-WebApi

cd AntiCAP-WebApi
```



#### 2.使用清华源下载项目所需依赖
```
pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
```


#### 3.配置环境变量
```
cp .env.example .env
# 编辑.env文件，设置用户名、密码等配置
```


#### 4.运行main.py
```
python main.py
```


###  Web页面
❗ 服务器部署打开6688端口

```
# Web主页:

http://127.0.0.1:6688/
http://localhost:6688/

# 开发者文档：

http://127.0.0.1:6688/docs
http://localhost:6688/docs
```

### 环境变量配置

| 变量名 | 说明 | 默认值 |
|--------|------|--------|
| SECRET_KEY | JWT密钥（留空自动生成） | 自动生成 |
| ACCESS_TOKEN_EXPIRE_MINUTES | 访问令牌过期时间(分钟) | 86400 |
| VALID_USERNAME | 用户名 | admin |
| VALID_PASSWORD | 密码 | admin |
| PORT | 服务端口 | 6688 |

<div align="center">

## 📄 使用说明

</div>

```
https://www.bilibili.com/video/BV1xYGgz9ENE
```
# 🐧 QQ交流群

<br>

<div align="center">

<img src="https://free.picui.cn/free/2025/07/04/6867f1907d1a0.png" alt="QQGroup" width="200" height="200">

</div>

# 🚬 请作者抽一包香香软软的利群
<br>

<div align="center">

<img src="https://free.picui.cn/free/2025/07/04/6867efd0bd67e.png" alt="Ali" width="200" height="200">
<img src="https://free.picui.cn/free/2025/07/04/6867efd0d7cbb.png" alt="Wx" width="200" height="200">

</div>





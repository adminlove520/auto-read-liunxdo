## 使用方法一：油猴脚本

自动刷 Linux do 的文章以及自动点赞
代码在 index_passage_list 中
油猴：https://greasyfork.org/en/scripts/489464-auto-read

## 使用方法二：puppeteer 无头运行

### 1.设置环境变量

.env 里面设置用户名 密码

### 2.运行

#### Windows

```sh
npm install
node .\pteer.js
```

#### Linux 额外安装以下包，运行命令相同

```sh
sudo apt-get update
sudo apt install nodejs npm  -y
sudo apt-get install -y wget unzip fontconfig locales gconf-service libasound2 libatk1.0-0 libc6 libcairo2 libcups2 libdbus-1-3 libexpat1 libfontconfig1 libgcc1 libgconf-2-4 libgdk-pixbuf2.0-0 libglib2.0-0 libgtk-3-0 libnspr4 libpango-1.0-0 libpangocairo-1.0-0 libstdc++6 libx11-6 libx11-xcb1 libxcb1 libxcomposite1 libxcursor1 libxdamage1 libxext6 libxfixes3 libxi6 libxrandr2 libxrender1 libxss1 libxtst6 ca-certificates fonts-liberation libappindicator1 libnss3 lsb-release xdg-utils wget

```

## 使用方法三：GitHub Action 每天 0 点阅读

### 1. fork 仓库

### 2.设置环境变量

.env 里面设置用户名 密码

### 3.启动 workflow

教程：https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web?tab=readme-ov-file#enable-automatic-updates

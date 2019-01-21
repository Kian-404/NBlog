# node_blog

## 项目运行

``` bash
# 克隆项目
git clone https://github.com/tianjianen/Node_blog.git

# 下载依赖
npm install

# 测试环境运行项目 打开端口localhost:3000
npm run dev

# 生产环境运行项目
npm run start


# 生产环境配置文件配置
/config/production.js 


# 项目文件目录结构


.
├── README.md
├── config
│   ├── default.js
│   └── production.js
├── index.js
├── lib
│   └── mongo.js
├── middlewares
│   └── check.js
├── models
│   ├── comments.js
│   ├── posts.js
│   └── users.js
├── package-lock.json
├── package.json
├── public
│   ├── css
│   └── img
├── routes
│   ├── comments.js
│   ├── index.js
│   ├── posts.js
│   ├── signin.js
│   ├── signout.js
│   └── signup.js
└── views
    ├── 404.ejs
    ├── components
    ├── create.ejs
    ├── edit.ejs
    ├── footer.ejs
    ├── header.ejs
    ├── post.ejs
    ├── posts.ejs
    ├── signin.ejs
    └── signup.ejs

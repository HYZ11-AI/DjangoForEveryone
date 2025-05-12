SimpleTodo/
├── public/               # 静态资源，用于存放前端构建的文件
│   └── index.html        # 前端应用的主页面
├── src/                  # 前端 Vue.js 应用
│   ├── components/       # Vue 组件
│   │   └── TodoItem.vue  # 单个待办事项组件
│   ├── App.vue           # 主界面
│   ├── main.js           # 启动入口
│   └── assets/           # 静态资源（如CSS、图片等）
│       └── styles.css    # 全局样式
├── backend/              # 后端 Django 应用
│   ├── baseapp/          # Django 项目目录
│   │   ├── __init__.py
│   │   ├── settings.py   # 配置文件
│   │   ├── urls.py       # URL 路由配置
│   │   ├── wsgi.py
│   │   └── asgi.py
│   ├── DjangoExtensions/ # Django 扩展应用（如果需要）
│   │   ├── __init__.py
│   │   ├── settings.py   # 配置文件
│   │   ├── urls.py       # URL 路由配置
│   │   ├── wsgi.py
│   │   └── asgi.py
│   ├── ExtendUserModel/  # 用户模型扩展应用
│   │   ├── __init__.py
│   │   ├── models.py     # 数据库模型
│   │   ├── views.py      # 视图函数
│   │   └── urls.py       # URL 路由配置
│   ├── db.sqlite3        # 数据库文件
│   ├── manage.py         # Django 管理脚本
│   └── README.md         # 后端项目说明
├── package.json          # 前端项目依赖
├── README.md             # 项目说明
└── venv/                 # 虚拟环境目录
    ├── Lib
    ├── bin
    ├── include
    └── lib
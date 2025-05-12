<<<<<<< HEAD
SimpleTodo/
├── public/               # 静态资源
│   └── index.html        # 主页面模板
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
│   ├── DjangoExtensions/ # Django 扩展应用
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
=======
# DjangoForEveryone

## A repository for JimShapedCoding Django Tutorials

### Architecture of this repository:

 - baseapp - A Django application that I will work on, throughout some of my tutorials to explain and show topics.
   - This app includes a very basic customization, for visualizing data nice. And also templates/static directories being created there
 - In order to see more content on this repo, checkout to other branches like `post-tutorial`, to see the project status after I finish working on, in some tutorial.


### 克隆项目

```bash
git clone https://github.com/2217481412huang/j.git
cd j


### 安装依赖

python -m venv myenv
激活虚拟环境
myenv\Scripts\activates

### 启动项目
启动项目
python manage.py runserver

项目将运行在  http://127.0.0.1:8001/ 

11s
>>>>>>> 86ae1c09f962c13ff821b1749ec3754e762a53e1

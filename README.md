# flaskvue

#创建虚拟机环境
cd 到当前目录
virtualenv venv
pip install -r requirement

#数据库迁移指令
python manage.py db init
python manage.py db migrate
python manage.py db upgrade

#启动flask
python manager.py runserver 

#安装前端包
cd vuejs
npm install 

#启动前端包
npm run dev

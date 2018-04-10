说明和操作步骤：
1. git clone https://github.com/miguelgrinberg/flasky-first-edition.git
2. git checkout 8g
  将这个8g的版本内容复制到桌面，放入flask-8g包
3. cd flask-8g
4. heroku create flasky-8g
5. heroku git:remote -a flasky-8g
6. heroku addons:create heroku-postgresql:hobby-dev
7. heroku pg:promote postgresql-objective-28623
8. git init
9. git add .
10.git commit -m 'v1.0'
11.git push heroku master
12.heroku run python manage.py deploy
13.heroku restart

狗书第一版git checkout 8g, 然后直接切到17章导入部署代码和各个环境，后面部署成功的源码
对接的邮箱账号是wcy24@foxmail.com, app是flasky-8g，地址就是https://flasky-8g.herokuapp.com/



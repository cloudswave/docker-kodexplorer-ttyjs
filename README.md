# docker-kodexplorer-ttyjs
docker下集成了kodexplorer和ttyjs

#quick start
run the command in docker with foregroud:
`docker run -t -i -p 23:22 -p 3001:3000 -p 81:80 ethanzhu/kodexplorer-ttyjs`
or background:
`docker run -d -p 23:22 -p 3001:3000 -p 81:80 ethanzhu/kodexplorer-ttyjs`
#the note
- 访问webshell: http://{ip}:3001
- 访问KODExplorer：http://{ip}:81
- 登陆ssh: ssh ubuntu@{ip} -p 23
- 网站根目录：/usr/www
- KODExplorer：admin admin
- ubuntu账号:ubuntu ubuntu

服务命令:
```
service nginx stop/start/restart
service php5-fpm stop/start/restart
tty.js -p 3000 -d
```
tty.js地址：https://github.com/chjj/tty.js
KODExplorer：https://github.com/kalcaddle/KODExplorer

1.shadowsocks的使用：
    1)  /home/adron/.nvm/versions/node/v0.12.5/lib/node_modules/shadowsocks
    2)  运行命令：nohup node bin/ssserver &

2.Ghost博客
    1）切换Nodejs到0.10.35后先删除sqlite3在npm install --production，然后运行npm start /// NODE_ENV=production pm2 start index.js

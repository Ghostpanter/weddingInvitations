# weddingInvitations

结婚请柬 婚礼电子请帖 婚礼H5 邀请函

clone 到本地可直接打开index.html 文件查看效果, 仅支持移动端, pc需使用手机模式

## 直接部署

```bash
git clone https://github.com/nijun008/weddingInvitations.git
git clone -b dependabot/npm_and_yarn/qs-and-express-6.11.0 https://github.com/nijun008/weddingInvitations.git
git clone -b dependabot/npm_and_yarn/express-4.17.3 https://github.com/nijun008/weddingInvitations.git
cd weddingInvitations
npm cache clean --force
rm -rf node_modules/
rm package-lock.json
npm install
node app
```

默认端口为8081, 可以在app.js中修改端口

## Docker部署

```bash
docker build -t xxx:xxx .

docker run -dit -p 宿主机端口:80 xxx:xxx 
```

访问 IP即可

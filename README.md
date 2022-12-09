### 安装依赖. 
1. 安装nodejs . 
```
wget https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh && chmod +x install.sh 
./install.sh 
source ~/.bashrc

nvm install v16.13.0
```

2. 安装项目依赖. 
```
npm install -g cross-env
npm install 

```

3. 运行
```
npm run start
```

所有逻辑都在 `examples/ding-dong-bot.ts` 文件，可以自行修改。


包含关键词:  `请问` 、 `帮我`  才会做出回应. 


依赖chatgpt: 

[git@github.com:clearcodecn/chatgpt.git](https://github.com/clearcodecn/chatgpt)

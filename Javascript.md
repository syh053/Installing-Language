# Installing nvm to use Javascript

這是透過安裝 nvm [Node 版本管理控制]，並安裝 Node 的手順

<h3 ><a href="https://github.com/coreybutler/nvm-windows" target="_blank">資料來源</a></h3>


1. 進入 nvm <a href="https://github.com/coreybutler/nvm-windows" target="_blank">官網</a>

2. 點擊
![image](https://ppt.cc/fnCXEx@.png)

3. 運行以下指令查看 pyenv 是否安裝成功
![image](https://ppt.cc/fTwWux@.png)

4. 打開終端機輸入 nvm version 確定安裝成功
```
nvm version
```

5. 查看 Windows 上可以使用 nvm 安裝的 Node 的版本
```
nvm list available
```

6. 安裝指令
```
nvm install <version>
```

7. 指定要使用的 Node 版本
```
nvm use <version>
```

8. 查看 Node.js 版本
```
node -v
```
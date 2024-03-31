# Installing nvm to use Javascript

這是透過安裝 nvm [Node 版本管理控制]，並安裝 Node 的手順

<h3 ><a href="https://github.com/coreybutler/nvm-windows" target="_blank">資料來源</a></h3>


1. 進入 nvm <a href="https://github.com/coreybutler/nvm-windows" target="_blank">官網</a>
___ 


2. <p>點擊</p>
![image](https://ppt.cc/fnCXEx@.png)
___

3. <p> nvm-setup.zip 進行下載安裝</p>
![image](https://ppt.cc/fTwWux@.png)
___

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
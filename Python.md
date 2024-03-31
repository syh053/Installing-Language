# Installing-Language

這是透過安裝 pyenv [Python 版本控制]，並安裝 Python 的手順

<h3 ><a href="https://github.com/pyenv-win/pyenv-win" target="_blank">資料來源</a></h3>



1. 進入 git <a href="https://github.com/pyenv-win/pyenv-win" target="_blank">官網</a>

2. 複製以下指令後，到 PowerShell 執行

```
Invoke-WebRequest -UseBasicParsing -Uri "https://raw.githubusercontent.com/pyenv-win/pyenv-win/master/pyenv-win/install-pyenv-win.ps1" -OutFile "./install-pyenv-win.ps1"; &"./install-pyenv-win.ps1"
```

3. 運行以下指令查看 pyenv 是否安裝成功
```
pyenv --version
```

4. 執行以下指令查看 pyenv-win 支援的 Python 版本列表
```
pyenv install -l
```

5. 運行pyenv install <version>安裝支援的版本
```
pyenv install <version>
```

6. 運行pyenv global <version>將指定 Python 版本設定為全域版本
```
pyenv global <version>
```

7. 運行pyenv local <version>將指定 Python 版本設定為區域版本，
   指令完成後會在資料夾輸出一個 .python-version 的檔案
```
pyenv local <version>
```

8. 檢查您正在使用的 Python 版本及其路徑
```
pyenv version
<version> (set by \path\to\.pyenv\pyenv-win\.python-version)
```

9. 將已安裝的套件匯出一份清單
```
pip freeze > requirements.txt
```

10. 安裝清單中的套件
```
pip -r requirements.txt
```


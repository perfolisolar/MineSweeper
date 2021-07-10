# 生成可执行文件

```
pyinstaller -Dw -n Sweeper -i Sweeper.ico code\main.py code\heroDialog.py code\limit.py code\mineLabel.py code\mineSweeperGUI.py code\rule.py code\selfDefinedParameter.py code\statusLabel.py code\superGUI.py code\symbol.py code\symbolDialog.py

xcopy .\code\media .\dist\Sweeper\
```

# 执行可执行文件

```
.\dist\Sweeper\Sweeper.exe
```

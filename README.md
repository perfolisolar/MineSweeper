**湘潭大学2021年上学期软件设计实践**

使用python实现扫雷游戏

---

# 生成可执行文件

```
pyinstaller -Dw -n Sweeper -i Sweeper.ico code\main.py code\heroDialog.py code\limit.py code\mineLabel.py code\mineSweeperGUI.py code\rule.py code\selfDefinedParameter.py code\statusLabel.py code\superGUI.py code\symbol.py code\symbolDialog.py

xcopy .\code\media .\dist\Sweeper\
```

# 执行可执行文件

```
.\dist\Sweeper\Sweeper.exe
```

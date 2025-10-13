# MinetechEvolution
https://www.curseforge.com/projects/1028308  
Issues tracker for the Minetech Evolution modpack. Please submit bugs [here](https://github.com/Blue-Beaker/MinetechEvolution/issues).  
Minetech Evolution整合包的故障跟踪器. 请在[此](https://github.com/Blue-Beaker/MinetechEvolution/issues)提交bug.  
## Frequently Asked Questions/常见问题
A machine/block/item from some mod can't be found.  
某模组的某个机器/方块/物品没有.  
- If that can't be found in JEI, it's mostly locked behind a stage.  
- 如果该内容无法在JEI找到, 则很可能是需要达成某个阶段才能解锁.

Chapter 3 and later chapters?  
第三章及之后的章节?  
- They are still Work In Progress, can be unplayable, and may have breaking changes in later updates. If you want to play, please make a manual backup of your world before doing it.  
- 这些章节仍未完工, 可能不可玩, 后续的更新也可能引入破坏性改动. 如果你想玩这些部分, 建议在此之前为存档做个手动备份.  

My save have crashed. What should I do?  
我的存档损坏了. 我该做什么?  
- The modpack comes with automatic backups. Goto `.minecraft/backups`, run `restore-script.bat` or `restore-script.sh` and follow the wizard to recover from backups. The modpack has differential backups by default.  
- 整合包有自动备份. 前往`.minecraft/backups`, 运行`restore-script.bat`或`restore-script.sh`, 然后跟随向导来恢复备份. 整合包默认设置为差异备份(differential).  
- 注意恢复向导只有英文.  
- 第一步选择备份种类 - 没有修改过配置就选择differential(差异备份).  
- 第二步选择恢复方式 - 将备份导出为zip压缩包,恢复单个文件,或恢复整个世界.  
- 第三步选择是客户端还是服务端 - 如果没使用独立服务端,则选择Client(客户端).  
- 选择客户端后, 继续选择要恢复的世界, 最后输入y确认. 恢复过程中不要打开存档.  

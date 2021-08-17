# Stair Speedtest Reborn 个人修改版
Fork From [tindy2013/stairspeedtest-reborn](https://github.com/tindy2013/stairspeedtest-reborn)

# 如何进行个人修改？
1.Fork本仓库

2.切换到 ./src/version.h 修改自定义的版本号，将"CommandManager专版"修改为你自己的版本号，如果您不放心本版本，您可以Fork[官方仓库](https://github.com/tindy2013/stairspeedtest-reborn)

3.切换到 ./src/renderer.cpp 在该文件内搜索"Generated at"将"CM.在线测速"修改为你自己的，如果您Fork的是[官方仓库](https://github.com/tindy2013/stairspeedtest-reborn)那么需要将整行进行替换： 
```
   std::string gentime = "Generated at " + getTime(3) + " by CM.在线测速";
```
4.如果需要更改其他内容，请自行摸索

# winx64HookLib
x64HOOK库

支持系统:win64

项目环境:Vs2015

作者:火哥

QQ群：1026716399



1.此库没有任何汇编解析引擎

2.小巧简单


注意: 由于没有做相对地址的处理，导致在HOOK完毕 跳回要模拟执行原有的指令会有如下问题

1.碰见立即数内存寻址

2.碰见JCC,CALL,JMP等指令 会出现异常


有时间会不定期的更新，希望大家共同开发！打造一个完美，强大的HOOK 库
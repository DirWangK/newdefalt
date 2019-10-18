利用符号执行去除控制流平坦化
安装请参考https://github.com/SnowGirls/deflat

angr新版本下脚本报错，对其进行修改。
参考：修复去除控制流平坦化工具deflat.py https://www.jianshu.com/p/cf72c6128b7a

测试使用angr7.8.9.26 正常

此脚本用来对抗ollvm中的控制流扁平化(-fla)

对于指令替换(-sub)、虚假控制流程(-bcf)未做处理
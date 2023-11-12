# Godot-FtgGameframework
一个标准Ftg动作游戏框架。支持一般动作的一般需求 如动作配表，连段，攻击盒与受击盒的计算。  
Action.json文件内进行静态数据配表。  
CharaObj/ActionControler/Act管理器是三个主要的类  
仔细看 Action.json配表里Action的转换条件。
# 默认出招表
[1] 移动：上下左右移动（上为跳，下为蹲）  
[2]普攻: J-拳普攻（空中/蹲下都是） -》命中后连按 J 旋转长剑 ；I-脚击
[3] 战术动作: 跳时双击向前 向前滑翔一段距离； 双击 前-前 进入奔跑；后退时 接 前-后 转向。
[4] 技能：下-前下-前-脚 转身飞踢！！！ ； 飞踢命中 接 前-脚 长剑上划。
[5] 瞎几把抄的连段：脚击->转身飞踢->长剑上划-》击飞偶也！

************PyComplier************
Scanner:词法分析器
Parser:语法分析器
GUI:图形界面
Main:主程序入口

    输入数据可以为整数,小数,也可以为分数,某些数学函数要注意定义域
    比如math.log取值不可以从0开始.
    应用的开始只需要传入文件名,调用GUI_TEST就可以画图图案

正则表达式:r'(\d+\.\d+[eE][-+]?\d+|\d+\.\d*|[0-9]\d*|0[0-7]+|0x[0-9a-fA-F]+|[a-zA-Z_]\w*|\|\||\+|\-[-]?|\*[*]?|/[/]?|=|\?|:|,|;|\(|\)|\[|\]|\{|\}|\'|\")'
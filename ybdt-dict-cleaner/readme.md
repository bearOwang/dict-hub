功能：可对指定文件（如dict.txt）去重，或将新字典添加到旧字典尾部后对旧字典去重，生成去重后的新文件（新文件名dict-new.txt）

2020/12/30-发现有些字典的换行符是"\n"，有些字典的换行符是"\r\n"  
新增功能：对linux和windows下换行符做适配

2020/12/30-发现有些字典的每行首尾包含空格或制表符  
新增功能：去重的同时会去除每行首尾的空格符(" ")、回车符("\r")、换行符("\n")、制表符("\t")

2020/12/31-发现有些字典的默认字符集不是UTF-8  
新增功能：先识别目标字典的字符集，再用指定字符集打开字典
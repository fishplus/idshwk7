建立info.txt文件，其中包含id和name
选择指定的图片input.png
在对应工具包的终端执行python3 LSBSteg.py encode -i input.png -o test.png -f info.txt完成hide
在对应工具包的终端执行python3 LSBSteg.py decode -i test.png -o info.txt提取信息

# Python2
转义字符，二进制，字符编码
#转义字符  换行：\n；回车：\r; 水平制表符：\t; 退格：\b.
print('hello\nworld')   #\ +转义功能的首字母  n-->newline的首字母表示换行
print('hello\tworld')   #\t 一组四个字符大小的单元格 -->用空格补齐单元格
print('helloooo\tworld')
print("hello\rworld") #\rworld将hello覆盖
print("hello\bworld")#\b退一个格，将o退没

print('http:\\\\www.baidu.com')
print('老师说：\'大家好\'')

#原字符：不希望字符串中的转义字符起作用，就使用原字符，就是在字符串之前加上r或R
print(r'hello\nworld')
#注意事项：最后一个字符不能是反斜线\
#print(r'hello\nworld\')
#可以是两个\\，一个会把\后的’转义，所以不行，\\时则不会
print(r'hello\nworld\\')


#二进制与字符编码
#8位-->8bit==1byte
#1024byte==1KB   1024KB==1MB  1024MB==1GB  1024GB==1TB\
print(chr(0b100111001011000))
print(ord('乘'))

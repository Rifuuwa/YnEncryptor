# 创建时间 2022/6/27的18:50

import hashlib  # 导入hashlib
import os

sha1 = hashlib.sha1()  # 建立sha1对象
pwd = input('键入需要加密的内容:\n')
pwds = str(pwd)
if isinstance(pwd, str) is True:  # 如果该数据的类型是str
    f1 = open('D:/pwd.txt', 'w')  # 新建文件pwd.text保存密文
    sha1.update(pwds.encode("utf8"))
    print(sha1.hexdigest(), file=f1)  # 打印hash
    f1.close()
    print('成功加密至文件D:/pwd.txt')
    os.system('pause')
else:
    print("含有非法字符")

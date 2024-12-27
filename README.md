# zip-压缩
有时候需要压缩文件但是目标机器没办法或者是不方便使用自带的压缩工具-特此诞生此工具

使用方法
zip.exe ./    //这个是吧当前目录压缩
zip.exe C:\Users\wy\Desktop   //这是把C:\Users\wy\Desktop目录压缩
zip.exe C:\Users\wy\Desktop\1.txt //这是把C:\Users\wy\Desktop\1.txt文件压缩

不带名字默认压缩成文件夹或者文件的名字.zip
或者
zip.exe ./ 123.zip   //这个是吧当前目录压缩成123.zip
zip.exe C:\Users\wy\Desktop 123.zip //这个是吧当前目录压缩成123.zip
zip.exe C:\Users\wy\Desktop\1.txt 123.zip //这是把C:\Users\wy\Desktop\1.txt文件压缩成123.zip

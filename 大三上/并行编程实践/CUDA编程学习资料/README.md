## CUDA C Programming

文件扩展名为.cu

在VS2019环境下创建和编译cu文件，具体操作为：

创建空项目->

新建源文件->

> ​		项目->生成依赖性->生成自定义->点击CUDA11.0
>
> ​		**选择cu文件右键选择属性.** 选择项类型为CUDA C/C++

运行本地windows调试器->  注意文件名及其路径中不要有中文！！

成功生成exe文件

![image-20210713094413531](assets/1.png)

- cpptools为vscode下载扩展，类似whl文件，这里通过vsix安装。

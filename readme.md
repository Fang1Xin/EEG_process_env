# 脑电预处理-分析程序环境搭建教程



## 安装软件

1. VScode（程序运行软件） + Anaconda（环境管理）

   https://www.jianshu.com/p/ef1ae10ba950

   使用该教程进行到第一到第四步（前四步中按照自己电脑的系统位数（多为64位）选择安装包，教程中选择的是32位）

2.  创建环境 打开电脑搜索栏 搜索Anaconda Prompt，一般打开于C盘用户名文件夹

   输入

   ```
   D:
   ```

   切换至D盘，再输入（path为environment.yml文件所在文件夹）

   ```
   cd path
   ```

   回车，进入该文件夹后，输入(注意：new name需替换为给这个环境起的名字，按需要修改)

   ```
   conda env create -f environment.yml -n new_name
   ```

   等待运行，环境搭建完成

3. 配置VScode

   https://www.jianshu.com/p/ef1ae10ba950 依旧使用该教程：第七步的1、2、3

4. 将刚配置的eeg环境搭载进Vscode

   设置内核
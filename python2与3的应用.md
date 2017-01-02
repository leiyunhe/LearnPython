# python103个人学习策略

1. 将Py103的课程任务目录下载到本地。
(git clone git@github.com:leiyunhe/*****)
2. 直接在任务目录文件夹中存放程序和文档。
3. 每日将完成的内容推送到github上。

# 下载并安装python3

1. 安装环境时，setup第一步要特别注意勾选“Add Python 3.5 to PATH”（能够确保环境变量设置正确。）
2. 选择customize install方式，在这种模式中可以更改安装路径。
可勾选并安装其他感兴趣的内容。
3. 重启电脑。

# 切换python2与python3

1. 将python2与python3安装文件夹中的python.exe文件分别重命名为python2.exe, python3.exe.
2. 在CLI中，输入python2/python3可分别调用不同的版本。
3. 运行py程序时，输入 python2 ex1.py运行python2程序,或者python3 ex1.py来运行python3程序。
>参考文献：
知乎：[在同一台电脑上如何进行python2与3的切换](https://www.zhihu.com/question/22846291)


# python2与python3的区别
从Learn Python The Hard Way中前七个练习来看，主要区别在于语法表达方式。

python2：<pre><code>print **********</code></pre>

python3: <pre><code>print (**********)</code></pre>

>参考学习资料来源：
>1. [Learn Python The Hard Way](https://learnpythonthehardway.org/book/preface.html)
>2. [廖雪峰的官方网站](http://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000)


# 附加探索：用pip安装模块Pakage（Learn Python The Hard Way-ex46）
看到有人建议安装virtualenv，因此尝试了用pip直接安装其他模块。好处是：不用下载，直接用命令行 <pre><code>pip install nose/distribute/virtualenv</code></pre>

### 第一步：下载并安装pip.
- 下载pip，并解压缩到python27目录。
- 在powershell(CLI)中进入pip目录。
- 运行setup.py。
- 检测pip。

### 第二步：应用pip安装distribute、nose和virtualenv
- CLI进入python27目录。
- 运行 <pre><code>pip install SomePakage</code></pre>.



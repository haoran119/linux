# 面试总结之Linux / Shell

## Linux

* Linux cshrc文件作用
* Linux如何起进程/查看进程/杀进程
* Linux 文件755 代表什么权限
* Linux辅助线程
* Linux进程间通信方法
  * pipeline，msgq...
  * [进程间通信_百度百科](http://baike.baidu.com/link?url=tLNXNQvG5Wo6NptnjkflYaUQbdqW5fC3n40Cv4iF4YSX5EzgfJgwIbZnAfpXLVV1QRvP1293Dgo9qRBmSVfME_)
* Linux基本命令
  * [Linux 命令大全 | 菜鸟教程](http://www.runoob.com/linux/linux-command-manual.html)
* Linux监控命令，监测IO
* [46个Linux面试常见问题](https://mp.weixin.qq.com/s/XdCbBmndv4i4C0nkCvHVWQ)
  * https://www.cnblogs.com/passzhang/p/8552757.html
* [面试中22 个 Linux 高频命令](https://mp.weixin.qq.com/s/pFGssuUe9LzeDY1Te8cHNw)
  * https://blog.csdn.net/weixin_38429587/article/details/79110588
* [面试 | Linux 下的动态链接库问题](https://mp.weixin.qq.com/s/eyF14T5bVDA7uZzf3ehenQ)
* [面试 | Linux 下软链接和硬链接的区别](https://mp.weixin.qq.com/s/DiorIQaLWWMzeozZH2jtiQ)
* [100 道 Linux 笔试题](https://mp.weixin.qq.com/s/Y7_zYt2JoxhjTQhTCLBJOA)
* [10道常见的 Linux 面试题 (qq.com)](https://mp.weixin.qq.com/s/d0JiB7-4VUb7S6_7SBhL_Q)

## Shell 

* What is $*?
  * Will display all the commandline arguments that are passed to the script
* What is the difference between a shell variable that is exported and the one that is not exported?
  * export LANG=C
    * will make the variable LANG the global variable, put it into the global environment. all other processes can use it.
  * LANG=C
    * will change the value only in the current script.
* How will you list only the empty lines in a file (using grep)?
  ```sh
  grep "^[ ]*$" filename.txt
  ```
  * In character set (between [ and ] one space and tab is given)
  * this command will gives all the blank line including those having space and tabs (if pressed)only
* How do you read arguments in a shell program - $1, $2 ?
  ```sh
  #!/bin/sh
  for i in $*
  do
  echo $i
  done
  ```
  * On executig the above script with any number of command-line arguments it will display all the parametsrs.
* How would you get the character positions 10-20 from a text file?
  ```sh
  cut -c10-20 <filename.txt>
  ```
  or
  ```sh
  cat filename.txt | cut -c 10-20
  ```
* 用脚本实现：两个文件有多列，在指定列中找相匹配串。
* 精心汇总的 24 道 shell 脚本面试题 - 程序员大咖
  * https://mp.weixin.qq.com/s/elYuWwwiYR2XzP2K3qDeNQ
  * https://linux.cn/article-5311-1.html
  1. Shell脚本是什么、它是必需的吗?
  2. 什么是默认登录shell，如何改变指定用户的登录shell
  3. 可以在shell脚本中使用哪些类型的变量?
  4. 如何将标准输出和错误输出同时重定向到同一位置?
  5. shell脚本中“if”语法如何嵌套?
  6. shell脚本中“$?”标记的用途是什么？
  7. 在shell脚本中如何比较两个数字 ?
  8. shell脚本中break命令的作用 ?
  9. shell脚本中continue命令的作用 ?
  10. 告诉我shell脚本中Case语句的语法 ?
  11. shell脚本中while循环语法 ?
  12. 如何使脚本可执行 ?
  13. “#!/bin/bash”的作用 ?
  14. shell脚本中for循环语法 ?
  15. 如何调试shell脚本 ?
  16. shell脚本如何比较字符串?
  17. Bourne shell(bash) 中有哪些特殊的变量 ?
  18. 在shell脚本中，如何测试文件 ?
  19. 在shell脚本中，如何写入注释 ?
  20. 如何让 shell 就脚本得到来自终端的输入?
  21. 如何取消变量或取消变量赋值 ?
  22. 如何执行算术运算 ?
  23. do-while语句的基本格式 ?
  24. 在shell脚本如何定义函数呢 ?
* [常见的 shell 脚本面试题](https://mp.weixin.qq.com/s/ZHmZiKXe8vGPThQ2-8qhkA)

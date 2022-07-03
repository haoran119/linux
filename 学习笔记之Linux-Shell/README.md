# 学习笔记之Linux / Shell

* [shell（计算机壳层）_百度百科](http://baike.baidu.com/subview/849/15831672.htm)
* [Shell (computing) - Wikipedia, the free encyclopedia](http://en.wikipedia.org/wiki/Shell_(computing))
* [iSeries QSHELL - Wikipedia](http://en.wikipedia.org/wiki/ISeries_QSHELL)
  * According to IBM, QSHELL is a “UNIX-like” interface built over OS/400. The commands you issue point to programs in a “QSHELL” library. To use QSHELL, key STRQSH or QSH on an iSeries command line.
  * PASE is a “real” UNIX—it is actually AIX. It looks similar to QSHELL, but doesn’t have some of the limitations built into QSHELL. To use PASE, CALL QP2TERM.
* [AIX_百度百科 ](http://baike.baidu.com/view/349664.htm)
  * AIX（Advanced Interactive eXecutive）是IBM基于AT&T Unix System V开发的一套类UNIX操作系统，运行在IBM专有的Power系列芯片设计的小型机硬件系统之上。
* [面试总结之Linux/Shell - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/5559113.html)
* [学习笔记之Linux开发(C语言) - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/5122821.html)
* [介绍 Linux 文件系统](https://mp.weixin.qq.com/s/Hb2W4Dm4fhHOgnX6vUUVGQ)
* [Linux桌面进化史](https://mp.weixin.qq.com/s/Pyyb_hHZJOlylplrmG8uWg)
  * https://opensource.com/article/19/8/how-linux-desktop-grown
* [命令行的艺术](https://mp.weixin.qq.com/s/eiTABcqQ3QwCiCpeEHBszg)
  * https://github.com/jlevy/the-art-of-command-line/blob/master/README-zh.md
* [Unix 激荡 50 年：驱动 Android、iOS 的操作系统是如何从失败开始的?](https://mp.weixin.qq.com/s/9QSsGC8UCtShexD1uQ1Tzg)
  * https://arstechnica.com/gadgets/2019/08/unix-at-50-it-starts-with-a-mainframe-a-gator-and-three-dedicated-researchers/
* [进程调度，一个调度器的自白](https://mp.weixin.qq.com/s/7-NcjLghdnRr01mFTeehhg)
* [10个不得不知的Linux常识](https://mp.weixin.qq.com/s/J_74--fpDDpZIrKP2dq5iw)
  * https://blog.51cto.com/7424593/1744358
* [你应该了解的Linux知识](https://mp.weixin.qq.com/s/OWdfRIGbVYOBHhNfbrVs4Q)
* [Linux下你还知道这些特殊文件？](https://mp.weixin.qq.com/s/odOpV5INmu8tfegyjgU_bg)
* [Ubuntu 的十年回顾](https://mp.weixin.qq.com/s/QTwH8e60wK7DmseiUZL7GQ)
  * https://www.omgubuntu.co.uk/2019/12/ubuntu-defining-moments-2010s
* [Understanding Linux File Permissions | Linuxize](https://linuxize.com/post/understanding-linux-file-permissions/)
  * In Linux, file permissions, attributes, and ownership control the access level that the system processes and users have to files. This ensures that only authorized users and processes can access specific files and directories.
  * In Linux, access to the files is restricted using file permissions, attributes, and ownership. To change the file’s permissions use the chmod command.

## LINUX COMMAND

* Unix/Linux Command Reference
  * [fwunixref.pdf (cmu.edu)](https://www.cs.cmu.edu/~213/recitations/fwunixref.pdf)
  * [fwunixref.pdf (fosswire.com)](https://files.fosswire.com/2007/08/fwunixref.pdf)
* [【ZZ】Linux常用指令 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/8674197.html)
* [Linux常用命令全称 - 程序员大咖](https://mp.weixin.qq.com/s/AMnlM75hAMdrSCURZ4QarQ)
  * https://www.cnblogs.com/wangcp-2014/p/6539035.html
* [176条DevOps人员常用的linux命令速查表 - 程序员大咖](https://mp.weixin.qq.com/s/iQBmEzsGxAx4FJq0SBH6Gg)
* [97条 Linux 常用命令总结 - 机器学习算法与Python学习](https://mp.weixin.qq.com/s/RK_bqt5ihi3jAn9-i1qKtg)
  * https://zhuanlan.zhihu.com/p/36093355
* [图解 Linux 常用命令](https://mp.weixin.qq.com/s/NbwSQOj2fwyYDPFvqtazcA)
  * https://blog.csdn.net/xulong_08/article/details/81463054
* [如何查看Linux系统的状态信息？](https://mp.weixin.qq.com/s/7KptRZpIoquQlwVT2jw-6w)
* [解放你的双手，一个命令帮你减负 - Linux学习](https://mp.weixin.qq.com/s/EA3MbENrq8jfj0bD40ITNw)
* [如何用 Linux 技巧大大提高工作效率？ - CSDN](https://mp.weixin.qq.com/s/wZ7tqB8EDEduQE-2gtUdFA)
* [工作中常用到的Linux命令](https://mp.weixin.qq.com/s/tuy46Lqf6gDY7QiWsCH5pQ)
* [Linux最常用命令](https://mp.weixin.qq.com/s/rpNxF0iD8fGZd8r-lnIdUA)
  * https://blog.csdn.net/xulong_08/article/details/81463054
* [Linux上，最常用的一批命令解析（10年精选）](https://mp.weixin.qq.com/s/PO0h-5xlHiZZSOr7Dw0Fjg)
* [Linux 实用指令大全](https://mp.weixin.qq.com/s/VTCoiglKNQKHEKQ_M8drCg)
  * https://blog.csdn.net/qq_42322103/article/details/96307643
* [从命令行同时移动多种文件类型的小技巧](https://mp.weixin.qq.com/s/6UGkNTFj67PeCHPohlRZXQ)
* [Linux 中删除目录的多种方法](https://mp.weixin.qq.com/s/HAt6fJEuL1SqXBTRPFujMw)
  * https://www.linuxidc.com/Linux/2019-08/159921.htm
* [软件测试工程师的 Linux 十大场景命令使用](https://mp.weixin.qq.com/s/5uFRLtz-fDfUqNRdUr6gUQ)
* [一个录制并回放Linux终端会话的命令](https://mp.weixin.qq.com/s/OoQ0Dftsq5S3wJQvpa18FQ)
  * https://www.linuxidc.com/Linux/2019-04/157926.htm
* [3 种在Linux命令行查看图像的方法](https://mp.weixin.qq.com/s/ew1Mu4MgBkOk1fWPzm-gow)
* [为何killall有时找不到你的进程？killall是干什么的？](https://mp.weixin.qq.com/s/6roIBVFSJKxgLLFea6OATg)
* [Linux下如何拆分大的日志文件？](https://mp.weixin.qq.com/s/_Yin-MQvYxNDcID6JKUpGQ)
* [几个命令了解ELF文件的“秘密”](https://mp.weixin.qq.com/s/3I7ev0U8EGTHwkSfAOLpHQ)
* [为什么执行自己的程序要在前面加./](https://mp.weixin.qq.com/s/LdHHVsK9UsQ1mNLgA1pdSw)
* [Linux里面常用的查看文本小技巧](https://mp.weixin.qq.com/s/yygNo3CpNHcS7IAjt87Sig)
  * https://blog.csdn.net/Danny_idea/article/details/98670880
* [Linux生产环境上，最常用的一套“Sed“技巧](https://mp.weixin.qq.com/s/i5KPOf3hDQpoVprSaX5FcA)
  * https://github.com/aureliojargas/sokoban.sed
* [sed命令，后台开发必知命令 (qq.com)](https://mp.weixin.qq.com/s/08iB170gzBONLrIyXkNL5Q)
* [常用的 Linux 命令和技巧！](https://mp.weixin.qq.com/s/XtYKDgyPqG0lKaJ1ysaXqw)
  * https://dev.to/mateuszjarzyna/linux-s-commands-and-tricks-i-m-using-in-my-daily-job-as-a-developer-4cle
* [10个高效Linux技巧及Vim命令对比](https://mp.weixin.qq.com/s/Og6qZ_45BD_kLRvsIfYJEQ)

## BASH

* [Linux Bash编程详细语法总结](https://mp.weixin.qq.com/s/L-W4w14oVNkfTvpoBZSPlg)
* [『一网打尽』 Bash 常用命令](https://mp.weixin.qq.com/s/uWDli1O5u73GCx0MpsGcWg)

## VIM

* [vim三种模式下的小技巧 - Linux学习](https://mp.weixin.qq.com/s/XgKK9kyuaBwF8x4caBULYQ)
* [谁说 Vim 不好用？送你一个五彩斑斓的编辑器](https://mp.weixin.qq.com/s/v9rOPfjIblA9hZoEJIhunw)
* [Coding效率提升，15张 Vim 速查表奉上](https://mp.weixin.qq.com/s/4xWoN-vujzGLYBYG0jcbJw)
* [8个技巧让Vim菜鸟变专家](https://mp.weixin.qq.com/s/KrBwSk_UgyZLivcXAMS2xQ)
* [Vim高手，从来不用鼠标](https://mp.weixin.qq.com/s/fj_WqAyuw5liOHc91Dx3NQ)
* [10款好用的Vim插件，你知道几个？](https://mp.weixin.qq.com/s/S4afPpMrBtYV6ml8Qb4NXw)
  * https://opensource.com/article/19/11/vim-plugins
* [30个Vim常用命令](https://mp.weixin.qq.com/s/T6t964XQadO5pJ1FJJrjDQ)

## SHELL

* [学习笔记之Shell脚本的输出重定向 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/4955877.html)
* [学习笔记之Linux Shell脚本教程：30分钟玩转Shell脚本编程 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/5304025.html)
* [编写可靠Linux shell脚本的八个建议](https://mp.weixin.qq.com/s/NNYuIfzEoitXKnHteJwj_A)
* [Linux Shell的18条常用命令整理 - Linux学习](https://mp.weixin.qq.com/s/mNSXpKzMpMcP3V6Rf6Nzcg)
* [10 个实战与面试【常用 Shell 脚本】编写](https://mp.weixin.qq.com/s/xuC_pH1X_GmyK0vVWrBzWQ)
  * https://blog.51cto.com/lizhenliang/1929044
* [Linux Shell 基础 -- 总结几种括号、引号的用法](https://mp.weixin.qq.com/s/nM3P7iVIygrwEEhkjDdH4Q)
  * https://www.cnblogs.com/tongye/p/10646211.html
* [一份Linux shell“圣经”收好](https://mp.weixin.qq.com/s/juul4YWoWCBzNpQWMdP4wg)
  * https://github.com/dylanaraps/pure-bash-bible
* [Linux Shell 时间运算以及时间差计算方法！](https://mp.weixin.qq.com/s/3SrV3wTrcu9O2s1r_MwRHg)
  * https://www.cnblogs.com/chengmo/archive/2010/07/13/1776473.html

## 常用命令

* [Linux 命令大全 | 菜鸟教程](http://www.runoob.com/linux/linux-command-manual.html)
* bash - enter bash command line from virtual environment (e.g. conda)
* bg - Runs jobs in the background
  * https://www.cyberciti.biz/faq/unix-linux-bg-command-examples-usage-syntax/
* cat 文件名 输出文件内容到基本输出（屏幕 or 加>fileName 到另一个文件）
  ```sh
  cat filename.sh
  ```
  * [linux - How does "cat << EOF" work in bash? - Stack Overflow](https://stackoverflow.com/questions/2500436/how-does-cat-eof-work-in-bash/2500451)
* cb 格式化源代码
* cd 进入目录
* chmod //change mode，改变文件的权限
  * https://en.wikipedia.org/wiki/Chmod
  * set test.sh to be executable
    ```sh
    chmod +x test.sh
    ```
  * grant read, write and execute to the User / Group / Others class
    ```sh
    chmod 777 test.sh
    ```
* clear - clear the terminal screen
* cp copy
  * https://www.runoob.com/linux/linux-comm-cp.html
  ```sh
  cp source.py dest.py
  cp -r test newtest

  # result : newtest/test
  ```
* date 当前的时间和日期
* diff 比较文件的差异
  * https://www.runoob.com/linux/linux-comm-diff.html
  ```sh
  diff a.py b.py -y -W 50
  diff -r dir_a dir_b
  ```
* echo 显示指定文本
  * echo $abc 在变量赋值之后，只需在变量前面加一个$去引用.
* find - Linux find命令用来在指定目录下查找文件。
  * http://www.runoob.com/linux/linux-comm-find.html
  ```sh
  find / -name "test*"
  find . -name "*.py"
  ```
  * [系统总结一波Linux下find命令](https://mp.weixin.qq.com/s/e-cRvtQIumo7YgddrdoXBw)
  * [3 Ways to Find a File in Linux - wikiHow](https://www.wikihow.com/Find-a-File-in-Linux)
    * search on the current directory and subdirectories, and ignore the case of query
    ```sh
    find . -iname 'filename'
    ```
* grep - search text
  * http://www.runoob.com/linux/linux-comm-grep.html
  ```sh
  grep -rn 'test' .
  grep -rnw ~/mydir/ -e 'test'
  grep -irnw ~/mydir/test.log -e '.*error' -A3 -B3
  grep -irnw ~/mydir/test?.log -e '.*error.*' | grep -Eiv 'RuntimeError'
  ```
  * [linux - how to grep for “include” and “exclude another term” from file? - Super User](https://superuser.com/questions/1453480/how-to-grep-for-include-and-exclude-another-term-from-file)
  * [How to use wildcards, by The Linux Information Project (LINFO)](http://www.linfo.org/wildcard.html)
* hostname
  * Function: Get or set hostname or DNS domain name
  * Syntax: hostname [-v] [-a] [--alias] [-d] [--domain] [-f] [--fqdn] [-A] [--all-fqdns] [-i] [--ip-address] [-I] [--all-ip-addresses] [--long] [-s] [--short] [-y] [--yp] [--nis]
* htop -u my_username
  * check what process is running by a user
  * https://en.wikipedia.org/wiki/Htop
  * https://www.cyberciti.biz/faq/linux-list-processes-by-user-names-euid-and-ruid/
* ldd
  * [ldd (Unix) - Wikipedia](https://en.wikipedia.org/wiki/Ldd_(Unix))
  * ldd (List Dynamic Dependencies) is a *nix utility that prints the shared libraries required by each program or shared library specified on the command line.[1]
  ```sh
  $ ldd /usr/bin/mp3blaster
  ```
* less
  * https://en.wikipedia.org/wiki/Less_(Unix)
  * less is a terminal pagerprogram on Unix, Windows, and Unix-like systems used to view (but not change) the contents of a text file one screen at a time. It is similar to more, but has the extended capability of allowing both forward and backward navigation through the file. Unlike most Unix text editors/viewers, less does not need to read the entire file before starting, resulting in faster load times with large files.
* [lint](http://baike.baidu.com/view/1617406.htm) 语法检查程序
* ln
  * http://www.runoob.com/linux/linux-comm-ln.html
  * creating a symbolic link named my_link.txt to a file named my_file.txt
  ```sh
  ln -s my_file.txt my_link.txt
  ```
* locate - find files
  * [locate (Unix) - Wikipedia](https://en.wikipedia.org/wiki/Locate_(Unix))
  ```sh
  locate poetry
  ```
* ls dir
  * verify the symlink
  ```sh
  ls -l my_link.txt
  ```
* man help
* mkdir 创建目录
  * [unix - mkdir's "-p" option - Stack Overflow](https://stackoverflow.com/questions/22737933/mkdirs-p-option)
    * -p, --parents
    * no error if existing, make parent directories as needed
* more 显示文件
  ```sh
  more type
  ```
* mv 改文件名 /移动文件
  * [Linux and Unix mv command tutorial with examples | George Ornbo](https://shapeshed.com/unix-mv/#how-to-move-a-directory)
* passwd 更改密码
  * https://www.runoob.com/linux/linux-comm-passwd.html
* ps 查看当前进程状况
* pushd and popd
  * [pushd and popd - Wikipedia](https://en.wikipedia.org/wiki/Pushd_and_popd)
    * In computing, pushd and popd are commands used to work with the command line directory stack.
  * [Linux pushd and popd Command Tutorial for Beginners (3 Examples)](https://www.howtoforge.com/linux-pushd-popd-command/#q-how-to-check-directory-stack)
* pwd 显示目录路径命令
* rm 删除文件
  * rm -rf 删除非空文件夹
* rmdir 删除目录
* sudo
  * https://www.howtogeek.com/447906/how-to-control-sudo-access-on-linux/#:~:text=%20How%20to%20Control%20sudo,file.%20It%20is...%20More
  * The sudo command lets you run commands on Linux as though you were someone else, such as root. sudo also lets you control who can access root's capabilities, with granularity. Give users full access or let them use a small subset of commands.
  * Originally, it was called “superuser do”, because you could do things as the superuser. Its scope has been widened now, and you can use sudo to execute a command as though you were any user. It has been renamed to reflect that new functionality. It is now called “substitute user do.”
  * To use sudo to run a command as another user, we need to use the -u (user) option. Here, we’re going run the whoami command as the user mary. If you use the sudo command without the -u option, you’ll run the command as root.
    ```sh
    $ sudo -u mary whoami
    ```
  * You can use the sudo command to log in as another user without knowing their password. You’ll be prompted for your own password. We need to use the -i (login) option.
    ```sh
    $ sudo -i -u mary
    ```
* top
  * [10分钟教会你看懂top](https://mp.weixin.qq.com/s/8bBj1utjbF0-RIlWTF3KWQ)
    * [10分钟教会你看懂top](https://juejin.cn/post/6844903919588491278)
    * Load Average
    * top命令一行一行看
    * 其他命令
* who 你的用户名和终端类型
* 定义变量 name=abc? (bash/pdksh) || set name = abc (tcsh)

## FAQ

* What's localhost ?
  * [localhost - Wikipedia](https://en.wikipedia.org/wiki/Localhost)
  * The name localhost normally resolves to the IPv4 loopback address 127.0.0.1, and to the IPv6 loopback address ::1.
* How to extract .tar.gz Files ?
  ```sh
  $ tar xvzf file.tar.gz
  $ tar xvzf file.tar.gz -C /path/to/somedirectory
  ```
  * [How To Extract .tar.gz Files using Linux Command Line - Interserver Tips](https://www.interserver.net/tips/kb/extract-tar-gz-files-using-linux-command-line/)
* How to fix Address already in use ?
  * [Bind failed: Address already in use - Stack Overflow](https://stackoverflow.com/questions/15198834/bind-failed-address-already-in-use)
  * Use netstat -tulpn to display the processes
  * Use netstat -pnlt | grep ':1' to find which process use the port 1
    * [networking - how to use netstat on a specific port in Linux - Super User](https://superuser.com/questions/602049/how-to-use-netstat-on-a-specific-port-in-linux)
  * kill -9 <pid> This will terminate the process
* How to view the contents of tar.gz file without extracting it ?
  ```sh
  $ tar -tf filename.tar.gz
  ```
  * [How can I view the contents of tar.gz file without extracting from the command-line? - Ask Ubuntu](https://askubuntu.com/questions/392885/how-can-i-view-the-contents-of-tar-gz-file-without-extracting-from-the-command-l)
* How to hide and view hidden files / directories ?
  ```sh
  $ mv file .file
  $ ls -al
  $ ll -a
  ```
  * [An Easy Way to Hide Files and Directories in Linux](https://www.tecmint.com/hide-files-and-directories-in-linux/)
    * To hide a file or directory from the terminal, simply append a dot . at the start of its name
* How to view system environment variables ?
  ```sh
  $ env
  ```
* How to add and view path environment variable ?
  ```sh
  $ export PATH=~/folder/:${PATH}
  $ echo $PATH
  ```
* How to add and use alias ?
  ```sh
  $ alias test=~/bin/test
  $ test
  ```
* How to find and kill process ?
  ```sh
  $ ps ax | grep python
  11111 pts/9 Tl 0:08 python ...
  $ kill -9 11111
  ```
  * [Kill Process in Linux or Terminate a Process in UNIX / Linux Systems - nixCraft](https://www.cyberciti.biz/faq/kill-process-in-linux-or-terminate-a-process-in-unix-or-linux-systems/)
* How to kill a CLOSE_WAIT socket connection ?
  * [linux - How do I remove a CLOSE_WAIT socket connection - Stack Overflow](https://stackoverflow.com/questions/15912370/how-do-i-remove-a-close-wait-socket-connection)
  ```sh
  $ netstat -an --tcp --program
  Active Internet connections (servers and established)
  Proto Recv-Q Send-Q Local Address Foreign Address State PID/Program name
  tcp 0 0 127.0.0.1:25 0.0.0.0:* LISTEN -
  tcp 11 0 127.0.0.1:15540 127.0.0.1:51974 CLOSE_WAIT -

  $ ss --tcp state CLOSE-WAIT --kill
  Recv-Q Send-Q Local Address:Port Peer Address:Port
  ```
* How to reverse-i-search back to search commands in history ?
  * Ctrl + r
* How to check memory usage ?
  ```sh
  $ free -m (display in MB)
  $ top
  $ htop
  ```
  * [5 commands to check memory usage on Linux – BinaryTides](https://www.binarytides.com/linux-command-check-memory-usage/)
* How to check disk usage ?
  * df命令用于显示目前在Linux系统上的文件系统的磁盘使用情况统计。
    * https://www.runoob.com/linux/linux-comm-df.html
    ```sh
    df -h
    df -h /dir
    ``` 
  * du 查看磁盘空间状况
    * https://www.runoob.com/linux/linux-comm-du.html
* What's .bashrc ?
  * .bashrc is a shell script that Bash runs whenever it is started interactively. It initializes an interactive shell session.
    * [bash - What is the purpose of .bashrc and how does it work? - Unix & Linux Stack Exchange](https://unix.stackexchange.com/questions/129143/what-is-the-purpose-of-bashrc-and-how-does-it-work)
  ```sh
  $ cat .bashrc
  ```

# 学习笔记之Linux

* [shell（计算机壳层）_百度百科](http://baike.baidu.com/subview/849/15831672.htm)
* [Shell (computing) - Wikipedia, the free encyclopedia](http://en.wikipedia.org/wiki/Shell_(computing))
* [iSeries QSHELL - Wikipedia](http://en.wikipedia.org/wiki/ISeries_QSHELL)
  * According to IBM, QSHELL is a “UNIX-like” interface built over OS/400. The commands you issue point to programs in a “QSHELL” library. To use QSHELL, key STRQSH or QSH on an iSeries command line.
  * PASE is a “real” UNIX—it is actually AIX. It looks similar to QSHELL, but doesn’t have some of the limitations built into QSHELL. To use PASE, CALL QP2TERM.
* [AIX_百度百科 ](http://baike.baidu.com/view/349664.htm)
  * AIX（Advanced Interactive eXecutive）是IBM基于AT&T Unix System V开发的一套类UNIX操作系统，运行在IBM专有的Power系列芯片设计的小型机硬件系统之上。
* [CentOS - Wikipedia](https://en.wikipedia.org/wiki/CentOS)
  * CentOS (/ˈsɛntɒs/, from Community Enterprise Operating System; also known as CentOS Linux)[5][6] is a Linux distribution that provides a free and open-source community-supported computing platform, functionally compatible with its upstream source, Red Hat Enterprise Linux (RHEL).[7][8] In January 2014, CentOS announced the official joining with Red Hat while staying independent from RHEL,[9] under a new CentOS governing board.[10][11]
  * The first CentOS release in May 2004, numbered as CentOS version 2, was forked from RHEL version 2.1AS.[1] Since version 8, CentOS officially supports the x86-64, ARM64, and POWER8 architectures, and releases up to version 6 also supported the IA-32 architecture. As of December 2015, AltArch releases of CentOS 7 are available for the IA-32 architecture, Power ISA, and for the ARMv7hl and AArch64 variants of the ARM architecture.[12][13] CentOS 8 was released on 24 September 2019.[14]
  * In December 2020, Red Hat unilaterally terminated CentOS development.[15][16][17][18] In response, CentOS founder Gregory Kurtzer created the Rocky Linux project as a successor to the original mission of CentOS.[19] In March 2021, Cloud Linux (makers of CloudLinux OS) released a new RHEL derivative called AlmaLinux.[20]
  * While the distribution was discontinued at the end of 2021, development of CentOS Stream, its midstream variant, continues.[21]
  * [How to check CentOS version - CentOS configuration and tutorials](https://linuxconfig.org/how-to-check-centos-version#:~:text=The%20simplest%20way%20to%20check,to%20troubleshoot%20your%20CentOS%20system.)
    * `cat /etc/centos-release`
* [面试总结之Linux/Shell - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/5559113.html)
* [学习笔记之Linux开发(C语言) - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/5122821.html)
* [Linux 教程 | 菜鸟教程](https://www.runoob.com/linux/linux-tutorial.html)

## RESROUCES

* [Linux桌面进化史](https://mp.weixin.qq.com/s/Pyyb_hHZJOlylplrmG8uWg)
  * https://opensource.com/article/19/8/how-linux-desktop-grown
* [命令行的艺术](https://mp.weixin.qq.com/s/eiTABcqQ3QwCiCpeEHBszg)
  * https://github.com/jlevy/the-art-of-command-line/blob/master/README-zh.md
* [Unix 激荡 50 年：驱动 Android、iOS 的操作系统是如何从失败开始的?](https://mp.weixin.qq.com/s/9QSsGC8UCtShexD1uQ1Tzg)
  * https://arstechnica.com/gadgets/2019/08/unix-at-50-it-starts-with-a-mainframe-a-gator-and-three-dedicated-researchers/
* [10个不得不知的Linux常识](https://mp.weixin.qq.com/s/J_74--fpDDpZIrKP2dq5iw)
  * https://blog.51cto.com/7424593/1744358
* [你应该了解的Linux知识](https://mp.weixin.qq.com/s/OWdfRIGbVYOBHhNfbrVs4Q)
* [Ubuntu 的十年回顾](https://mp.weixin.qq.com/s/QTwH8e60wK7DmseiUZL7GQ)
  * https://www.omgubuntu.co.uk/2019/12/ubuntu-defining-moments-2010s
* [Understanding Linux File Permissions | Linuxize](https://linuxize.com/post/understanding-linux-file-permissions/)
  * In Linux, file permissions, attributes, and ownership control the access level that the system processes and users have to files. This ensures that only authorized users and processes can access specific files and directories.
  * In Linux, access to the files is restricted using file permissions, attributes, and ownership. To change the file’s permissions use the chmod command.
* [Linux 性能分析工具汇总](https://mp.weixin.qq.com/s/QFbVwYWsIB0Ayw_-kJICYQ)
  * https://rdc.hundsun.com/portal/article/731.html?ref=myread
  * 性能分析工具
    * ![image](https://user-images.githubusercontent.com/34557994/194443595-66880de8-5128-4806-83d9-d557b38f06b6.png)
    * vmstat--虚拟内存统计
      * vmstat（VirtualMeomoryStatistics，虚拟内存统计）是 Linux 中监控内存的常用工具,可对操作系统的虚拟内存、进程、CPU 等的整体情况进行监视。vmstat 的常规用法：vmstat interval times 即每隔 interval 秒采样一次，共采样 times 次，如果省略 times，则一直采集数据，直到用户手动停止为止。
    * iostat--用于报告中央处理器统计信息
      * iostat 用于报告中央处理器（CPU）统计信息和整个系统、适配器、tty 设备、磁盘和 CD-ROM 的输入/输出统计信息，默认显示了与 vmstat 相同的 cpu 使用信息，使用以下命令显示扩展的设备统计
    * dstat--系统监控工具
      * dstat 显示了 cpu 使用情况，磁盘 io 情况，网络发包情况和换页情况，输出是彩色的，可读性较强，相对于 vmstat 和iostat 的输入更加详细且较为直观。在使用时，直接输入命令即可，当然也可以使用特定参数。
    * iotop--LINUX进程实时监控工具
      * iotop命令是专门显示硬盘IO的命令，界面风格类似top命令，可以显示IO负载具体是由哪个进程产生的。是一个用来监视磁盘I/O使用状况的top类工具，具有与top相似的UI，其中包括PID、用户、I/O、进程等相关信息。
    * pidstat--监控系统资源情况
      * pidstat 主要用于监控全部或指定进程占用系统资源的情况,如 CPU,内存、设备 IO、任务切换、线程等。
    * top
      * top 命令的汇总区域显示了五个方面的系统性能信息：
        * 负载：时间，登陆用户数，系统平均负载；
        * 进程：运行，睡眠，停止，僵尸；
        * cpu:用户态，核心态，NICE,空闲，等待IO,中断等；
        * 内存：总量，已用，空闲（系统角度），缓冲，缓存；
        * 交换分区：总量，已用，空闲
        * 任务区域默认显示：进程 ID，有效用户，进程优先级，NICE 值，进程使用的虚拟内存，物理内存和共享内存，进程状态，CPU 占用率，内存占用率，累计 CPU 时间，进程命令行信息。
    * htop
      * htop 是 Linux 系统中的一个互动的进程查看器,一个文本模式的应用程序(在控制台或者X终端中),需要 ncurses。
    * mpstat
      * mpstat 是 Multiprocessor Statistics的缩写，是实时系统监控工具。其报告CPU的一些统计信息，这些信息存放在 /proc/stat 文件中。在多 CPUs 系统里，其不但能查看所有 CPU 的平均状况信息，而且能够查看特定 CPU 的信息。
    * netstat
      * netstat 用于显示与 IP、TCP、UDP和 ICMP 协议相关的统计数据，一般用于检验本机各端口的网络连接情况。
    * ps--显示当前进程的状态
      * ps 参数太多，具体使用方法可以参考 man ps
    * strace
      * 跟踪程序执行过程中产生的系统调用及接收到的信号，帮助分析程序或命令执行中遇到的异常情况。
    * uptime
      * 能够打印系统总共运行了多长时间和系统的平均负载，uptime 命令最后输出的三个数字的含义分别是 1分钟，5分钟，15分钟内系统的平均负荷。
    * lsof
      * lsof（list open files）是一个列出当前系统打开文件的工具。通过 lsof 工具能够查看这个列表对系统检测及排错
    * perf
      * perf 是 Linux kernel 自带的系统性能优化工具。优势在于与 Linux Kernel 的紧密结合，它可以最先应用到加入 Kernel 的new feature，用于查看热点函数，查看 cashe miss 的比率，从而帮助开发者来优化程序性能。
  * 常用的性能测试工具
    * Linux observability tools | Linux 性能观测工具
      * ![image](https://user-images.githubusercontent.com/34557994/194444371-66fc61a8-0c42-4c99-a9ef-57e289ce7e65.png)
      * 首先学习的Basic Tool有如下：uptime、top(htop)、mpstat、isstat、vmstat、free、ping、nicstat、dstat。
      * 高级的命令如下：sar、netstat、pidstat、strace、tcpdump、blktrace、iotop、slabtop、sysctl、/proc。
    * Linux benchmarking tools | Linux 性能测评工具
      * ![image](https://user-images.githubusercontent.com/34557994/194444505-fa538ec3-1d27-498a-95a7-0b3f77214ac8.png)
      * 是一款性能测评工具，对于不同模块的性能测试可以使用相应的工具，想要深入了解，可以参考最下文的附件文档。
    * Linux tuning tools | Linux 性能调优工具
      * ![image](https://user-images.githubusercontent.com/34557994/194444545-34324076-ebc6-4fde-a9a3-4eb7825e800d.png)
      * 是一款性能调优工具，主要是从linux内核源码层进行的调优，想要深入了解，可以参考下文附件文档。
    * Linux observability sar | linux性能观测工具
      * ![image](https://user-images.githubusercontent.com/34557994/194444597-071b53ec-ed55-4f49-9529-15d25a6a2b52.png)
      * sar（System Activity Reporter系统活动情况报告）是目前LINUX上最为全面的系统性能分析工具之一，可以从多方面对系统的活动进行报告，包括：文件的读写情况、系统调用的使用情况、磁盘I/O、CPU效率、内存使用状况、进程活动及IPC 有关的活动等方面。

### Hardware

#### CPU

* [Single-core - Wikipedia](https://en.wikipedia.org/wiki/Single-core#:~:text=A%20single%2Dcore%20processor%20is,than%20a%20multi%2Dcore%20system.)
  * A single-core processor is a microprocessor with a single core on its die.[1] It performs the fetch-decode-execute cycle once per clock-cycle, as it only runs on one thread. A computer using a single core CPU is generally slower than a multi-core system.
  * Single core processors used to be widespread in desktop computers, but as applications demanded more processing power, the slower speed of single core systems became a detriment to performance. Windows supported single-core processors up until the release of Windows 11, where a dual-core processor is required. [2]
  * Single core processors are still in use in some niche circumstances. Some older legacy systems like those running antiquated operating systems (e.g. Windows 98) cannot gain any benefit from multi-core processors. Single core processors are also used in hobbyist computers like the Raspberry Pi and Single-board microcontrollers. The production of single-core desktop processors ended in 2013 with the Celeron G470. [3]
* [Multi-core processor - Wikipedia](https://en.wikipedia.org/wiki/Multi-core_processor)
  * A multi-core processor is a microprocessor on a single integrated circuit with two or more separate processing units, called cores, each of which reads and executes program instructions.[1] The instructions are ordinary CPU instructions (such as add, move data, and branch) but the single processor can run instructions on separate cores at the same time, increasing overall speed for programs that support multithreading or other parallel computing techniques.[2] Manufacturers typically integrate the cores onto a single integrated circuit die (known as a chip multiprocessor or CMP) or onto multiple dies in a single chip package. The microprocessors currently used in almost all personal computers are multi-core.
  * A multi-core processor implements multiprocessing in a single physical package. Designers may couple cores in a multi-core device tightly or loosely. For example, cores may or may not share caches, and they may implement message passing or shared-memory inter-core communication methods. Common network topologies used to interconnect cores include bus, ring, two-dimensional mesh, and crossbar. Homogeneous multi-core systems include only identical cores; heterogeneous multi-core systems have cores that are not identical (e.g. big.LITTLE have heterogeneous cores that share the same instruction set, while AMD Accelerated Processing Units have cores that do not share the same instruction set). Just as with single-processor systems, cores in multi-core systems may implement architectures such as VLIW, superscalar, vector, or multithreading.
  * Multi-core processors are widely used across many application domains, including general-purpose, embedded, network, digital signal processing (DSP), and graphics (GPU). Core count goes up to even dozens, and for specialized chips over 10,000,[3] and in supercomputers (i.e. clusters of chips) the count can go over 10 million (and in one case up to 20 million processing elements total in addition to host processors).[4]
  * The improvement in performance gained by the use of a multi-core processor depends very much on the software algorithms used and their implementation. In particular, possible gains are limited by the fraction of the software that can run in parallel simultaneously on multiple cores; this effect is described by Amdahl's law. In the best case, so-called embarrassingly parallel problems may realize speedup factors near the number of cores, or even more if the problem is split up enough to fit within each core's cache(s), avoiding use of much slower main-system memory. Most applications, however, are not accelerated as much unless programmers invest effort in refactoring.[5]
  * The parallelization of software is a significant ongoing topic of research. Cointegration of multiprocessor applications provides flexibility in network architecture design. Adaptability within parallel models is an additional feature of systems utilizing these protocols.[6]
* [What Is a CPU Core? A Basic Definition | Tom's Hardware](https://www.tomshardware.com/news/cpu-core-definition,37658.html)
  * A CPU core is a CPU’s (opens in new tab)processor. In the old days, every processor had just one core that could focus on one task at a time. Today, CPUs(opens in new tab) have been two and 18 cores, each of which can work on a different task. As you can see in our CPU Benchmarks Hierarchy, that can have a huge impact on performance. 
  * A core can work on one task, while another core works a different task, so the more cores a CPU has, the more efficient it is(opens in new tab). Many processors, especially those in laptops, have two cores, but some laptop CPUs (known as mobile CPUs), such as Intel’s 8th Generation processors, have four. You should shoot for at least four cores in your machine if you can afford it.
  * Most processors can use a process called simultaneous multithreading(opens in new tab) or, if it’s an Intel processor, Hyper-threading(opens in new tab) (the two terms mean the same thing) to split a core into virtual cores, which are called threads(opens in new tab). For example, AMD CPUs (opens in new tab)with four cores use simultaneous multithreading to provide eight threads, and most Intel CPUs with two cores use Hyper-threading to provide four threads.
  * Some apps take better advantage of multiple threads than others. Lightly-threaded apps, like games, don't benefit from a lot of cores, while most video editing and animation programs can run much faster with extra threads.
  * Note: Intel also uses the term “Core” to brand some of its CPUs (ex: Intel Core i7-7500U processor). Of course, Intel CPUs (and all CPUs) that do not have the Core branding use cores as well. And the numbers you see in an Intel Core (or otherwise) processor is not a direct correlation to how many cores the CPU has. For example, the Intel Core i7-7500U processor does not have seven cores.
* [CPU Speed: What Is CPU Clock Speed? | Intel](https://www.intel.com/content/www/us/en/gaming/resources/cpu-clock-speed.html)
  * In general, a higher clock speed means a faster CPU. However, many other factors come into play.
  * Your CPU processes many instructions (low-level calculations like arithmetic) from different programs every second. The clock speed measures the number of cycles your CPU executes per second, measured in GHz (gigahertz).
  * A “cycle” is technically a pulse synchronized by an internal oscillator, but for our purposes, they’re a basic unit that helps understand a CPU’s speed. During each cycle, billions of transistors within the processor open and close.
  * A CPU with a clock speed of 3.2 GHz executes 3.2 billion cycles per second. (Older CPUs had speeds measured in megahertz, or millions of cycles per second.)
  * Sometimes, multiple instructions are completed in a single clock cycle; in other cases, one instruction might be handled over multiple clock cycles. Since different CPU designs handle instructions differently, it’s best to compare clock speeds within the same CPU brand and generation.
  * For example, a CPU with a higher clock speed from five years ago might be outperformed by a new CPU with a lower clock speed, as the newer architecture deals with instructions more efficiently. An X-series Intel® processor might outperform a K-series processor with a higher clock speed, because it splits tasks between more cores and features a larger CPU cache. But within the same generation of CPUs, a processor with a higher clock speed will generally outperform a processor with a lower clock speed across many applications. This is why it’s important to compare processors from the same brand and generation.
* [What Is Intel® Turbo Boost Technology? - Intel](https://www.intel.com/content/www/us/en/gaming/resources/turbo-boost.html)
  * How Does Intel® Turbo Boost Technology Work?
    * CPUs don’t always need to run at their maximum frequency. Some programs are more dependent on memory to run smoothly, while others are CPU-intensive. Intel® Turbo Boost Technology is an energy-efficient solution to this imbalance: it lets the CPU run at its base clock speed when handling light workloads, then jump to a higher clock speed for heavy workloads.
    * Running at a lower clock rate (the number of cycles executed by the processor every second) allows the processor to use less power, which can reduce heat and positively impact battery life in laptops. But when more speed is needed, Intel® Turbo Boost Technology dynamically increases the clock rate to compensate. This is sometimes called “algorithmic overclocking”.
    * Intel® Turbo Boost Technology can potentially increase CPU speeds up to the Max Turbo Frequency while staying within safe temperature and power limits. This can increase performance in both single-threaded and multithreaded applications (programs that utilize several processor cores).
    * If you’re wondering how to enable Turbo Boost, don’t worry — it’s enabled by default. You don’t need to download or configure anything.
  * What Is Max Turbo Frequency?
    * When handling light workloads, the CPU runs at the base frequency listed in its specifications. (Or lower, when the energy-saving Intel SpeedStep® technology scales CPU speeds.) When handling hardware threads marked for high performance, Intel® Turbo Boost Technology increases the clock speed up to the Max Turbo Frequency.
    * For example, the Intel® Core™ i9-9900K processor has a base frequency of 3.60 GHz, and a Max Turbo frequency of 5.00 GHz. Note that depending on its situation, a given CPU may not always reach its Max Turbo Frequency. The dynamic increase in speed changes depending on the workload and the thermal headroom available.
    * When comparing CPU clock speeds, the Max Turbo Frequency is typically the key number to keep in mind. It reflects the processor’s peak performance before overclocking.1 Along with core count and premium features, it’s one of the key considerations when CPU shopping.
* [What are Threads in Computer Processor or CPU? - GeeksforGeeks](https://www.geeksforgeeks.org/what-are-threads-in-computer-processor-or-cpu/)
  * Threads are the virtual components or codes, which divides the physical core of a CPU into virtual multiple cores. A single CPU core can have up-to 2 threads per core.
  * For example, if a CPU is dual core (i.e., 2 cores) it will have 4 threads. And if a CPU is Octal core (i.e., 8 core) it will have 16 threads and vice-versa.
* [虚拟内存 & I/O & 零拷贝](https://mp.weixin.qq.com/s/DMWfSxrbu4kgCh4JCQ4XIQ)
* [CPU 是如何与内存交互的](https://mp.weixin.qq.com/s/SaaHKPnNUSvDkmwKtip3HA)


## LINUX COMMANDS

* [Unix/Linux Command Reference](https://github.com/haoran119/linux/blob/main/Unix_command_cheatsheet.pdf)
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
* [如何用 Linux 技巧大大提高工作效率？ - CSDN](https://mp.weixin.qq.com/s/wZ7tqB8EDEduQE-2gtUdFA)
* [Linux最常用命令](https://mp.weixin.qq.com/s/rpNxF0iD8fGZd8r-lnIdUA)
  * https://blog.csdn.net/xulong_08/article/details/81463054
* [Linux 实用指令大全](https://mp.weixin.qq.com/s/VTCoiglKNQKHEKQ_M8drCg)
  * https://blog.csdn.net/qq_42322103/article/details/96307643
* [Linux里面常用的查看文本小技巧](https://mp.weixin.qq.com/s/yygNo3CpNHcS7IAjt87Sig)
  * https://blog.csdn.net/Danny_idea/article/details/98670880
* [Linux生产环境上，最常用的一套“Sed“技巧](https://mp.weixin.qq.com/s/i5KPOf3hDQpoVprSaX5FcA)
  * https://github.com/aureliojargas/sokoban.sed
* [常用的 Linux 命令和技巧！](https://mp.weixin.qq.com/s/XtYKDgyPqG0lKaJ1ysaXqw)
  * https://dev.to/mateuszjarzyna/linux-s-commands-and-tricks-i-m-using-in-my-daily-job-as-a-developer-4cle
* [10 Commands to Collect System and Hardware Info in Linux](https://www.tecmint.com/commands-to-collect-system-and-hardware-information-in-linux/)
  * 1. How to View Linux System Information
    * To know only the system name, you can use the `uname` command without any switch that will print system information or the `uname -s` command will print the kernel name of your system.
  * 2. How to View Linux System Hardware Information
    * Here you can use the `lshw` tool to gather vast information about your hardware components such as cpu, disks, memory, usb controllers, etc.
  * 3. How to View Linux CPU Information
    * To view information about your CPU, use the `lscpu` command as it shows information about your CPU architecture such as a number of CPUs, cores, CPU family model, CPU caches, threads, etc from sysfs and /proc/cpuinfo.
  * 4. How to Collect Linux Block Device Information
    * Block devices are storage devices such as hard disks, flash drives, etc. `lsblk` command is used to report information about block devices as follows.
  * 5. How to Print USB Controllers Information
    * The `lsusb` command is used to report information about USB controllers and all the devices that are connected to them.
  * 6. How to Print PCI Devices Information
    * PCI devices may include usb ports, graphics cards, network adapters, etc. The `lspci` tool is used to generate information concerning all PCI controllers on your system plus the devices that are connected to them.
  * 7. How to Print SCSI Devices Information
    * To view all your scsi/sata devices, use the `lsscsi` command as follows. If you do not have the lsscsi tool installed, run the following command to install it.
  * 8. How to Print Information about SATA Devices
    * You can find some information about sata devices on your system as follows using the `hdparm` utility. In the example below, I used the block device /dev/sda1 which is the hard disk on my system.
  * 9. How to Check Linux File System Information
    * To gather information about file system partitions, you can use the `fdisk` command. Although the main functionality of the fdisk command is to modify file system partitions, it can also be used to view information about the different partitions on your file system.
  * 10. How to Check Linux Hardware Components Info
    * You can also use the `dmidecode` utility to extract hardware information by reading data from the DMI tables.
  * There are many other ways you can use to obtain information about your system hardware components. Most of these commands use files in the /proc directory to extract system information.

### COMMANDS

* [Linux manual pages: alphabetic list of all pages](https://man7.org/linux/man-pages/dir_all_alphabetic.html)
* [Linux 命令大全 | 菜鸟教程](http://www.runoob.com/linux/linux-command-manual.html)
* [linux yum 命令 | 菜鸟教程](https://www.runoob.com/linux/linux-yum.html)
  * yum（ Yellow dog Updater, Modified）是一个在 Fedora 和 RedHat 以及 SUSE 中的 Shell 前端软件包管理器。
  * 基于 RPM 包管理，能够从指定的服务器自动下载 RPM 包并且安装，可以自动处理依赖性关系，并且一次安装所有依赖的软件包，无须繁琐地一次次下载、安装。
  * yum 提供了查找、安装、删除某一个、一组甚至全部软件包的命令，而且命令简洁而又好记。
  * `yum [options] [command] [package ...]`
    * options：可选，选项包括-h（帮助），-y（当安装过程提示选择全部为 "yes"），-q（不显示安装的过程）等等。
    * command：要进行的操作。
    * package：安装的包名。
* [Linux apt 命令 | 菜鸟教程](https://www.runoob.com/linux/linux-comm-apt.html)
  * apt（Advanced Packaging Tool）是一个在 Debian 和 Ubuntu 中的 Shell 前端软件包管理器。
  * apt 命令提供了查找、安装、升级、删除某一个、一组甚至全部软件包的命令，而且命令简洁而又好记。
  * apt 命令执行需要超级管理员权限(root)。
  * `apt [options] [command] [package ...]`
    * options：可选，选项包括 -h（帮助），-y（当安装过程提示选择全部为"yes"），-q（不显示安装的过程）等等。
    * command：要进行的操作。
    * package：安装的包名。
* bash - enter bash command line from virtual environment (e.g. conda)
* [bg - Runs jobs in the background](https://www.cyberciti.biz/faq/unix-linux-bg-command-examples-usage-syntax/)
* cat 文件名 输出文件内容到基本输出（屏幕 or 加>fileName 到另一个文件）
    ```sh
    cat filename.sh
    ```
    * [linux - How does "cat << EOF" work in bash? - Stack Overflow](https://stackoverflow.com/questions/2500436/how-does-cat-eof-work-in-bash/2500451)
    * [Cat command in Linux with examples - GeeksforGeeks](https://www.geeksforgeeks.org/cat-command-in-linux-with-examples/)
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
* [cp copy](https://www.runoob.com/linux/linux-comm-cp.html)
```sh
cp source.py dest.py
cp -r test newtest

# result : newtest/test
```
* [cron](https://man7.org/linux/man-pages/man8/cron.8.html)
  * crond - daemon to execute scheduled commands
* [crontab - maintains crontab files for individual users](https://man7.org/linux/man-pages/man1/crontab.1.html)
  * [A Beginners Guide To Cron Jobs - OSTechNix](https://ostechnix.com/a-beginners-guide-to-cron-jobs/)
  * [Crontab manpage - crontab.5 - Crontab.guru](https://crontab.guru/crontab.5.html)
  * [Crontab.guru - The cron schedule expression editor](https://crontab.guru/#50_14_*_*_1-5)
```sh
crontab -l
# 50 14 * * 1-5 ~/test.sh >> test.log
crontab -e
```
* [date 命令可以用来显示或设定系统的日期与时间](https://www.runoob.com/linux/linux-comm-date.html)
```sh
# date
Tue May 24 09:29:43 CST 2022
```
* [df](https://www.runoob.com/linux/linux-comm-df.html)
  * Linux df（英文全拼：disk free） 命令用于显示目前在 Linux 系统上的文件系统磁盘使用情况统计。
  * `df [选项]... [FILE]...`
  * How to check disk usage ?
    ```sh
    df -h
    df -h /dir
    ``` 
* [du](https://www.runoob.com/linux/linux-comm-du.html)
  * Linux du （英文全拼：disk usage）命令用于显示目录或文件的大小。
  * du 会显示指定的目录或文件所占用的磁盘空间。
  * `du [-abcDhHklmsSx][-L <符号连接>][-X <文件>][--block-size][--exclude=<目录或文件>][--max-depth=<目录层数>][--help][--version][目录或文件]`
* [diff 比较文件的差异](https://www.runoob.com/linux/linux-comm-diff.html)
  * diff [-abBcdefHilnNpPqrstTuvwy][-<行数>][-C <行数>][-D <巨集名称>][-I <字符或字符串>][-S <文件>][-W <宽度>][-x <文件或目录>][-X <文件>][--help][--left-column][--suppress-common-line][文件或目录1][文件或目录2]
  * [diff command in Linux with examples - GeeksforGeeks](https://www.geeksforgeeks.org/diff-command-linux-examples/?ref=leftbar-rightbar)
```sh
diff a.py b.py -y -W 200
diff -r dir_a dir_b
diff -r dir_a dir_b -x .git*
diff -r dir_a dir_b -x .git* -c
diff -r dir_a dir_b -x .git* -u
diff -r dir_a dir_b -x .git* -y -W 200 --suppress-common-lines
diff -r dir_a dir_b -x .git* -q
```
* [echo 显示指定文本](https://man7.org/linux/man-pages/man1/echo.1.html)
  * `echo $abc` 在变量赋值之后，只需在变量前面加一个$去引用.
* [eval](https://www.runoob.com/linux/linux-comm-eval.html)
  * Linux eval命令用于重新运算求出参数的内容。
  * eval可读取一连串的参数，然后再依参数本身的特性来执行。
  * [bash - What's the difference between eval and exec? - Unix & Linux Stack Exchange](https://unix.stackexchange.com/questions/296838/whats-the-difference-between-eval-and-exec)
  * [linux - How can I store a command in a variable in a shell script? - Stack Overflow](https://stackoverflow.com/questions/5615717/how-can-i-store-a-command-in-a-variable-in-a-shell-script)
```sh
x="ls | wc"
eval "$x"
y=$(eval "$x")
echo "$y"
```
* [exec](https://www.geeksforgeeks.org/exec-command-in-linux-with-examples/)
  * exec command in Linux is used to execute a command from the bash itself. This command does not create a new process it just replaces the bash with the command to be executed. If the exec command is successful, it does not return to the calling process.
  * Syntax:
    * exec [-cl] [-a name] [command [arguments]] [redirection ...]
  * Options:
    * c: It is used to execute the command with empty environment.
    * a name: Used to pass a name as the zeroth argument of the command.
    * l: Used to pass dash as the zeroth argument of the command.
* [export](https://www.runoob.com/linux/linux-comm-export.html)
  * `export [-fnp][变量名称]=[变量设置值]`
  * -f 　代表[变量名称]中为函数名称。
  * -n 　删除指定的变量。变量实际上并未删除，只是不会输出到后续指令的执行环境中。
  * -p 　列出所有的shell赋予程序的环境变量。
  * How to add and view path environment variable ?
```sh
$ export PATH=~/folder/:${PATH}
$ echo $PATH
```
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
* [ls dir](https://www.runoob.com/linux/linux-comm-ls.html)
  * verify the symlink
    * `ls -l my_link.txt`
  * 列出目前工作目录下所有名称是 s 开头的文件，越新的排越后面
    * `ls -ltr s*`
* [lsof - list open files](https://man7.org/linux/man-pages/man8/lsof.8.html)
  * show deleted file in open
    * `lsof | grep -i deleted`
  * [Script to kill deleted files lsof](http://www.techbluff.com/linux/script-to-kill-deleted-files-lsof/)
    * `lsof +L1 | grep 'deleted' | awk '{print $2}' | xargs kill -9`
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
* [ps 查看当前进程状况](https://man7.org/linux/man-pages/man1/ps.1.html)
* How to find and kill process ?
  ```sh
  $ ps ax | grep python
  11111 pts/9 Tl 0:08 python ...
  $ kill -9 11111
  ```
  * [Kill Process in Linux or Terminate a Process in UNIX / Linux Systems - nixCraft](https://www.cyberciti.biz/faq/kill-process-in-linux-or-terminate-a-process-in-unix-or-linux-systems/)
* pushd and popd
  * [pushd and popd - Wikipedia](https://en.wikipedia.org/wiki/Pushd_and_popd)
    * In computing, pushd and popd are commands used to work with the command line directory stack.
  * [Linux pushd and popd Command Tutorial for Beginners (3 Examples)](https://www.howtoforge.com/linux-pushd-popd-command/#q-how-to-check-directory-stack)
* pwd 显示目录路径命令
* rm 删除文件
  * rm -rf 删除非空文件夹
  * [shell script to remove a file if it already exist - Stack Overflow](https://stackoverflow.com/questions/31318068/shell-script-to-remove-a-file-if-it-already-exist)
* rmdir 删除目录
* [rsync - a fast, versatile, remote (and local) file-copying tool](https://man7.org/linux/man-pages/man1/rsync.1.html)
  * `rsync --progress -z ~/local_path/test_file id@*.*.*.*:~/remote_path/`
  * [4 Ways to Transfer Files and Directories on Linux – devconnected](https://devconnected.com/4-ways-to-transfer-files-and-directories-on-linux/)
  * [如何在 Linux 中使用 rsync 传输文件](https://mp.weixin.qq.com/s/br7U-hXqNAPJUYYj23CJ-g)
* [sleep 将目前动作延迟一段时间](https://www.runoob.com/linux/linux-comm-sleep.html)
  * `sleep [--help] [--version] number[smhd]`
    * --help : 显示辅助讯息
    * --version : 显示版本编号
    * number : 时间长度，后面可接 s、m、h 或 d
      * 其中 s 为秒，m 为 分钟，h 为小时，d 为日数
* sudo
  * https://www.howtogeek.com/447906/how-to-control-sudo-access-on-linux/#:~:text=%20How%20to%20Control%20sudo,file.%20It%20is...%20More
  * The sudo command lets you run commands on Linux as though you were someone else, such as root. sudo also lets you control who can access root's capabilities, with granularity. Give users full access or let them use a small subset of commands.
  * Originally, it was called “superuser do”, because you could do things as the superuser. Its scope has been widened now, and you can use sudo to execute a command as though you were any user. It has been renamed to reflect that new functionality. It is now called “substitute user do.”
  * To use sudo to run a command as another user, we need to use the -u (user) option. Here, we’re going run the whoami command as the user mary. If you use the sudo command without the -u option, you’ll run the command as root.
    * `$ sudo -u mary whoami`
  * You can use the sudo command to log in as another user without knowing their password. You’ll be prompted for your own password. We need to use the -i (login) option.
    * `$ sudo -i -u mary`
* [tar](https://www.runoob.com/linux/linux-comm-tar.html)
  * `tar [-ABcdgGhiklmMoOpPrRsStuUvwWxzZ][-b <区块数目>][-C <目的目录>][-f <备份文件>][-F <Script文件>][-K <文件>][-L <媒体容量>][-N <日期时间>][-T <范本文件>][-V <卷册名称>][-X <范本文件>][-<设备编号><存储密度>][--after-date=<日期时间>][--atime-preserve][--backuup=<备份方式>][--checkpoint][--concatenate][--confirmation][--delete][--exclude=<范本样式>][--force-local][--group=<群组名称>][--help][--ignore-failed-read][--new-volume-script=<Script文件>][--newer-mtime][--no-recursion][--null][--numeric-owner][--owner=<用户名称>][--posix][--erve][--preserve-order][--preserve-permissions][--record-size=<区块数目>][--recursive-unlink][--remove-files][--rsh-command=<执行指令>][--same-owner][--suffix=<备份字尾字符串>][--totals][--use-compress-program=<执行指令>][--version][--volno-file=<编号文件>][文件或目录...]`
  * How to compress ?
    * [How to compress a whole directory (including subdirectories) using TAR in Unix based OS with the CLI | Our Code World](https://ourcodeworld.com/articles/read/642/how-to-compress-a-whole-directory-including-subdirectories-using-tar-in-unix-based-os-with-the-cli)
  ```sh
  $ tar -czvf test.tar.gz a.c
  $ tar -czvf test.tar.gz testdir/
  ```
  * How to extract .tar.gz Files ?
    * [How To Extract .tar.gz Files using Linux Command Line - Interserver Tips](https://www.interserver.net/tips/kb/extract-tar-gz-files-using-linux-command-line/)
  ```sh
  $ tar xvzf file.tar.gz
  $ tar xvzf file.tar.gz -C /path/to/somedirectory
  ```    
  * How to view the contents of tar.gz file without extracting it ?
    * [How can I view the contents of tar.gz file without extracting from the command-line? - Ask Ubuntu](https://askubuntu.com/questions/392885/how-can-i-view-the-contents-of-tar-gz-file-without-extracting-from-the-command-l)
    * `$ tar -tf filename.tar.gz`
* [taskset - set or retrieve a process's CPU affinity](https://man7.org/linux/man-pages/man1/taskset.1.html)
  * `taskset [options] mask command [argument...]`
  * `taskset [options] -p [mask] pid`
  * The taskset command is used to set or retrieve the CPU affinity of a running process given its pid, or to launch a new command with a given CPU affinity. CPU affinity is a scheduler property that "bonds" a process to a given set of CPUs on the system. The Linux scheduler will honor the given CPU affinity and the process will not run on any other CPUs. Note that the Linux scheduler also supports natural CPU affinity: the scheduler attempts to keep processes on the same CPU as long as practical for performance reasons. Therefore, forcing a specific CPU affinity is useful only in certain applications.
  * [How to run program or process on specific CPU cores on Linux](https://www.xmodulo.com/run-program-process-specific-cpu-cores-linux.html)
    * Install taskset on Linux
    * View the CPU Affinity of a Running Process
      * `$ taskset -p 2915`
      * `$ taskset -cp 2915`
    * Pin a Running Process to Particular CPU Core(s)
      * `$ taskset -p 0x11 9030`
      * `$ taskset -cp 0,4 9030`
    * Launch a Program on Specific CPU Cores
      * `$ taskset 0x1 test_pgm`
    * Dedicate a Whole CPU Core to a Particular Program
      * `isolcpus=0,1`
  * [How to set CPU affinity for a process from C or C++ in Linux? - Stack Overflow](https://stackoverflow.com/questions/280909/how-to-set-cpu-affinity-for-a-process-from-c-or-c-in-linux)
  * [Thread Affinity | CoffeeBeforeArch.github.io](https://coffeebeforearch.github.io/2020/05/27/thread-affinity.html)
  * [c++ - Set CPU affinity when create a thread - Stack Overflow](https://stackoverflow.com/questions/24645880/set-cpu-affinity-when-create-a-thread#:~:text=In%20C%2B%2B%2011%20you%20cannot,handle%20for%20the%20thread%20\(thread.)
  * [C++11 threads, affinity and hyperthreading - Eli Bendersky's website](https://eli.thegreenplace.net/2016/c11-threads-affinity-and-hyperthreading/)
* time
  * `time sleep 2`
  * [Linux time命令 | 菜鸟教程](https://www.runoob.com/linux/linux-comm-time.html)
  * [在Linux上，使用time优雅的统计程序运行时间](https://mp.weixin.qq.com/s/g8wQiVMwSBRAeBUSRuUrRQ)
* top
  * [10分钟教会你看懂top](https://mp.weixin.qq.com/s/8bBj1utjbF0-RIlWTF3KWQ)
    * [10分钟教会你看懂top](https://juejin.cn/post/6844903919588491278)
    * Load Average
    * top命令一行一行看
    * 其他命令
* [unzip 命令用于解压缩zip文件](https://www.runoob.com/linux/linux-comm-unzip.html)
  * `unzip [-cflptuvz][-agCjLMnoqsVX][-P <密码>][.zip文件][文件][-d <目录>][-x <文件>] 或 unzip [-Z]`
  * `unzip test.zip`
  * -v 参数用于查看压缩文件目录信息，但是不解压该文件。
    * `unzip -v abc.zip`
  * [How to Unzip Files in Linux | Linuxize](https://linuxize.com/post/how-to-unzip-files-in-linux/)
* who 你的用户名和终端类型
* [zip 命令用于压缩文件](https://www.runoob.com/linux/linux-comm-zip.html)
  * `zip [-AcdDfFghjJKlLmoqrSTuvVwXyz$][-b <工作目录>][-ll][-n <字尾字符串>][-t <日期时间>][-<压缩效率>][压缩文件][文件...][-i <范本样式>][-x <范本样式>]`
  * -f 更新现有的文件。
  * -j 只保存文件名称及其内容，而不存放任何目录名称。
  * overwrite zip file
    * `zip -FSj test.zip a.txt b.txt`
  * [How to Zip Files and Directories in Linux | Linuxize](https://linuxize.com/post/how-to-zip-files-and-directories-in-linux/)
  * [command line - How to overwrite existing zip file instead of updating it in Info-Zip? - Super User](https://superuser.com/questions/350991/how-to-overwrite-existing-zip-file-instead-of-updating-it-in-info-zip)
* 定义变量 name=abc? (bash/pdksh) || set name = abc (tcsh)

## BASH

* [dylanaraps/pure-bash-bible: 📖 A collection of pure bash alternatives to external processes.](https://github.com/dylanaraps/pure-bash-bible#loop-over-a-range-of-numbers)
* [『一网打尽』 Bash 常用命令](https://mp.weixin.qq.com/s/uWDli1O5u73GCx0MpsGcWg)

## VIM

* [Linux vi/vim | 菜鸟教程](https://www.runoob.com/linux/linux-vim.html)
* [Vim Cheat Sheet](https://vim.rtorr.com/)
* [8个技巧让Vim菜鸟变专家](https://mp.weixin.qq.com/s/KrBwSk_UgyZLivcXAMS2xQ)
* [10款好用的Vim插件，你知道几个？](https://mp.weixin.qq.com/s/S4afPpMrBtYV6ml8Qb4NXw)
  * https://opensource.com/article/19/11/vim-plugins

## SHELL

* [Shell 教程 | 菜鸟教程](https://www.runoob.com/linux/linux-shell.html)
* [学习笔记之Shell脚本的输出重定向 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/4955877.html)
* [学习笔记之Linux Shell脚本教程：30分钟玩转Shell脚本编程 - 浩然119 - 博客园](https://www.cnblogs.com/pegasus923/p/5304025.html)
* [编写可靠Linux shell脚本的八个建议](https://mp.weixin.qq.com/s/NNYuIfzEoitXKnHteJwj_A)
* [10 个实战与面试【常用 Shell 脚本】编写](https://mp.weixin.qq.com/s/xuC_pH1X_GmyK0vVWrBzWQ)
  * https://blog.51cto.com/lizhenliang/1929044
* [Linux Shell 基础 -- 总结几种括号、引号的用法](https://mp.weixin.qq.com/s/nM3P7iVIygrwEEhkjDdH4Q)
  * https://www.cnblogs.com/tongye/p/10646211.html
* [一份Linux shell“圣经”收好](https://github.com/dylanaraps/pure-bash-bible)
* [Linux Shell 时间运算以及时间差计算方法！](https://www.cnblogs.com/chengmo/archive/2010/07/13/1776473.html)
* How to iterate date range to execute cmd ?
  * [Loop through a date range in Shell Script | TechieRoop](https://techieroop.com/loop-through-a-date-range-in-shell-script/)
  * [shell - How to concatenate string variables in Bash - Stack Overflow](https://stackoverflow.com/questions/4181703/how-to-concatenate-string-variables-in-bash)
  * [How to catch and handle errors in bash](https://www.xmodulo.com/catch-handle-errors-bash.html)
```sh
#!/usr/bin/bash

# input args
# start=$1
# end=$2

# hardcode values
start='20221101'
end='20221109'

start=$(date -d $start +%Y%m%d)
end=$(date -d $end +%Y%m%d)

while [[ $start -le $end ]]
do
    cmd="rm -f ./output_$start.log && ./test_pgm >> ./output_$start.log"
    echo $cmd
    eval $cmd || echo
    start=$(date -d"$start + 1 day" +"%Y%m%d")
done
```

## FAQ

* What's localhost ?
  * [localhost - Wikipedia](https://en.wikipedia.org/wiki/Localhost)
  * The name localhost normally resolves to the IPv4 loopback address 127.0.0.1, and to the IPv6 loopback address ::1.
* How to fix Address already in use ?
  * [Bind failed: Address already in use - Stack Overflow](https://stackoverflow.com/questions/15198834/bind-failed-address-already-in-use)
  * Use netstat -tulpn to display the processes
  * Use netstat -pnlt | grep ':1' to find which process use the port 1
    * [networking - how to use netstat on a specific port in Linux - Super User](https://superuser.com/questions/602049/how-to-use-netstat-on-a-specific-port-in-linux)
  * kill -9 <pid> This will terminate the process
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
* How to add and use alias ?
  ```sh
  $ alias test=~/bin/test
  $ test
  ```
* How to find out a CPU Core that is running a particular Process in Linux ?
  * [4 Ways to Find Out a CPU Core that is running a particular Process in Linux - Techglimpse](https://techglimpse.com/find-cpu-processor-running-process-linux/#:~:text=You%20can%20use%20ps%20command,field%20in%20ps%20command%20output.&text=The%20above%20command%20output%20indicates,assigned%20to%20CPU%20core%202.)
    * Command 1 : Using ps command
      * You can use ps command to find out which process is currently assigned to which CPU core. Lookout for the PSR field in ps command output.
        * `$ ps -o pid,psr,comm -p 24868`
    * Command 2: Using top command
      * In the ‘top’ output screen, hit ‘f‘ to add “Last used cpu (SMP)” and hit ‘j‘ (lookout for the asterisk in the Last used cpu (SMP) row). Once done, you’ll see CPU core ID that runs each process in column ‘P’.
    * Command 3: Using htop
      * Launch htop command and hit F2 to enter Setup. Under Setup column, select ‘Columns’ and select “PROCESSOR’ under “Available Columns”. Once done, hit F5 to add the column and F10 to save.
    * Command 4: Using taskset command
      * You can use taskset command to retrieve CPU affinity of a running process.
        * `$ taskset -c -p 24868`
* How to stop jupyter notebook ?
```sh
$ ps ax | grep notebook
19843 pts/2    Tl20170 pts/2    S+
$ kill -9 19843
```
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
* What's .bashrc ?
  * .bashrc is a shell script that Bash runs whenever it is started interactively. It initializes an interactive shell session.
    * [bash - What is the purpose of .bashrc and how does it work? - Unix & Linux Stack Exchange](https://unix.stackexchange.com/questions/129143/what-is-the-purpose-of-bashrc-and-how-does-it-work)
  ```sh
  $ cat .bashrc
  ```
* How to activate virtualenv automatically when login session ?
```sh
$ echo 'source /virtualenv/source/.venv/bin/activate' >> ~/.bashrc
$ cat ~/.bashrc
# .bashrc
...
source /virtualenv/source/.venv/bin/activate
```
* How to fix `fatal error: error writing to /tmp/ccdm6pWv.s: No space left on device` ?
  * [c - Unable to compile with make | fatal error No space left on device - Stack Overflow](https://stackoverflow.com/questions/31493663/unable-to-compile-with-make-fatal-error-no-space-left-on-device)
  * check and delete files `df -h /tmp`
  * workaround 
    ```sh
    mkdir ~/tmp
    export TMPDIR=~/tmp
    ```

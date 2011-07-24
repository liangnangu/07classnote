#vim

    进入 可视行模式快捷键shift + v

    退出  再次按大写v

    剪切d  粘贴 p（小写在光标下一行粘贴，大写在光标上一行粘贴）
    可视行模式下选中多行
     
    然后shift + > 整体缩进多行

    然后shift + < 整体减少多行

## multiple files  可视行模式

    :ls #see buffers

    :bn # go to next buffer

    :bp # go to previous buffer

    :bd # delete a buffer

##  插入模式快捷键

    ctrl + n 可以自动补齐，查找匹配字符；

    ctrl + t 自动缩进

    ctrl + d 缩进返回

## ~/ .vimrc

    vim的配置文件

###vim的配置

    自动缩进 set autoindent

    显示行号 set number

    tabstop= 4 

    set shiftwidth=4  可视行缩进为四个空格

    map ,ss :set spell<cr>  在vim中把set spell用，ss映射。注意map是普通模式映射的快捷键

    imap  jj <esc>  从插入模式回到普通模式  把esc用jj映射 注意imap是插入模式快捷键映射的代号


#gcc

    gcc -E 编译生成.i结尾的中间文件

    gcc -S 编译生成.s结尾的汇编文件

    gcc -c 编译生成.o结尾的机器码文件

    gcc -o 指定生成文件的名字

    gcc -l 指定包含文件存放的目录

    gcc -Wall　打开所有警告


# peter video

http://media.happypeter.org/screencasts.html



# git

## install安装

    sudo apt-get install git-core 

    sudo apt-get install tig

    git pull

##githup 操作步骤

    lobal setup:

     Set up git

            git config --global user.name "liangnangu"

            git config --global user.email 574647990@qq.com

      Add your public key


    Next steps:

             mkdir classnote

             cd classnote

             git init//初始化

             touch README

             git add README//通知git跟踪REMADME

             git commit -m -a 'first commit'//做一个版本

             git remote add origin git@github.com:liangnangu/classnote.git//'这个地方要注意第一次上传必须要有这一行，以后push可以没有'

             git push -u origin master


    Existing Git Repo?Y

            cd existing_git_repo

            git remote add origin git@github.com:liangnangu/classnote.git

            git push -u origin master


    Importing a Subversion Repo?

      Click here


    When you are done:

      Continue

    git rm 文件名 通知git不在跟踪某文件 用于删除网页上某个无用的文件

# linux basics

    Linux is OS(operating system)

    OS as linus see it:

    OS is nothing but the kernel.

    Linux is nothing but the kernel.

    ubuntu is Linux + 1000 app.

    OS as MS see it:

    OS is kernel + desktop env.
# tips

   Clear screen : Ctrl-l

   Copy and Paste: select -> middle button

## language

https://github.com/happypeter/job-akae/wiki

## translation

http://dict.youdao.com/

# shell ( shell is a commandline interpreter)



bash is a kind of shell. 

## filesystem tree

    ls

    cd
# ~ means your home dir

    cd .. # go to the parent of current dir

    pwd

    man pwd # q to quit

    mkdir dir

### path

    绝对路径: start with /

    相对路径: start with .

## shell prompt

    peter@cow:~/tg-note$

    user@machinename:currentWorkingDirectory(folder)$

# software installation

    sudo apt-get install tree

## where we are

    locate 文件名     在系统上定位某个文件

    sudo updatedb     更新数据库

    find 文件名       查找一个文件

    | 表示管道符  表示前面的输出作为后面的输入

    grep 字符串      查找匹配的字符串

    find 文件名|grep 字符串   在查找出来的文件中匹配字符串并输出

    ps 列出系统上当前的进程

    ps aux 列出系统上所有的进程

    kill ID号 关闭对应的进程

    kill -9 ID号 强行关闭死掉的进程

    ls|grep tig  在列出的目录下查找匹配的文件


# tar 

http://www.happypeter.org/posts/10

# ref

http://happypeter.github.com/LGCB/

http://billie66.github.com/TLCL/book/i

# reading

http://norvig.com/21-days.html

## some of my favorite sites

http://www.linfo.org/

http://www.wikipedia.org/

http://news.ycombinator.com/news



# 终端


    shift + ctrl + t  打开一个新标签

    ctrl + pgup ctrl+ pgdn 标签之间切换

    ctrl + alt + t 打开一个终端

    ctrl + d   关闭一个终端 关闭一个标签

    ctrl + alt + d 最小化最大化终端之间切换

    ctrl + r 根据关键子 查找最近输入的命令

    alias 重定向 格式 aaa = 'sudo apt-get install'

    shell 配置文件名字 .bashrc   位于当前目录下

    source .bashrc  通知shell 重读配置文件


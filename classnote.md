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
## ~/ .vimrc

# peter video

http://media.happypeter.org/screencasts.html



# git
## install安装

    sudo apt-get install git-core 
    sudo apt-get install tig

    git pull
githup 操作步骤
Global setup:

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
         git remote add origin git@github.com:liangnangu/classnote.git//
         git push -u origin master


Existing Git Repo?Y

        cd existing_git_repo
        git remote add origin git@github.com:liangnangu/classnote.git
        git push -u origin master


Importing a Subversion Repo?

  Click here


When you are done:

  Continue

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



# tar 

http://www.happypeter.org/posts/10

# ref

http://happypeter.github.com/LGCB/

http://billie66.github.com/TLCL/book/i



# 终端


shift + ctrl + t  打开一个新标签

ctrl + pgup ctrl+ pgdn 标签之间切换

ctrl + alt + t 打开一个终端

ctrl + d   关闭一个终端 关闭一个标签

ctrl + alt + d 最小化最大化终端之间切换


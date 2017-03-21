# linux-commands
some commands</br>
>mv(移动或更名现有的文件或目录)</br>
>    description:mv -bfiuv oldfile newfile</br>
>    -b 若需覆盖文件,则覆盖前先行备份</br>
>    -f 若目标文件或目录与现有的文件或目录重复,则直接覆盖现有的文件或目录</br>
>    -i 覆盖前先行询问用户</br>
>    -u 在移动或更改文件名时,若目标文件已存在,且其文件日期比原文件新,则不覆盖目标文件</br>
>    -v 执行时显示详细的信息</br>

rm(删除文件或目录)
    description:rm -dfirv file
    -d 直接把欲删除的目录的硬连接数据删成0,删除该目录
    -f 强制删除文件或目录
    -i 删除既有文件或目录之前先询问用户
    -r 递归处理,将指定目录下的所有文件及子文件一并处理
    -v 显示指令的执行过程

cp(复制文件或目录)
    description:cp -abdfilpPrRsuvx oldfile newfile
    -a 此参数的效果和同时指定"-dpR"参数相同
    -b 删除,覆盖目标文件之前的备份,把目标文件或目录也建立符号连接,并指向与源文件或目录连接的原始文件或目录
    -f 强制复制文件或目录,不论目标文件或目录是否已存在
    -i 覆盖既有文件之前先询问用户
    -l 对源文件建立硬连接而非复制文件
    -p 保留源文件或目录的属性
    -P 保留源文件或目录的路径
    -r 递归处理,将指定目录下的文件与子目录一并处理
    -R 递归处理,将指定目录下的所有文件与子目录一并处理
    -s 对源文件建立符号连接而非复制文件
    -u 使用这项参数后只会在源文件的更改时间较目标文件更新时或是名称相互对应的目标文件并不存在时才复制文件
    -v 显示指令执行过程
    -x 复制的文件或目录存放的文件系统必须与cp指令执行时所处的文件系统相同,否则不予复制

cd(切换目录)
    description:cd dir

ls(列出目录内容)
    description:ls -1aAbBcCdDfFgGhHiklLmnNopqQrRsStuUvxX
    -1 每列仅显示一个文件或目录名称
    -a 显示所有文件和目录
    -A 显示所有文件和目录但不现实现行目录和上层目录
    -b 显示脱离字符
    -B 忽略备份文件和目录
    -c 以更改时间排序
    -C 以上至下，左到右的直行方式显示
    -d 显示目录名称而非其内容
    -D 用Emacs的模式产生文件和目录列表
    -l 使用详细格式列表
    -N 直接列出文件和目录名称,包括控制字符
    -Q 把文件和目录名称以""号标示起来
    -r 反向排序
    -R 递归处理,将指定目录下的所有文件及子目录一并处理
    -s 显示文件的目录的大小
    -S 用文件和目录的大小排序
    -t 用文件和目录的更改时间排序

mkdir(建立目录)
    description:mkdir -p dir
    -p 若所要建立目录的上层目录尚未建立,则会一并建立上层目录

pwd(显示当前目录)
    description:pwd

rmdir(删除目录)
    description:rmdir -p --ignore-fail-on-non-empty 
    -p 删除指定目录后,若该目录的上层目录已变成空目录,则将其一并删除
    --ignore-fail-on-non-empty 忽略非空目录的错误信息



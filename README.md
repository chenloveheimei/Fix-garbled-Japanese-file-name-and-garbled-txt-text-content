# Fix-garbled-Japanese-file-name-and-garbled-txt-text-content
修复日语文件名乱码、日语txt文本内容乱码
一般在日网下载的压缩包直接解压会乱码，这个是自动修复的小脚本
好像说解压时用winrar哪里有设置就可以不乱吗但是我找不到。

直接输入文件夹路径，里面的文件的文件名（文件夹名也可以）和txt文本内容都可以修复乱码。
我的电脑是gbk编码，如果不行的话可以把把代码里面的<gbk>改成你电脑的编码。只会修改纯日语乱码（比如乱码里面掺杂了中文，程序会提示跳过），用的日语编码是<Shift_JIS>

打包了一个.exe文件，没有装python也可以直接运行，具体操作：
change_coding.exe文件双击运行，按提示选择修复文件夹乱码还是txt文本乱码，然后输入乱码文件所在文件夹路径。每一次修改之前都有确认，不用担心把文件名搞错搞乱。
注：因为文件要修改文件名之类，会被杀毒软件看成木马隔离。拉出隔离区、添加信任，就可以用了。
在另外一台电脑上(也是win10)试了试可以用。但是这个是64位的版本。

python代码很少很简单的。
注：这个是修复文件名和txt文件乱码的，游戏乱码不行的。

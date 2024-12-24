# 《金庸群侠传》复刻版
<img src='https://raw.githubusercontent.com/scarsty/kys-pascal/master/open.png' />

<img src='https://raw.githubusercontent.com/scarsty/kys-pascal/master/2.png' />

原DOS下面的经典游戏《金庸群侠传》pascal复刻版。

通过更换数据包，可以运行大部分MOD。

## 如何编译
SDL2的pas文件请从<https://github.com/ev1313/Pascal-SDL-2-Headers>获取,把Pascal-SDL-2-Headers项目下的所有pas、inc文件都复制过来放到这里kys.lpr入口文件同目录下。其他外部库的文件均已经自带。

首先下载游戏本体，其中包含了Windows版本的exe文件和dll文件以及资源文件：<https://pan.baidu.com/s/1nv9R5rz>。

注意大部分是使用商业性质的素材，禁止使用其盈利。

安装Lazarus，如果你对命令行熟悉可以只安装fpc，推荐使用最新版。CodeTyphon也可以。

使用Delphi社区版也可以编译，但不推荐。

不在Windows下面编译则需要安装运行库，用brew（Mac），apt-get（Ubuntu）之类安装sdl，sdl-mixer，sdl-ttf，sdl-image，smpeg，lua等相关sdl库。
如果lua库不能自动安装5.2版，下载lua5.2库自行编译，需要编译成支持i386的库。

检查lua52的开头部分指定的库文件名字，如果与现有的不同则修改。

在Windows，Mac，Ubuntu（我目前只试过这个Linux发行版）下面，库文件配置正确时，均可以用fpc直接编译通过。

未包含Android的工程。



## 注意
建议改用c++版：<https://github.com/scarsty/kys-cpp>。

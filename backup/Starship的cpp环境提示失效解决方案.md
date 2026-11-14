### 前情提示：博主在切换文件📄目录时发现在含.c,.python文件的目录中正常，而在遇到.cpp文件就失效了
于是博主开始问deepaseek,它先让我更新Starship，但是我的Steamship版本已经是最新了
所以它便让我改一下[c]，改成如下
> [custom.cpp]
> detect_extensions = ["cpp", "hpp", "cc"]
### 但是还是没用
### Deepseek便让我继续把[c]改成[custom.c],并在[format]中把$c\改为$custom.cpp
### 发现出现了环境提示，但是多了.cpp 
## 于是我便意识到是[c]出了问题，把[c]中的"c"换一个不会冲突的变量名就好了🥳
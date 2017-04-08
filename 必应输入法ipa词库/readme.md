# 必应输入法国际音标自定义词库
### 编码方案
#### 编码方案基础来源
- 潘悟云先生设计的云龙国际音标输入法（![http://www.eastling.org/resource.htm] (http://www.eastling.org/resource.htm)）
#### 修正方案
因必应输入法中数字用于候选词上屏，因此原编码中带数字的均作了修改，具体包括：
1. 圈发符号的数字编码修改如下：
![enter image description here](https://i.imgur.com/L7v8kmG.png)
2. θ原编码为数字0，改为oo-，此类的还有?等。
3. 逗号键（,<）和句号键（.>键）一般作为翻页用，编码中.号失效，故一律转换为d，虽和表示字符倒转的d（如ad，?）相冲突，增加了重码，但起码功能能继续保持，具体涉及音标：
![enter image description here](https://i.imgur.com/5OTHp0y.png)

## 使用方法
1. 将userdefinephrase.dat文件替换到必应输入法安装目录下的/shared的文件夹中；
2. 可能需要切换输入法或者重启系统才能生效。

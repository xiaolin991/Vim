## 移动
Vim 的两种单词对象：
狭义单词word:由空白字符（空格、制表符或换行符）分隔的字母、数字和下划线组成的序列。
广义单词Word：空格分隔的任何非空字符组成的序列
```
farm = add_animal(farm, animal)
输入w
W
```
按键           作用
w   next word             逐个狭义单词移动
e   end word           向前移动直到最近单词的结尾
W   next WORD           逐个广义单词移动
E   End WORD           向前移动直到最近广义单词的结尾
b   prev word           向后移动到狭义单词开头
B   prev WORD           向后移动到广义单词开头

x  delete char
X back-space
Basics:
h j k l are vi/vim cursor keys-use them as they are much closer than regular cursor keys!
Use i to enter insert mode,cursor turns from a block into a vertical line, and you can type in text.Use "Esc" to return Normal mode.
Use x to delete the current character,or X to delete the one to the left.
Use A to go insert text and the end of the line(whereever you are in the line!)
u to undo the last action-traditional vi has a single level, while vim supports unlimited undo(CTRL-R to redo)
0 jumps directly to the beginning of the line, $ to the end,and ^ to the first non-blank
Use R to enter insert mode with an overstrike cursor,which types over existing characters. 

1. 使用 * 键可以向后搜索光标所在位置的单词。反之，使用 # 键可以向前搜索光标所在位置的单词。第一次使用 * 或者 # 进行搜索之后，则可以使用 N 或 Shift-N 继续进行搜索。另外，如果设置了hlsearch选项（:set hlsearch）的话，那么使用 * Shift-N 则可以标记当前的单词为高亮显示。

2、在你的~/.vimrc中设置 set hlsearch ,这样的话你所搜索的所有匹配项将高亮显示出来，搜索另外一个不存在的词将会是之前的高亮匹配项取消高亮，或者使用  ": nohlsearch"也行，但是后者需要在你的vimrc文件中设计 set hlsearch,这样的话在你其他的搜索中仍能高亮。

：%s/objstr//gn 统计objstr出现的次数

:/objstr 搜索objstr n 向后找 N 向前找

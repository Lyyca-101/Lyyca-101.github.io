<h1 >关于XV6 Lab1的shell tab completion challenge</h1>
首先得想办法让terminal能够不回显tab<br>
其次是参考GNU readline library，其中有非常成熟的命令补全以及命令历史记录的实现<br>
实际上，很多的shell、一些工具的命令行模式，都使用了这个库
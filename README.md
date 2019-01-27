# JS-Gobang
使用js配合canvas实现网页五子棋小游戏.
布局： 1.标题 2.canvas棋盘 3.div>div*3(重新开始、悔棋、撤销悔棋)
    var _nowi = 0, _nowj = 0; //记录自己下棋的坐标
    var _compi = 0, _compj = 0; //记录计算机当前下棋的坐标
    var _myWin = [], _compWin = []; //记录我，计算机赢的情况
    
通过位置占用判断输赢，canvas画棋盘和棋子.


# sudoku
To solve a sudoku
用递归的方法对每个点的可能的取值进行试探 当其取值不符合数独规，则时则返回上一层进行下一次试探

在进行递归前对A[9][9]的数组进行扫描，排除明显错误的值，减小递归的深度。

# Quicksort
It is all about Quicksort

快速排序是基于分治模式
快速排序是基于就地排序

分解：数组A【p..r】被划分成两个（可能空）子数组A【p..q-1】和A【q+1..r】，使得A【p..q-1】中的每个元素都小于等于A(q)，而且，小于等于A【q+1..r】中的元素。下 标q 也在返个划分过程中迕行计算。
解决：通过递归调用快速排序，对子数组A【p..q-1】和A【q+1..r】排序。
合并：因为两个子数组使就地排序的，将它们的合并不需要操作：整个数组A【p..r】已排序。

数组划分：Partition（关键，它对子数组A【p..r】进行就地重排）



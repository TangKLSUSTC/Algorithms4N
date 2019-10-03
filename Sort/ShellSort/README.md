# 希尔排序

又称，缩小增量排序（diminishing-increment sort）。
又称其实就是把整个算法的逻辑给体现了出来。

选一个间隔gap，即，每间隔一个gap就取一个数，这样就将原来的序列构成了gap个子序列，在每个子序列上做插入排序。
之后，再不断地缩小间隔。直到gap为1。

* 当n足够大时，时间复杂度在O(n^1.25)。

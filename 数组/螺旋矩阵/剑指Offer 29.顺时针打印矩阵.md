[力扣题目链接](https://leetcode.cn/problems/shun-shi-zhen-da-yin-ju-zhen-lcof/description/)<br>
此题为原题：
[原题题解](https://github.com/RenYin812/programmercarl-leetcode-notes/blob/main/%E6%95%B0%E7%BB%84/%E8%9E%BA%E6%97%8B%E7%9F%A9%E9%98%B5/54.%E8%9E%BA%E6%97%8B%E7%9F%A9%E9%98%B5.md)\
虽然力扣上面说与螺旋矩阵那道题相同，但限制却不同，此题的限制为0 <= matrix.length <= 100；0 <= matrix[i].length <= 100，多了0这种情况，上述题解能够处理1的情况
但如果是空矩阵还需在函数里最前面加上if语句：
```C
if (matrixSize == 0 || matrixColSize[0] == 0) {
        *returnSize = 0;
        return NULL;
    }
```

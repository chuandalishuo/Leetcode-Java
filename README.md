Leetcode-java
=============
Author: Shuo Li

Solutions of leetcode coding problems

0. Easy

        3. 4Sum (夹逼,剪枝)
        4. Add Binary (进位)
        5. Add Two Numbers (进位)
        6. Anagram (HashMap, String sort)
        7. Balanced Binary Tree (Recursive)
        8. Best Time to Buy and Sell Stock (greedy)
        9. Best Time to Buy and Sell Stock II (greedy)
         . Maximum Subarray (DP)
        11.Binary Tree In order Traversal (Recursive)
        12.Binary Tree Level Order Traversal (Recursive)
        15.Binary Tree post order Traversal (Recursive)
        16.Binary Tree Preorder Traversal (Recursive)
        17.Binary Tree Zigzag Level Order Traversal (Recursive, Collections.reverse(List))
        18.Candy (前后扫描)
        19.Climbing Stairs(DP,斐波那契数列)
        22.Combination Sum II (深搜+目标递减+不断向后搜索+剪枝)
        23.Combinations (深搜+目标递减+不断向后搜索)
        25.Construct Binary Tree from Preorder and Inorder Traversal (same as 24)
        27.Convert Sorted Array to Binary Search Tree(similar as 24, more simple, 递归折半)
        .Trapping Rain Water(每个柱能储水取决于两侧最高柱高度较短的和当前柱高度差。 两种思路：1.DP找到每个柱的左最高和右最高；2.先找最高的柱分成两半，两边向中间算。相似26)
        29.Copy List with Random Pointer(制作重复链表，复制随机指针，断开重复链表。注意null判断)
1. Need to do more times
    
        1. 3Sum (夹逼,剪枝)
        2. 3Sum Closest (夹逼,剪枝)
        13.Binary Tree Level Order Traversal II(reverse recursive, Collections.reverse(List))
        21.Combination Sum (深搜+目标递减+不断向后搜索+剪枝)
2. Time consuming

        20.Clone Graph(dfs/bfs graph traversal + HashMap mark cloned)
        24.Construct Binary Tree from Inorder and Postorder Traversal (递归，用inorder中左右子树长度确定postorder中左右子树的分割)
3. Difficult
        
        10. Best Time to Buy and Sell Stock III (最大M段子和, 两侧DP)
        14. Binary Tree Maximum Path Sum
        26.Container With Most Water (容积取决于短板和间隔，greedy每次保证不减, 两头夹逼测试，间隔在缩短，就要保证短板在增高。夹逼过程还可以剪枝。)
        28.Convert Sorted List to Binary Search Tree (递归折半，全局变量遍历链表)
        . Largest Rectangle in Histogram(由每个柱高度决定的矩阵的宽度是距它最左和最右并不比它矮的柱之间的距离。one way is O(n^2). 高效的方法是维护递增堆栈，直到当前柱太矮，处理由之前比它高的每一个柱决定的面积：出栈一个柱，以它为高度；相应的矩形宽度是从当前矮柱的前一格到当前栈顶的柱的后一格（这两个柱比它矮，而其间的所有柱都比它高，都已出栈）。)

## STLAlgorithm
analysis stl algorithm

### Permuting Elements

- [x] bool next_permutation (BidirectionalIterator beg, BidirectionalIterator end)
- [x] bool next_permutation (BidirectionalIterator beg, BidirectionalIterator end, BinaryPredicate op)
- [ ] bool prev_permutation (BidirectionalIterator beg, BidirectionalIterator end)
- [ ] bool prev_permutation (BidirectionalIterator beg, BidirectionalIterator end, BinaryPredicate op)

参考练习：

- LeetCode 31. 下一个排列

#### Removing Elements in a Sequence

- [x] ForwardIterator remove (ForwardIterator beg, ForwardIterator end, const T& value)
- [x] ForwardIterator remove_if (ForwardIterator beg, ForwardIterator end, UnaryPredicate op)

补充： `list` 和 `forword_list` 提供了效果相同的成员函数 `remove` 和 `remove_if`，效率较高，因为不需要重新赋值，只是重新链接。

参考练习：

- Leetcode 27. 移除元素
- Leetcode 203. 移除链表元素
importance: 3

---

# 随机排序

编写函数 `shuffle(array)` 混洗（随机重新排序）数组的元素。

多次运行 `shuffle` 可以导致不同的元素顺序。例如：

```js
let arr = [1, 2, 3];

shuffle(arr);
// arr = [3, 2, 1]

shuffle(arr);
// arr = [2, 1, 3]

shuffle(arr);
// arr = [3, 1, 2]
// ...
```

所有元素顺序应该具有相等的概率。例如，`[1,2,3]` 可以重新排序为 `[1,2,3]` 或 `[1,3,2]` 或 `[3,1,2]` 等。每种情况的概率相等。



# Теория
https://leetcode.com/explore/learn/card/array-and-string/

---
# GPT
## 1. Теория по массивам
- **Что такое массив**: упорядоченная структура данных, хранящая элементы одного типа.    
- **Операции над массивами**:    
    - Доступ к элементу по индексу — `O(1)`.        
    - Поиск элемента — `O(n)`, если неотсортирован, `O(log n)`, если отсортирован (бинарный поиск).        
    - Вставка/удаление элемента в конец — `O(1)`.        
    - Вставка/удаление элемента в начало или середину — `O(n)`, так как приходится сдвигать элементы.        
- **Два указателя (Two Pointers)** — техника оптимизации при решении задач на массивы.
- **Sliding Window (скользящее окно)** — техника для оптимизации поиска подмассивов с определенными свойствами.
- **Prefix Sum и Difference Array** — полезные техники для быстрых вычислений сумм на подотрезках.
- **Отсортированные и несортированные массивы**: важные алгоритмы, такие как **бинарный поиск** и **merge-sort**.
## 2. Задачи на массивы
## 🔹 **Базовые задачи (Easy)**
- [Two Sum](https://leetcode.com/problems/two-sum/) — найти два элемента, сумма которых равна `target`.
- [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) — найти максимальную прибыль от покупки/продажи акций.
- [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/description/) — удалить дубликаты из отсортированного массива.
- [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) — проверить, есть ли в массиве дубликаты.
- [Majority Element](https://leetcode.com/problems/majority-element/) — найти элемент, встречающийся более `n/2` раз.
## 🔹 **Средние задачи (Medium)**
- [3Sumhttps://leetcode.com/problems/3sum/]() — найти три элемента, сумма которых равна 0.
- [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/description/) — создать массив, где каждый элемент — это произведение всех элементов, кроме текущего (без деления).
- [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/) — найти количество подмассивов с суммой `k`.
- [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/description/) — найти самую длинную последовательность подряд идущих чисел в массиве.
- [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/) — найти минимальный элемент в повернутом отсортированном массиве.

## 🔹 **Сложные задачи (Hard)**
- [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) — найти медиану двух отсортированных массивов.
- [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/description/) — найти объем воды, который может быть собран после дождя.
- [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/description/) — найти максимум в каждом подмассиве фиксированной длины.
- [Longest Subarray with At Most K Distinct Elements](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/description/) — найти длину самого длинного подмассива с не более чем `K` различными элементами.
- [Merge Intervals](https://leetcode.com/problems/merge-intervals/description/) — объединить пересекающиеся интервалы
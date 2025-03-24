# Теория
https://leetcode.com/explore/learn/card/array-and-string/

---
# GPT
## 1. Теория по СТРОКАМ
- **Хранение строк в памяти**: строки неизменяемы в большинстве языков.    
- **Операции над массивами**:    
    - Поиск подстроки — `O(n)` с использованием **KMP-алгоритма** или **Rabin-Karp**.        
    - Разворот строки — `O(n)`.
    - Сравнение строк — `O(n)`.  
- **Sliding Window для строк** — полезен при анализе подстрок.
- **Hashing в строках** — позволяет эффективно сравнивать строки.
- **Trie (префиксное дерево)** — структура данных для хранения и поиска слов.
- **Anagrams & Palindromes** — <font color="#c00000">частые темы на собеседованиях</font>.
## 2. Задачи на массивы
## 🔹 **Базовые задачи (Easy)**
- [Valid Anagram](https://leetcode.com/problems/valid-anagram/description/) — проверить, являются ли две строки анаграммами.
- [Reverse String](https://leetcode.com/problems/reverse-string/) — развернуть строку.
- [First Unique Character in a String](https://leetcode.com/problems/first-unique-character-in-a-string/) — найти первый уникальный символ.
- [Implement strStr()](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/description/) — найти индекс первого вхождения подстроки в строку.
- [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) — проверить, является ли строка палиндромом.
## 🔹 **Средние задачи (Medium)**
- [Group Anagrams](https://leetcode.com/problems/group-anagrams/description/) — сгруппировать анаграммы.
- Longest Substring Without Repeating Characters — найти самую длинную подстроку без повторяющихся символов.
- Longest Palindromic Substring — найти самую длинную палиндромную подстроку.
- Decode String — раскодировать закодированную строку.
- Find All Anagrams in a String — найти все вхождения анаграмм подстроки в строке.

## 🔹 **Сложные задачи (Hard)**
- Minimum Window Substring — найти минимальную подстроку, содержащую все символы другой строки.
- Edit Distance — найти минимальное количество операций для преобразования одной строки в другую.
- Palindrome Partitioning — разбиение строки на палиндромные подстроки.
- Substring with Concatenation of All Words — найти все подстроки, состоящие из перестановок слов заданного списка.
- Word Search II — найти все слова в матрице букв.
# AtCoder Practice Log
This repository is my training log for AtCoder.　

## 1. Contest History
| Contest | Result | Learnings (Qiita) |
| :--- | :--- | :--- |
| [AtCoder Beginner Contest 430](https://atcoder.jp/contests/abc430) | A-Task (100) | [Qiita](https://qiita.com/iamthinking98/items/eba690b8573557dc5b83) |
| [AtCoder Beginner Contest 431](https://atcoder.jp/contests/abc431) | A-Task (100), B-Task(200) | - |
| [AtCoder Beginner Contest 432](https://atcoder.jp/contests/abc432) | A-Task (100)| - |
| [AtCoder Beginner Contest 433](https://atcoder.jp/contests/abc433) | A-Task (100), B-Task(200), C-Task(TLE)| - |
| [AtCoder Beginner Contest 434](https://atcoder.jp/contests/abc434) | A-Task (100), B-Task(200)| - |
| [AtCoder Beginner Contest 435](https://atcoder.jp/contests/abc435) | A-Task (100), B-Task(200)| - |
| [AtCoder Beginner Contest 436](https://atcoder.jp/contests/abc436) | A-Task (100), B-Task(200)| - |
| [AtCoder Beginner Contest 437](https://atcoder.jp/contests/abc437) | A-Task (100), B-Task(200)| - |
| [AtCoder Beginner Contest 438](https://atcoder.jp/contests/abc438) | A-Task (100), B-Task(200)| - |
| [AtCoder Beginner Contest 440](https://atcoder.jp/contests/abc440) | A-Task (100), B-Task(200)| - |


# Practice Log
| Problem | Submission (The Code) | Key Takeaway |
| :--- | :--- | :--- |
| [AtCoder Beginner Contest 430 - problem_B](https://atcoder.jp/contests/abc430/tasks/abc430_b) | [atcoder1.ipynb - my_answer](https://github.com/iamthinking98-jpg/AtCoder/blob/main/atcoder1.ipynb) | Using set with tuple `for` duplicate checking.　List comprehension, nested `for` loops.|
| [AtCoder Beginner Contest 428 - problem_B](https://atcoder.jp/contests/abc428/tasks/abc428_b) | [atcoder2.ipynb - my_answer](https://github.com/iamthinking98-jpg/AtCoder/blob/main/atcoder2.ipynb) | Using **collections.Counter** for efficient frequency counting, and **list comprehension** for concise list creation.|
| [AtCoder Beginner Contest 429 - problem_B](https://atcoder.jp/contests/abc429/tasks/abc429_b) | [atcoder3.ipynb - my_answer](https://github.com/iamthinking98-jpg/AtCoder/blob/main/atcoder3.ipynb) | Refactored an $O(N^2)$ solution to O(N) by pre-calculating the total sum outside the loop, avoiding repeated `sum()` calls within each iteration.|
| [AtCoder Beginner Contest 431 - problem_B](https://atcoder.jp/contests/abc431/tasks/abc431_b) | [atcoder4.ipynb - my_answer](https://github.com/iamthinking98-jpg/AtCoder/blob/main/atcoder4.ipynb) | Optimized performance by replacing O(N) list operations (like `in` and `remove`) with O(1) set operations.|
| [AtCoder Beginner Contest 432 - problem_B](https://atcoder.jp/contests/abc432/tasks/abc432_b) | [atcoder5.ipynb - my_answer](https://github.com/iamthinking98-jpg/AtCoder/blob/main/atcoder5.ipynb) |Confirmed that the str type supports direct indexing for character access (e.g., `s[i]`).　Reviewed basic techniques, such as swapping values within a list (e.g., `a[i]`, `a[j] = a[j]`, `a[i]`). |
| [AtCoder Beginner Contest 433 - problem_C](https://atcoder.jp/contests/abc433/tasks/abc433_c) | [atcoder6.ipynb - my_answer](https://github.com/iamthinking98-jpg/AtCoder/blob/main/atcoder6.ipynb) |Identified performance bottleneck in brute-force substring search. Nested loops with sorting resulted in $O(N^3)$ complexity, causing TLE. Need to refactor using linear scan approach.|
| [AtCoder Beginner Contest 434 - problem_B](https://atcoder.jp/contests/abc434/tasks/abc434_b) | [atcoder7.ipynb - my_answer](https://github.com/iamthinking98-jpg/AtCoder/blob/main/atcoder7.ipynb) |Initially achieved AC with an O(NM) brute-force approach (`solution_original.py`). I refactored it to an O(N+M) linear scan algorithm to optimize calculation time for larger inputs and to robustly handle potential zero division risks. |
| [AtCoder Beginner Contest 435 - problem_B](https://atcoder.jp/contests/abc435/tasks/abc435_b) | [atcoder8.ipynb - my_answer](https://github.com/iamthinking98-jpg/AtCoder/blob/main/atcoder8.ipynb) |The previous implementation calculated `sum(A[i:j+1])` from scratch in every iteration.I refactored the logic to update the total sum incrementally. This approach avoids unnecessary list copying and improves execution speed within the $O(N^3)$ constraints.|
| [AtCoder Beginner Contest 436 - problem_C](https://atcoder.jp/contests/abc436/tasks/abc436_c) | [atcoder9.ipynb - my_answer](https://github.com/iamthinking98-jpg/AtCoder/blob/main/atcoder9.ipynb) |In this version, I optimized the program by switching from a 2D list to ``set`` to manage coordinate data. This change significantly reduces memory usage and improves lookup efficiency when checking for used coordinates, making the logic more scalable for larger grids.|
| [AtCoder Beginner Contest 437 - problem_B](https://atcoder.jp/contests/abc437/tasks/abc437_b) | [atcoder_10.ipynb - my_answer](https://github.com/iamthinking98-jpg/AtCoder/blob/main/atcoder_10.ipynb) |I replaced nested loops with Python's set intersection (`&`) to find common elements. This change significantly reduces time complexity and makes the search logic more efficient.|
| [AtCoder Beginner Contest 438 - problem_C](https://atcoder.jp/contests/abc438/tasks/abc438_c) | [atcoder_11.ipynb - my_answer](https://github.com/iamthinking98-jpg/AtCoder/blob/main/atcoder_11.ipynb) |Optimized performance by replacing $O(N^2)$ simulation logic using list slicing with an O(N) stack-based linear scan.|
| [AtCoder Beginner Contest 440 - problem_C](https://atcoder.jp/contests/abc440/tasks/abc440_b) | [atcoder_12.ipynb - my_answer](https://github.com/iamthinking98-jpg/AtCoder/blob/main/atcoder_12.ipynb) |Replaced the dictionary with tuples for efficient default sorting and simplified output using unpacking.|




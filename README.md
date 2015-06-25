# Blue Puzzle

## 简介
这是一个简单的小游戏，非常容易上手，点击[这里](http://yexiaorain.github.io/webhek_puzzle/)开始吧！

### 看一个简单的截图吧！

![image](raw/puzzle_preview.png)


----

# Solver

Write by [YeXiaoRain](https://github.com/YeXiaoRain)

## Usage

**Step 1**

Use your favorite editor to open `solver.c`

Edit the GAMESIZE at line 2

```c
#define GAMESIZE 20
```

to the number you need to solve.

**Step 2**

compile it with `gcc -o solver solver.c`

**Step 3**

run it with `./solver`

## About Solver

For `n*n` Game

Time complexity is `O(n^2 * 2^n)`

Space complexity is `O(n^2)` which can reduce to `O(2*n)`

It cost `4.1s` to solve `20*20` puzzle and cost `3.9s` if caculating and checking last line at the same time.


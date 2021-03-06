### 1-1 Comparision of running times
***
For each function f(n) and time t in the following table, determine the largest size n of a problem that can be solved in time t, assuming that the algorithm to solve the problem takes f(n) microseconds.

|             | 1 second | 1 minute | 1 hour | 1 day | 1 month | 1 year | 1 century |
|:-----------:|:--------:|:--------:|:------:|:-----:|:-------:|:------:|:---------:|
|     lgn     |          |          |        |       |         |        |           |
|     √n      |          |          |        |       |         |        |           |
|      n      |          |          |        |       |         |        |           |
|    nlgn     |          |          |        |       |         |        |           |
|n<sup>2</sup>|          |          |        |       |         |        |           |
|n<sup>3</sup>|          |          |        |       |         |        |           |
|2<sup>n</sup>|          |          |        |       |         |        |           |
|     n!      |          |          |        |       |         |        |           |

### `Answer`
|             |    1 second   |     1 minute     |     1 hour    |      1 day     |      1 month     |       1 year      |      1 century      |
|:-----------:|:-------------:|:----------------:|:-------------:|:--------------:|:----------------:|:-----------------:|:-------------------:|
|     lgn     |     2<sup>10<sup>6</sup></sup>    |    2<sup>10<sup>6</sup></sup> * 60   | 2<sup>10<sup>6</sup></sup> * 3600 | 2<sup>10<sup>6</sup></sup> * 86400 | 2<sup>10<sup>6</sup></sup> * 2592000 | 2<sup>10<sup>6</sup></sup> * 31104000 | 2<sup>10<sup>6</sup></sup> * 3110400000 |
|     √n      | 1000000000000 | 3600000000000000 |   1.296E+019  |  7.46496E+021  |   6.718464E+024  |  9.67458816E+026  |   9.67458816E+030   |
|      n      |    1000000    |     60000000     |   3600000000  |   86400000000  |   2592000000000  |   31104000000000  |   3110400000000000  |
|    nlgn     |     62746     |      2801417     |   133378058   |   2755147513   |    71870856404   |    787089606198   |    67699498463641   |
|n<sup>2</sup>|      1000     |       7745       |     60000     |     293938     |      1609968     |      5577096      |       55770960      |
|n<sup>3</sup>|      100      |        391       |      1532     |      4420      |       13736      |       31448       |        145972       |
|2<sup>n</sup>|       19      |        25        |       31      |       36       |        41        |         44        |          51         |
|     n!      |       9       |        11        |       12      |       13       |        15        |         16        |          17         |

### 3-2 Relative asymptotic growths
***
Indicate, for each pair of expressions (A, B) in the table below, whether A is O, o, Ω, ω, or Θ of B. Assume that k ≥ 1, ϵ > 0, and c > 1 are constants. Your answer should be in the form of the table with "yes" or "no" written in each box.

|        A       |         B        |  O  |  o  |  Ω  |  ω  |  Θ  |
|:--------------:|:----------------:|:---:|:---:|:---:|:---:|:---:|
|lg<sup>k</sup> n|  n<sup>ϵ</sup>   |     |     |     |     |     |
|lg<sup>k</sup> n|  n<sup>ϵ</sup>   |     |     |     |     |     |
|       √n       |n<sup>sin  n</sup>|     |     |     |     |     |
|  2<sup>n</sup> | 2<sup>n/2</sup>  |     |     |     |     |     |
|2<sup>lgc</sup> | c<sup>lgn</sup>  |     |     |     |     |     |
|     lg(n!)     |lg(n<sup>n</sup>) |     |     |     |     |     |

### `Answer`
|        A       |         B        |  O  |  o  |  Ω  |  ω  |  Θ  |
|:--------------:|:----------------:|:---:|:---:|:---:|:---:|:---:|
|lg<sup>k</sup> n|  n<sup>ϵ</sup>   | yes | yes |  no |  no |  no |
|lg<sup>k</sup> n|  n<sup>ϵ</sup>   | yes |  no |  no |  no |  no |
|       √n       |n<sup>sin  n</sup>|  no |  no |  no |  no |  no |
|  2<sup>n</sup> | 2<sup>n/2</sup>  |  no |  no | yes | yes |  no |
|2<sup>lgc</sup> | c<sup>lgn</sup>  | yes |  no | yes |  no | yes |
|     lg(n!)     |lg(n<sup>n</sup>) | yes |  no | yes |  no | yes |

# 👿 Devil Principle Calculus 魔鬼法演算
The Devil Principle Calculus (魔鬼法演算)。魔鬼法，一时爽，最后火葬场。

## 起因

> 略

## 语法语义
Devil Principle Calculus 的基本语义和 Lambda Calculus 完全等同，但 Devil Principle Calculus 使用非常自然的中文，并且可以相当随意地掺杂跟程序无关的瞎扯淡。

### `lambda` 符号
“xxx 是魔鬼法” 或者 “xxx 是抄袭法” 或者 “xxx 是骗人的” => `\lambda xxx. _?_`
“xxx和yyy是魔鬼法” => `\lambda xxx yyy. _?_`，当然也可以可莉化

例如：Go是魔鬼法 => `\lambda Go. _?_`

### 表达式
“xxx 是魔鬼法”中的 `xxx` 出现在后文的句子中

例如：Go是魔鬼法，学Go的人其运必衰 => `\lambda Go. Go` (`id` 函数)

例如：Go是魔鬼法，Rust是魔鬼法，学Go和Rust的人其运必衰 => `\lambda Go. \lambda Rust. Go Rust`
> 单个表达式中出现多个词素，自动变成函数调用

例如：Go是魔鬼法，Rust是魔鬼法，学Go的人其运必衰 => `\lambda Go. \lambda Rust. Go` (`TRUE`)

### `TRUE` 和 `FALSE`
 - `TRUE`：真的/真理/正道
 - `FALSE`：假的/骗你的

例如：西医是魔鬼法，心理学也是魔鬼法，真以为西医和心理学能治病？假的，骗你的。

  => `\lambda 西医. \lambda 心理学. 西医 心理学 FALSE` (`and` 函数)

### 左右括号
一些固定的、没有什么道理的话。

左括号
  - 那些骗子吧，就希望，空手套白狼
  - 人家当魔鬼
  - 多思考啊
  - 量子计算机，要能成功，早成功了
  - 药不是医，要懂医理
  - 好啦，别迷信
  - 我乱说话，马上就要倒霉
  - 事情还没调查清楚，就开始吹了
  - 外国人的东西，各种坑
  - 许多人，都是吃了亏了，倒了霉了，才晓得听道理。

右括号
  - 不要被忽悠了
  - 你信，人家就说你傻了
  - 就是想不如意
  - AI就是忽悠
  - 无所谓啊，蠢货太多/懒货太多
  - 迷信是倒霉的根源
  - 现代社会，报应快得很
  - 现代社会，到处都是骗
  - 你看有谁免费给你讲道理？

例如：

西医就是魔鬼法，西药也是魔鬼法，癌症都是骗人的。研究西药的人走错了路。多思考啊，西医用西药治癌症，实际上治的是根本不存在的病。现代社会，到处都是骗。

=> `\lambda 西医. \lambda 西药. \lambda 癌症. 西药 (西医 西药 癌症)`

### 特殊菜单

“魔鬼法就是魔鬼法”和 Python 的 `import this` 有同样的效果，输出一个 Zen of Devil Principle，内容待定


## 实现

> 少女折寿中

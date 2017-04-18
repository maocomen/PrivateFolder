## typora 语法

### 1、行左边加分割线

* 效果

  ![7E95CF46-4696-439D-A296-9BEE861DB574](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_one.png?raw=true)

* 语法

  " > "后 enter 即可

* 代码示例

  ```
  > 生命，是如此的美好
  ```

### 2、有序列表

* 效果

  ![F40B7D75-CD0D-4600-8BD6-D5FEAE78997E](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_two.png?raw=true)

* 语法

  数字 + ‘ . ’ 然后 space 即可

* 代码示例

  ```
  10. 222
  ```

### 3、无序列表

* 效果

  ![9F2791A5-AC89-46EC-A174-364BD4DF0AD8](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_three.png?raw=true)

* 语法

  “ * ” 号后 space 即可

* 代码示例

  ```
  * 123
  ```

### 4、任务列表

* 效果

  ![CCAADA08-F43F-4F83-8355-61A31CE39F1A](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_four.png?raw=true)

* 语法

  “ - [ ] ”  未完成任务

  " - [x] "已完成的任务

* 代码示例

  ```
  - [ ] a task list item
  - [ ] list syntax required
  - [ ] normal **formatting**, @mentions, #1234 refs
  - [ ] incomplete
  - [x] completed
  ```

### 5、代码块

* 效果

  ![FE869765-EF82-4D00-8C2C-A2EC323C31BF](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_five.png?raw=true)

* 语法

  " ``` " 后加 代码语言类型，enter 即可(加了代码语言类型会代码高亮，不加语言类型不会代码高亮)

* 代码示例

  ```
  ​```ruby
  require 'redcarpet'
  markdown = Redcarpet.new("Hello World!")
  puts markdown.to_html
  ​```
  ```

### 6、数学计算区域

* 效果

  ![7D57375C-1A06-4FB3-A8FB-7D9DBC4006C1](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_six.png?raw=true)

* 语法

  "  $$ " 后加 enter 即可形成 数学计算 区域

* 代码示例

  ```
  $$
  \mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
  \mathbf{i} & \mathbf{j} & \mathbf{k} \\
  \frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
  \frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
  \end{vmatrix}
  $$
  ```

### 7、表格

* 效果

  ![0F5F4A8D-4610-4967-A744-752F792BA7AB](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_seven.png?raw=true)

* 语法

  列与列之间用“ | ”分割，

* 代码示例

  ```
  | Left-Aligned  | Center Aligned  | Right Aligned |
  | :------------ |:--------------: | ----: |
  | col 3 is      | some wordy text | $1600 |
  | col 2 is      | centered        |   $12 |
  | zebra stripes | are neat        |    $1 |
  ```

### 8、脚注

* 效果

  ![19B395E2-87FA-4239-A9B3-0FA613C7ED48](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_eight.png?raw=true)

* 语法

  ‘[^]’ 中写入要写的脚注，然后文末用 '[^]:' 填写描述即可

* 代码示例

  ```
  You can create footnotes like this[^footnote].

  [^footnote]: Here is the *text* of the **footnote**.
  ```

### 9、分割线

* 效果

  ![B6F2F86C-9DAB-4EEE-B957-E1A37D0FDAC1](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_nine.png?raw=true)

* 语法

  在段末用“ *** ” 或 “ — ” 可在该段下添加分割线

* 代码示例

  ```
  ***
  ---
  ```

### 10、YAML Front Matters（虽然我不知道啥意思）

* 效果

  ![C717C67F-4F6E-4EDF-B5C8-FD5223C41D74](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_ten.png?raw=true)

* 语法

  在文章开头写入 ‘ — ’ 即可

* 代码示例

  ```
  ---
  ```

### 11、Table of Contents (TOC)（目前并没有发现什么卵用）

* 效果

  ![A57396E8-AB7F-498D-89AB-5A9FA128F280](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_eleven.png?raw=true)

* 语法

  输入 ” [toc] “即可

* 代码示例

  ```
  [toc]
  ```

  ​

### 12、换行

* 效果

  ![49D50C11-DFD5-42D0-921B-8CE7C09E9032](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_twelve.png?raw=true)

* 语法

  键入 “  `< br/ >`” 标签即可换行，键入两个 space 再按 enter 也可换行

* 代码示例

  ```
  111 <br/> <br/> <br/>222
  111
    
      
      
  222
  ```


### 13、内联

* 我们可以在文本开头制作一个目录页，点击目录的某一项，可跳转到相应的正文

* 语法

  [ 目录 ] 后键入（#相应的正文标题）即可

* 代码示例

  ```
  [header](#header)
    "###header"(引号去掉)
  ```


### 14、URL链接

* 点击，跳转到相应的url链接处

* 语法

  [ title ] 后键入（url）即可

* 代码示例

  ```
  [跳转到百度](https://www.baidu.com)
  ```

### 15、图片展示

* 语法

  ![] 后加（），括号里填网络地址或本地地址即可

* 代码示例

  ```
  ![alt](http://i1.sanwen8.cn/doc/1609/852-160912105Q2I6.jpg)
  ![alt](path)
  ```

### 16、斜体 加粗

* 效果

  ![B577E1A7-85D4-45FE-AFFE-B0DDA2B779BA](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_sixteen.png?raw=true)

* 语法

  * 斜体：  stirng 前后 拼接 * 或者 _ 都可以使文字变成斜体
  * 加粗： stirng 前后 拼接 ** 或者 __ 都可以使文字变成粗体

* 代码示例

  ```
  string
  _string_ *string*
  __string__ **string**16、让代码显示在一个正常的段落
  ```

### 17、让代码显示在一个正常的段落

* 效果 

  ![CFE1112A-1873-4357-8709-F5B0447007CA](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_seventeen.png?raw=true)

* 语法

  代码 前后加`

* 代码示例

  ```
  `printf()`
  ```

### 18、加删除线

* 效果

  ![DC2305FA-3829-41FA-BCFC-6EDC95780AC6](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_eighteen.png?raw=true)

* 语法

  要加删除线的语句前后加~~.

* 代码示例

  ```
  I what to delete ~~this~~.
  ```

### 19、下划线

* 效果

  ![F58F6E44-4683-46C8-9598-8122F9C5706E](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_nineteen.png?raw=true)

* 语法

  要打下划线的语句前加 `<u>`，后面加 `</u>`。

* 代码示例

  ```
  <u>underline</u>
  ```

### 20、emoji

* 效果

  ![73FCD027-9D90-4030-978E-EB4A15FF9A9C](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_twenty.png?raw=true)

* 代码示例

  ```
  :smile
  ```

### 21、让数学计算式显示在一个正常的段落

* 效果

  ![813B02BF-718F-411D-A64D-7FC1B943A688](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_twentyOne.png?raw=true)

* 语法

  先打$，然后按ESC，即可预览输入数学计算式。

* 代码示例

  ```
  this is $\lim_{x \to \infty} \exp(-x) = 0$ result
  ```

### 22、下标

* 效果

  ![C8F2CE28-94AD-4424-A550-5382992CC387](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_twentyTwo.png?raw=true)

* 语法

  以上为例，2前后加~，如果下标需要空格，以\ 分割

* 代码示例

  ```
  H~2~O  X~long\ text~A
  ```

### 23、上标

* 效果

  ![6BF4DB2B-B96D-410E-B10C-9AB9EA70E935](https://github.com/maocomen/PrivateFolder/blob/master/typora语法/Images/typora_image_twentyThree.png?raw=true)

* 语法

  以上为例，2 前后加^

* 代码示例

  ```
  X^2^
  ```

### 24、高亮

* 效果

  ==highlight==

* 语法

  高亮字符串前后加==

* 代码示例

  ```
  ==highlight==
  ```

  ​

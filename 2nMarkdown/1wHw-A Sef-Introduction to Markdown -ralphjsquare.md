#A Sef-Introduction to Markdown 

##Start
Markdown is a mark-language, designed by John Gruber in 2004. Markdown allows its user to edit documents using pure text format that can be easily read and written, then to transfer them to HTML format. It was much inspired by pure text e-mail.

##Why Markdown?
Markdown enjoys its natural advantages, including:

* Light-weighted, cross-platform
* Simple grammar, easy reading and writing
* Clean, comformity presented
* Instant access to display
* Quick, convenient
* Interference-proof
* Highly-compatabile

##Core Features
* Usable for everyone
* Small learning cost
* High transfer efficiency

##Scenarios for Markdown
* Project documents
* Online forum
* Blog
* Personal Works
* Scientific Writing
* Self Publication

## Basic Grammar for Markdown

###Titile
Including six levels according to the number of the symbol "#"

For instance,
Level 6 title is displayed as
###### I'm the Title Level 6

###Emphasis
Strong using "**" or "__"
Emphasize ussing "*" or "_"

For example,
**I am Strong**
and
_I was emphasized_

###List
* **Unordered List**

      Start with "*","-","+"
* **Ordered List**

      Start with "1."

For instance,

- 南京
+ 北京
+ 中山陵


1.  定陵
2.  妞
3.  雷雷雷

###Quotation

Start with ">", like

>This is a quotation, XD

###Blockquotes
This is where codes can be put in. Use "`" or "```", such as,

```
def list_function(x):
      x(1)=x(1)+3
      return x

n= [a, b, c]
print list_function(n)
```
代码行 `print
list_function(n)`

###Seperator
Use "***", "* * *", "*****", "---", or "___", like,

While
***
Where is the so-called seperator?
******
Here we are!
_________

###Link

1. Basic Mode:" [Link Name] (Link)"
2. * Referecen Link: "[Link Name][ID]". * At the end of the article: [ID]:link
3. Automated Link:<link>

For example,

1. [Who's your daddy?](Blizzard.com)

2. [I'm the Bug][Tim Hardaway]
[Tim Hardaway]: www.nytimes.com/timhardawaythebug

3. Sorry for party rock<LFMAO.COM>

##Advanced Grammar

###Sheet

"|Title |Title 1|Title 2|Title 3|
|---|---|---|---|
|A|B|C|D|"

Usually, the normal sheet is comprised of the symbols "|" and "-".
In Line 2, a successive series of "-" (at least 3 "-" form a seperator.

For instance,

|Province |ZJ 浙江省|FJ 福建省|YN 云南省|
|---|:-----|:-----|:-----|
|省会|杭州|厦门|昆明|
|人口|....|,,,,|....|

Let's try another one,

| Tables | Are | Cool|
|------|:----:|---:|
| col 3 is| right-alighned | $1600 |
| col 2 is| centred          |     $12|
| zebra stripes| are neat |       $1|

Well, looking good but where is the border?


###Picture

####Basic grammar for adding pictures:

`"![Pic name](Pic link)"`

or

`"![Pic](http://i,imgur.com/UKhrRrK.jpg)"`

Shall be displayed like:

"![Pic name](Pic link)"

or

"![Pic](http://i,imgur.com/UKhrRrK.jpg)"

` #those are what I called "null"`

####Some Grammer about Picture Location

`<center>
  ![Pic name](Pic link)
</center>`

like,

<center>
  ![Pic name](Pic link)
</center>

and,

`<figure>
  <img src="http://xxx.jpg">
</figure>`

like ,

<figure>
 <img src="http://cdn.sspai.com/attachment/thumbnail/2014/04/15/0135456d6a3c1051f0ed54e37cef070010f78_mw_800_wm_1_wmp_3.jpg">
</figure>

`#Ah, seems great`

##Others

###Shortcuts
This chapter seems not suitable for my current Markdown Applications. Maybe it can be fixed till I change it to the Macdown I think. Gotta try.

###Scientific Writing

I'll just copy tryping those in the spreadout and see what's going on.

`I am lazy.XD`


#### Mathematical  Formulae `$y = x^2$`  `"The formula didn't fit"`

Inline Math: `$\dfrac{\tfrac{1}{2}[1-(\tfrac{1}{2})^n]}{1-\trac{1}{2}} = s_n$`  .  `"that didn't fit, either"`

Math block:

```math
\oint_C x^3\, dx + 4y^2\, dy
`"totally fxxxed up"`
`Let's end here. The reason why those formulae did not come up is probably that I do not load all those formulae basis on my Mac.`
```

###Slides
Using [Remarkjs](https://github.com/gnab/remark), a opensource JavaScript library.

`But I didn't know how to use it, lol`


## Chinese Wrting Style 中文写作风格

### 空格

1. 中英文之间加空格；
2. 中文与数字之间加空格；
3. 数字与单位之间加空格（气温、百分比计量单位等除外）；
4. 全角标点（中文输入下的都好、句号、冒号、顿号等）与其他字符之间不空格；
5. 英文内容，输入逗号和句号后添加一个半角空格；
6. 段首不留空格。

###  符号

1. 中文货中英文混排中，用中文／全角标点；
2. 数字、英文用半角字符；
3. 出现整句英文， 该句用英文／半角标点；
4. 中文使用直角引号。直角引号。规则是先单后双；
5. 不重复使用标点符号；
6. 省略号：”……“。 不要以”。。。”等符号组合代替省略号。

### 拼写

1. 专有名词大小写使用；
2. 缩写要准确， 使用公认用法；
3. 长数字的输入， 从小数点开始向左， 每三位为一组， 组间空格。

`This is basically my homework.`

`End.`




         
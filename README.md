README SYNTAX LEARNING
==========
The aim of writing this log is to practice what I have learned from:<br>
https://github.com/guodongxiaren/README
****

|Author|Tianglong Zhang|
|---|---|
|E-mail|958879855@qq.com|

![picture1](http://www.5068.com/uploads/allimg/171125/1-1G125100937.jpg)

## *OUTLINE*
* [**Line**](#line)
* [**Title**](#title)
* [**Text**](#text)
* [**Picture**](#picture)
* [**Links**](#links)
* [**List**](#list)
* [**Quotation**](#quotation)
* [**Code**](#code)
* [**Table**](#table)
* [**Emotion**](#emotion)

### *Line*
**********
There are many ways to create a line in README.md, and let us have a look!<br>
We can insert "------" into a new line in this file, as follows.It is  the same to use  "*****" and "______".

-------------------
___________________
*******************

### *Title*
***********
Transform a word into title using "============="
===========================
Transform a word into title using "-------------"
---------------------------
# Transform a word into title using "#"
## Transform a word into title using "##", and you can add more "#".

### *Text*
*****
Add a "Tab" at the beginning of one line, and you can transform it into text formatting. Just as follows.

	I have add a "Tab" before this sentence.
	You can continue to write here.
What is more. We can use \``` \```.
```
I have add ``` at the beginning of lastrow.
I have add ``` at the beginning of nextrow.
```
We can also chage fonts, and just follow this table:

|Syntax|Performance|
|----|-----|
|`*Italic1*`|*Italic1*|
|`_Italic2_`| _Italic2_|
|`**Bold1**`|**Bold1**|
|`__Bold2__`|__Bold2__|
|`This is ~~Strikethrough~~`|This is ~~Strikethrough~~|

We can combine two or three of them when using.

### *Picture*
*****
We can add a picture into our log using:\![picture name](URL of the picture)<br>
Just like `![sky](http://p3.gexing.com/G1/M00/25/2E/rBACE1b_F9PSVH2VAACkQ3N6d8Y647_600x.jpg "The Beautifual Sky!")`<br>

![picture2](http://img.zcool.cn/community/014cca554bfd99000001bf7289bb04.jpg "The Beautifual Sky!")

Now, we add a GIF from our own repository using: `![picture3](https://github.com/zhangtianlong-git/Gitskills/blob/master/03847e558aa91dca801219c77870fcf.gif)`

![picture3](https://github.com/zhangtianlong-git/Gitskills/blob/master/03847e558aa91dca801219c77870fcf.gif)<br>
Add a JPG from our another repository using: `![picture4](https://github.com/zhangtianlong-git/test-repository/blob/master/sky.jpg)`.<br>
![picture4](https://github.com/zhangtianlong-git/test-repository/blob/master/sky.jpg)

### *links*
*****
We can link to `www.baidu.com` using: `[Baidu](http://www.baidu.com)`<br>
[Baidu_link](https://www.baidu.com/)<br>
We can link to any title in this log using: `[Go to the link](#title name)`.--tip: write name in lowercase!<br>
[return to the top](#readme)

### *List*
*****
We may create a list using: `* name` , `- name` and `Tab (*or-) name`.Just as shown below.
* name1
- name2
* name3
	* name4
		* name5
			* name6
			
We can also replace (\*or-) by `n.`.
1. name1
2. name2
3. name3
	1. name4
		1. name5
			1. name6
			
A check box can be created using: `- [ ] name` or `- [x] name`.
- [x] name1
- [x] name2
- [ ] name3
- [ ] name4

### *Quotation*
*****
We can add `>`,`>>`,`>>>` and so on at the beginning of one line.
>one `>`
>>two `>`
>>>three `>`

### *Code*
*****
FIirst line: ` ```programming language, just like (```python)`. Last line: ` ``` `.
```python
def add(a,b):
	return a+b
```

### *Table*
*****
A table can be created like this:<br>
```
|     name1     |     name2     |     name3     |
|:--------------|:-------------:|--------------:|
| left justified | align center | right justified |
```

|     name1     |     name2     |     name3     |
|:--------------|:-------------:|--------------:|
| left justified | align center | right justified |

### *Emotion*
*****
We can use `:blush:` to show :blush:, and it is really easy.
At last, a tip may be added.

	```diff
	+ 鸟宿池边树，僧敲月下门
	- 鸟宿池边树，僧推月下门
	```

```diff
+ 鸟宿池边树，僧敲月下门
- 鸟宿池边树，僧推月下门
```

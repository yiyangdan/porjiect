---
title: markdown test
top: ture
tags:
- 语法
- 测试
---
语法测试

![美女](https://cdn.hk01.com/di/media/images/2483737/org/35495152b2de6f9bb2f02950960b0d5b.jpg/zztfYcgmsnDWXrM15yuh2M2rmverVDBz-5PgivuT4Io?v=w1920r16_9 "哈喽")
<!--more-->
### 关于努力的名言
> 为了曾经的一己执念，风雨兼程只顾心中的你。  

停止奋斗，生命也就停止了。——卡莱尔    
聪明出于勤奋，天才在于积累。——华罗庚   
业精于勤而荒于嬉，行成于思而毁于随。——韩愈  
无论做什么事情，只要肯努力奋斗，是没有不成功的。——牛顿  
正确的道路是这样：吸取你的前辈所做的一切，然后再往前走。——列夫·托尔斯泰   
在这个并非尽善尽美的世界上，勤奋会得到报偿，而游手好闲则要受到惩罚。——毛姆  
  - #### 自由
  - #### 民主
  - #### 富强
  - #### 爱国
  ### 生活，从💗开始  
1. #### 真爱  
2. #### 财富  

[**My Github**](https://github.com/yiyangdan)

**加粗**  
*斜体*    
<p align='left'><font face='华文楷体' color="red" size='6'>字体，颜色和字号</font></p>

<center><font face='华文楷体' color="green" size='6'>字体，颜色和字号</font></center>  

<p align='right'><font face='华文楷体' color="blue" size='6'>字体，颜色和字号</font></p>  

[![视频](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQBJ22BlP9YqLQtH8zNmwAwZxUl8WO7IqIhwHhJeZSNGE6jXDXi)](https://www.bilibili.com/video/av53851218?from=search&seid=16331857946256767181 "猛男&新宝岛")

<center><font face='华文楷体' color="green" size='8'>Marxico官网实例</font></center>  

# Welcome to Marxico

@(Sample notebook)[Marxico|Manual|Markdown]

**Marxico** is a delicate Markdown editor for Evernote. With reliable storage and sync powered by Evernote, **Marxico** offers greate writing experience.

- **Versatile** - supporting code highlight, *LaTeX* & flow charts,  inserting images & attachments by all means.
- **Exquisite** -  neat but powerful editor, featuring offline docs, live preview, and offering the [desktop client][1] and offline [Chrome App][2].
- **Sophisticated** - deeply integrated with Evernote, supporting notebook & tags, two-way bind editing.   

----------

[TOC]

## Introducing Markdown

> Markdown is a plain text formatting syntax designed to be converted to HTML. Markdown is popularly used as format for readme files, ... or in text editors for the quick creation of rich text documents.  - [Wikipedia](http://en.wikipedia.org/wiki/Markdown)

As showed in this manual, it uses hash(#) to identify headings, emphasizes some text to be **bold** or *italic*. You can insert a [link](http://www.example.com) , or a footnote[^demo]. Serveral advanced syntax are listed below, please press `Ctrl + /` to view Markdown cheatsheet.

### Code block
``` python
@requires_authorization
def somefunc(param1='', param2=0):
    '''A docstring'''
    if param1 > param2: # interesting
        print 'Greater'
    return (param2 - param1 + 1) or None
class SomeClass:
    pass
>>> message = '''interpreter
... prompt'''
```

### LaTeX expression
$$	x = \dfrac{-b \pm \sqrt{b^2 - 4ac}}{2a} $$

### Table
| Item      |    Value | Qty  |
| :-------- | --------:| :--: |
| Computer  | 1600 USD |  5   |
| Phone     |   12 USD |  12  |
| Pipe      |    1 USD | 234  |

### Diagrams
#### Flow charts
```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```
#### Sequence diagrams
```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```

> **Note:** You can find more information:

> - about **Sequence diagrams** syntax [here][3],
> - about **Flow charts** syntax [here][4].

### Checkbox
You can use `- [ ]` and `- [x]` to create checkboxes, for example:

- [x] Item1
- [ ] Item2
- [ ] Item3

> **Note:** Currently it is only partially supported. You can't toggle checkboxes in Evernote. You can only modify the Markdown in Marxico to do that. Next version will fix this.  


### Dancing with Evernote

#### Notebook & Tags
**Marxico** add `@(Notebook)[tag1|tag2|tag3]` syntax to select notebook and set tags for the note. After typing `@(`, the notebook list would appear, please select one from it.  

#### Title
**Marxico** would adopt the first heading encountered as the note title. For example, in this manual the first line `Welcome to Marxico` is the title.

#### Quick Editing
Note saved by **Marxico** in Evernote would have a red ribbon button on the top-right corner. Click it and it would bring you back to **Marxico** to edit the note.

> **Note:** Currently **Marxico** is unable to detect and merge any modifications in Evernote by user. Please go back to **Marxico** to edit.

#### Data Synchronization
While saving rich HTML content in Evernote, **Marxico** puts the Markdown text in a hidden area of the note, which makes it possible to get the original text in **Marxico** and edit it again. This is a really brilliant design because:

- it is beyond just one-way exporting HTML which other services do;
- and it avoids privacy and security problems caused by storing content in a intermediate server.

> **Privacy Statement: All of your notes data are saved in Evernote. Marxico doesn't save any of them.**

#### Offline Storage
**Marxico** stores your unsynchronized content locally in browser storage, so no worries about network and broswer crash. It also keeps the recent file list you've edited in `Document Management(Ctrl + O)`.

> **Note:** Although browser storage is reliable in the most time, Evernote is born to do that. So please sync the document regularly while writing.

## Shortcuts
Help    `Ctrl + /`
Sync Doc    `Ctrl + S`
Create Doc    `Ctrl + Alt + N`
Maximize Editor    `Ctrl + Enter`
Preview Doc `Ctrl + Alt + Enter`
Doc Management    `Ctrl + O`
Menu    `Ctrl + M`

Bold    `Ctrl + B`
Insert Image    `Ctrl + G`
Insert Link    `Ctrl + L`
Convert Heading    `Ctrl + H`

## About Pro
**Marixo** offers a free trial of 10 days. After that, you need to [purchase](http://marxi.co/purchase.html) the Pro service. Otherwise, you would not be able to sync new notes. Previous notes can be edited and synced all the time.

## Credits
**Marxico** was first built upon [Dillinger][5], and the newest version is almost based on the awesome [StackEdit][6]. Acknowledgments to them and other incredible open source projects!

## Feedback & Bug Report
- Twitter: [@gock2][7]
- Email: <hustgock@gmail.com>

----------
Thank you for reading this manual. Now please press `Ctrl + M` and click `Link with Evernote`. Enjoy your **Marxico** journey!


[^demo]: This is a demo footnote. Read the [MultiMarkdown Syntax Guide](https://github.com/fletcher/MultiMarkdown/wiki/MultiMarkdown-Syntax-Guide#footnotes) to learn more. Note that Evernote disables ID attributes in its notes , so `footnote` and `TOC` are not actually working.

  [1]: http://marxi.co/client_en
  [2]: https://chrome.google.com/webstore/detail/kidnkfckhbdkfgbicccmdggmpgogehop
  [3]: http://bramp.github.io/js-sequence-diagrams/
  [4]: http://adrai.github.io/flowchart.js/
  [5]: http://dillinger.io
  [6]: http://stackedit.io
  [7]: https://twitter.com/gock2

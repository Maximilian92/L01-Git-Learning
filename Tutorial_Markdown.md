# **[- Preface -]**
**In VSCode:**\
\
Ctrl + Shift + p, type in "Markdown" -> Check relevant command\
Ctrl + k, v -> Open preview to the side\
Ctrl + Shift + v -> Open preview\
\
Download Extension "Markdown PDF" to export .md file as .pdf\
\
Enter, Space, Space -> Line break\
"\\" at the end of the current line -> Line break (Attention: "\\" also works as escape character)\
"\<br>" at the start of the next line -> Line break

<br>

# **[- Main Text -]**

<br>

## **1. Heading**

<br>

# 1st-level heading
## 2nd-level heading
### 3rd-level heading
#### 4rd-level heading
##### 5rd-level heading
###### 6rd-level heading

<br>

## **2. Font**

<br>

*Italic*\
**Bold**\
***Italic & Bold***\
~~Strikethrough~~

<br>

## **3. Reference**

<br>

> 1st-level reference
>> 2nd-level reference

<br>

## **4. Line**

<br>

---

Method1

---

<br>

***

Method2

***

<br>

## **5. Links**

<br>

![Picture](https://github.com/Maximilian92/L01-Git-learning/blob/master/image/Picture.png)

[link to google](http://google.com/)

<br>

## **6. List**

<br>

+ Method1 
   + Option1
      + Variable1
- Method2
* Method3

<br>

## **7. Table** 

<br>

Person1|Person2|Person3
:--|:--:|--:
Tony|Steve|Thor
Suit|Shield|Hammer

<br>

## **8. Code** 

<br>

Code line: `print("Hello world!")`

Code block: 
```
def greeting():
    print("Hello world!")
```

<br>

## **9. Flow diagram** 

<br>

```flow
st=>start: Start
op=>operation: Operation
cond=>condition: Y / N?
e=>end
st->op->cond
cond(Y)->e
cond(Y)->op
```
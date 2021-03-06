Markdown : Basic Syntax
==========================
# 1. What is Markdown?
## ๐ก Markdown
[**Markdown**](https://www.markdownguide.org/getting-started/)์ ํ์คํธ ๊ธฐ๋ฐ์ ๋งํฌ์ ์ธ์ด ์๋๋ค. HTML๋ก ๋ณํ์ด ๊ฐ๋ฅํ๋ฉฐ ํน์๊ธฐํธ์ ๋ฌธ์๋ฅผ ์ด์ฉํ์ฌ ๊ฐ๋จํ๊ณ  ๋น ๋ฅด๊ฒ ์ง๊ด์ ์ธ ์ปจํ์ธ ๋ฅผ ๋ง๋ค ์ ์์ต๋๋ค. ์์ฆ ๋ธ๋ก๊ทธ ํํ์ ์ปค๋ฎค๋ํฐ(notion, velog ๋ฑ)์์๋ ๋งํฌ๋ค์ด์ ๋ง์ด ํ์ฉํ๊ณ  ์๋ ๊ฒ๋ ๋งํฌ๋ค์ด์ด ์ผ๋ง๋ ์ ์ฉํ์ง ๋ณด์ฌ์ค๋๋ค.

### ๐ Wiki says,
๋งํฌ๋ค์ด(markdown)์ ์ผ๋ฐ ํ์คํธ ๋ฌธ์์ ์์์ ํธ์งํ๋ ๋ฌธ๋ฒ์ด๋ค. README ํ์ผ์ด๋ ์จ๋ผ์ธ ๋ฌธ์, ํน์ ์ผ๋ฐ ํ์คํธ ํธ์ง๊ธฐ๋ก ๋ฌธ์ ์์์ ํธ์งํ  ๋ ์ฐ์ธ๋ค. ๋งํฌ๋ค์ด์ ์ด์ฉํด ์์ฑ๋ ๋ฌธ์๋ ์ฝ๊ฒ HTML ๋ฑ ๋ค๋ฅธ ๋ฌธ์ํํ๋ก ๋ณํ์ด ๊ฐ๋ฅํ๋ค.
***

> **Pros**
>- ๊ฐ๊ฒฐํ๋ค
>- ๋ณ๋์ ๋๊ตฌ์์ด ์ฌ์ฉ ๊ฐ๋ฅ(์์ฑ ๊ฐ๋ฅ)
>- ๋ค์ํ ํํ๋ก์ ๋ณํ ๊ฐ๋ฅ (ex. HTML)
>- ํ์คํธ ํํ๋ก ์ ์ฅ๋์ด ์ฉ๋์ด ์ ๊ณ  ๋ณด๊ด์ด ์ฉ์ด

>**Cons**
>- ํ์ค์ด ์์ด ๋๊ตฌ์ ๋ฐ๋ผ ๋ณํ ๋ฐฉ์ ์ ๊ฐ๊ธฐ
>- ๋ชจ๋  HTML, ๋งํฌ์์ ๋์ฒดํ์ง๋ ๋ชปํ๋ค
---
---
## 1๏ธโฃ Headings (a.k.a Headers)
ํค๋๋ฅผ ๋ง๋ค๊ธฐ ์ํด์๋ ์ฐ๊ณ ์ ํ๋ ๊ตฌ๋ฌธ ๋๋ ๋จ์ด ์์ (#)์ ๋ถ์ด๋ฉด ๋๋ค. ์ด๋, (#)๊ณผ ํด๋น ๊ตฌ๋ฌธ ๋๋ ๋จ์ด ์ฌ์ด์ ๋์ด์ฐ๊ธฐ ํ๋ ๊ฒ์ ์์ด์๋ ์๋๋ค.
***
* ํฐ์ ๋ชฉ: ๋ฌธ์ ์ ๋ชฉ
    ```
    This is an H1
    =============
    ```
    This is an H1
    =============

* ์์์ ๋ชฉ: ๋ฌธ์ ๋ถ์ ๋ชฉ
    ```
    This is an H2
    -------------
    ```
    This is an H2
    -------------
***
|Markdown|Header|
|------|----------|
|# Heading level 1| ํฐ ์ ๋ชฉ : ๋ฌธ์ ์ ๋ชฉ|
|## Heading level 2| ์์ ์ ๋ชฉ : ๋ฌธ์ ๋ถ์ ๋ชฉ|
|### Heading level 3| ๊ธ๋จธ๋ฆฌ(1)|
|#### Heading level 4| ๊ธ๋จธ๋ฆฌ(2)|
|##### Heading level 5| ๊ธ๋จธ๋ฆฌ(3)|
|###### Heading level 6| ๊ธ๋จธ๋ฆฌ(4)|

<br>
[Example] 
<br>

# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
####### This is a 7 (์ง์ํ์ง ์๋๋ค)

---
---
## 2๏ธโฃ Paragraphs
๋ฌธ๋จ์ ๋ง๋ค๊ธฐ ์ํด์๋ ๊ทธ๋ฅ ์ฐ๋๋๋ก ์ฐ๋ฉด ๋๋ค. ์ค ๋ฐ๊พธ๊ณ  ์ถ์ผ๋ฉด ์ค์์ ๋๋์์ค..

## 3๏ธโฃ Line Breaks
\<br>์ break์ ์ฝ์๋ก ์ฝ๋ฉ ์ new line๊ณผ ์ ์ฌํ ๊ธฐ๋ฅ์ด๋ผ๊ณ  ์๊ฐํ๋ฉด ๋๋ค.
```
This is the first line<br>And this is the second line
```
This is the first line <br> And this is the second line

---
---

## 4๏ธโฃ Emphasis
> **Bold**
> <br>
> ๊ฐ์กฐ ๋ณผ๋ ์ฒ๋ฆฌ. ๋ณผ๋ ์ฒ๋ฆฌํ๊ณ  ์ถ์ ๋จ์ด ์ ๋ค๋ก (**) ๋๋ (__)๋ฅผ ๋ถ์ฌ์ค๋ค
> <br><br>
> *Italic*
> <br>
> ๊ธฐ์ธ์ฌ ์ฐ๊ธฐ. ์๋ค๋ก (*)๋ฅผ ๋ถ์ฌ์ฃผ๊ฑฐ๋ (_)๋ฅผ ๋ถ์ฌ์ค๋ค.
> <br><br>
> ***Bold and Italic***
> ๋ณผ๋ ์ฒ๋ฆฌ์ ๊ธฐ์ธ์ฌ์ฐ๊ธฐ๋ฅผ ๋ชจ๋ ํ๊ณ  ์ถ์ ๋์๋ (***) ๋๋ (___)๋ฅผ ๋ถ์ฌ์ค๋ค.


[Example]
```
๋ฐ์ ๋๊ฐ ๋์๋ ๊ผญ **๋ง์คํฌ**๋ฅผ ์จ์ผ ํ๋ค
์ง์ ๋ค์ด์ค๋ฉด ๊ผญ *์์ ๋ฆ์*์ผ ํ๋ค
***์ฌํ์  ๊ฑฐ๋ฆฌ๋๊ธฐ*** ๋ฐ๋์ ์ง์ผ์ผ ํฉ๋๋ค.
```
๋ฐ์ ๋๊ฐ ๋์๋ ๊ผญ **๋ง์คํฌ**๋ฅผ ์จ์ผ ํ๋ค
<br>
์ง์ ๋ค์ด์ค๋ฉด ๊ผญ *์์ ๋ฆ์*์ผ ํ๋ค
<br>
***์ฌํ์  ๊ฑฐ๋ฆฌ๋๊ธฐ*** ๋ฐ๋์ ์ง์ผ์ผ ํฉ๋๋ค.

---
```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
++underline++
~~cancelline~~
```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
++underline++
~~cancelline~~


---
---

## 5๏ธโฃ Blockquotes
์ด๋ฉ์ผ์์ ์ฌ์ฉํ๋ ```>``` ๋ธ๋ญ์ธ์ฉ๋ฌธ์๋ฅผ ์ด์ฉํ๋ค.
```
> This is a blockqute.
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.

Blockquote ์์์๋ ๋ค๋ฅธ ๋งํฌ๋ค์ด ์์๋ฅผ ํฌํจํ  ์ ์๋ค.

> ### This is a H3
> * List
>	```
>	code
>	```

---
---
## 6๏ธโฃ Lists
์์๊ฐ ์๋ ๋ชฉ๋ก๊ณผ ์์๊ฐ ์๋ ๋ชฉ๋ก์ ๋ง๋ค์ด๋ผ ์ ์๋ค.
### โ Ordered Lists
์์์๋ ๋ชฉ๋ก์ ์ซ์์ ์ ์ ์ฌ์ฉํ๋ค.
```
1. ์ฒซ๋ฒ์งธ
2. ๋๋ฒ์งธ
3. ์ธ๋ฒ์งธ
```
1. ์ฒซ๋ฒ์งธ
2. ๋๋ฒ์งธ
3. ์ธ๋ฒ์งธ

์ซ์๋ค์ ์์ฐจ์ ์ผ ํ์๋ ์์ผ๋, ์ฒซ๋ฒ์งธ ์ซ์๋ ํญ์ 1๋ก ์์ํด์ผ ํ๋ค.
```
1. ์ฒซ๋ฒ์งธ
3. ์ธ๋ฒ์งธ
2. ๋๋ฒ์งธ
```
1. ์ฒซ๋ฒ์งธ
3. ์ธ๋ฒ์งธ
2. ๋๋ฒ์งธ

### โ Unordered Lists
(-), (*), (+) ์ ๋ชฉ๋ก ์์ ๋ฃ์ด์ฃผ๋ฉด ๋๋ค. ๋ค์ฌ์ฐ๊ธฐ๋ฅผ ์ํ๋ฉด indent๋ฅผ ์ฌ์ฉํ๋ฉด ๋๋ค.
```
* First
  * Second
    * Third

+ First
  + Second
    + Third

- First
  - Second
    - Third
```

ํผํฉํด์ ์ฌ์ฉํ๋ ๊ฒ๋ ๊ฐ๋ฅ
```
* 1๋จ๊ณ
    - 2๋จ๊ณ
    	+ 3๋จ๊ณ
            = 4๋จ๊ณ
```

* 1๋จ๊ณ
    - 2๋จ๊ณ
    	+ 3๋จ๊ณ
			= 4๋จ๊ณ


---
---
## 7๏ธโฃ Code
- ```<pre><code></code></pre>``` : 4๊ฐ์ ๊ณต๋ฐฑ ๋๋ ํ๋์ ํญ์ผ๋ก ๋ค์ฌ์ฐ๊ธฐ๋ฅผ ๋ง๋๋ฉด ๋ณํ๋๊ธฐ ์์ํ์ฌ ๋ค์ฌ์ฐ์ง ์์ ํ์ ๋ง๋ ๋๊น์ง
- (```)๋ฅผ ์ฐ๋ฉด codeblock์ ์์ ๋ง๋ค์ด๋ผ ์ ์์ด ๋ฌธ๋ฒ๊ฐ์กฐ๊ฐ ๊ฐ๋ฅํ๋ค
- (`)backticks๋ก ๊ฐ์ผ ๋ถ๋ถ๋ง ์ฝ๋๋ก ๋ํ๋ผ ์๋ ์๋ค๋ค

[Example]

ํ์ค ๋์ด์ฐ๋ฉด ์ธ์์ด ์ ๋๋ก ์๋๋ ๋ฌธ์ ๊ฐ ๋ฐ์ํ๊ณค ํฉ๋๋ค.

```
This is a normal paragraph:

    This is a code block.
end code block.
```

<code>
```
This is a normal paragraph:
    This is a code block.
end code block.
```
</code>

์ค์ ๋ก ์ ์ฉํด๋ณด๋ฉด,
This is a normal paragraph:

    This is a code block.
end code block.

---
---

## 8๏ธโฃ Horizontal Rules (์ํ์ )
์ํ์ ์ ๋ง๋ค๊ธฐ ์ํด์๋ ๋ชจ๋ 3๊ฐ์ฉ ์ฐ๋ฉด ๋๋ค. (***) ๋๋ (---) ๋๋ (___). ๋ณดํต ํ์ด์ง๋ฅผ ๋๋๊ธฐ ์ํด์ ๋ง์ด ์ฌ์ฉํ๋ค.
```
***
---
___

* * *

***

*****

- - -

---------------------------------------
```
์๋ฌด๋ฆฌ ๊ฐ์๋ฅผ ๋ง์ด ์น๋ค๊ณ  ํ๋๋ผ๋ 3๊ฐ ์ด์์ด๋ฉด ๋ค ๋๊ฐ์ด rendered
* * *

***

*****

- - -

---------------------------------------
<br>
---
---
---


## 9๏ธโฃ Links
[ ] ์์ ๋งํฌ๋ฅผ ์ฐ๊ฒฐํ  ํ์คํธ๋ฅผ ๋ฃ๊ณ  ๋ฐ๋ก ๊ทธ ๋ค์ ( ) ๋งํฌ๋ฅผ ๋ฃ์ด์ค๋ค.

[Example]
```
์ฝ๋ฉ ๋ชจ๋ฅผ ๋๋ [๊ตฌ๊ธ๋ง](https://google.com)์ด์ง
```
์ฝ๋ฉ ๋ชจ๋ฅผ ๋๋ [๊ตฌ๊ธ๋ง](htps://google.com)์ด์ง

---

* Adding Titles

```
[link keyword][id]
[id]: URL "Optional Title here"

Link: [Google][googlelink]
[googlelink]: https://google.com "Go google"
```

Link: [Google][googlelink]
[googlelink]: https://google.com "Go google"

  
```
syntax: [Title](link)
```
Link: [Google](https://google.com, "google link")

---

* URLs and Email Addresses
```
<http://example.com/>
<address@example.com>
```

<http://example.com/>
<address@example.com>

---
---

## ๐ Images
```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
```
![๊ฒจ์ธ ์ ์ญ์ค๋ํ๊ต](https://scatch.ssu.ac.kr/wp-content/uploads/sites/5/2021/02/%EA%B9%80%ED%98%95%EB%AA%A83_2020%EC%88%AD%EC%8B%A4%EC%9D%98%EA%B2%A8%EC%9A%B8.jpg)
![์ญ๋๊ฒฝ์๊ด](https://scatch.ssu.ac.kr/wp-content/uploads/sites/5/2021/02/%EC%B5%9C%EC%9B%90%EC%9A%B05_%EB%B0%A4%EC%9D%98-%EA%B2%BD%EC%83%81%EA%B4%80.jpg "Soongsil Business")

์ฌ์ด์ฆ ์กฐ์  ๊ธฐ๋ฅ์ ์๊ธฐ ๋๋ฌธ์ ```<img width="" height=""></img>```๋ฅผ ์ด์ฉํ๋ค.

---
---

## โฐ Escaping Characters
๋งํฌ๋ค์ด์์ ์ฌ์ฉํ๋ ๋จ์ด๋ค์ ์ฌ์ฉํ๊ณ ์ ํ  ๋ (\ )๋ฅผ ์ฌ์ฉํ์ฌ ํ์ถํ๋ค.
```
\*Without the backlash, this would be a bullet in an unordered list
```

\* Without the backlash, this would be a bullet in an unordered list
|Character|Name|
|--------|----------|
\ | backslash
` | backtick
\* | asterik
_ | underscore
{} | curly braces
[] | brackets
<> | angle brackets
() | parentheses
\# | pound sign
\- | minus sign(hyphen)
! | exclamation mark
\| | pipe

## ๐พ GFM Summary in github
[Github LINK](https://github.com/jykim701/SE_assignment1)

## Hello this is modification for assignment2
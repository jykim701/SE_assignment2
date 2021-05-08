Markdown : Basic Syntax
==========================
# 1. What is Markdown?
## 💡 Markdown
[**Markdown**](https://www.markdownguide.org/getting-started/)은 텍스트 기반의 마크업 언어 입니다. HTML로 변환이 가능하며 특수기호와 문자를 이용하여 간단하고 빠르게 직관적인 컨텐츠를 만들 수 있습니다. 요즘 블로그 형태의 커뮤니티(notion, velog 등)에서도 마크다운을 많이 활용하고 있는 것도 마크다운이 얼마나 유용한지 보여줍니다.

### 📖 Wiki says,
마크다운(markdown)은 일반 텍스트 문서의 양식을 편집하는 문법이다. README 파일이나 온라인 문서, 혹은 일반 텍스트 편집기로 문서 양식을 편집할 때 쓰인다. 마크다운을 이용해 작성된 문서는 쉽게 HTML 등 다른 문서형태로 변환이 가능하다.
***

> **Pros**
>- 간결하다
>- 별도의 도구없이 사용 가능(작성 가능)
>- 다양한 형태로의 변환 가능 (ex. HTML)
>- 텍스트 형태로 저장되어 용량이 적고 보관이 용이

>**Cons**
>- 표준이 없어 도구에 따라 변환 방식 제각기
>- 모든 HTML, 마크업을 대체하지는 못한다
---
---
## 1️⃣ Headings (a.k.a Headers)
헤더를 만들기 위해서는 쓰고자 하는 구문 또는 단어 앞에 (#)을 붙이면 된다. 이때, (#)과 해당 구문 또는 단어 사이에 띄어쓰기 하는 것을 잊어서는 안된다.
***
* 큰제목: 문서 제목
    ```
    This is an H1
    =============
    ```
    This is an H1
    =============

* 작은제목: 문서 부제목
    ```
    This is an H2
    -------------
    ```
    This is an H2
    -------------
***
|Markdown|Header|
|------|----------|
|# Heading level 1| 큰 제목 : 문서 제목|
|## Heading level 2| 작은 제목 : 문서 부제목|
|### Heading level 3| 글머리(1)|
|#### Heading level 4| 글머리(2)|
|##### Heading level 5| 글머리(3)|
|###### Heading level 6| 글머리(4)|

<br>
[Example] 
<br>

# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
####### This is a 7 (지원하지 않는다)

---
---
## 2️⃣ Paragraphs
문단을 만들기 위해서는 그냥 쓰던대로 쓰면 된다. 줄 바꾸고 싶으면 줄에서 나누시오..

## 3️⃣ Line Breaks
\<br>은 break의 약자로 코딩 시 new line과 유사한 기능이라고 생각하면 된다.
```
This is the first line<br>And this is the second line
```
This is the first line <br> And this is the second line

---
---

## 4️⃣ Emphasis
> **Bold**
> <br>
> 강조 볼드 처리. 볼드 처리하고 싶은 단어 앞 뒤로 (**) 또는 (__)를 붙여준다
> <br><br>
> *Italic*
> <br>
> 기울여 쓰기. 앞뒤로 (*)를 붙여주거나 (_)를 붙여준다.
> <br><br>
> ***Bold and Italic***
> 볼드 처리와 기울여쓰기를 모두 하고 싶을 때에는 (***) 또는 (___)를 붙여준다.


[Example]
```
밖에 나갈 때에는 꼭 **마스크**를 써야 한다
집에 들어오면 꼭 *손을 닦아*야 한다
***사회적 거리두기*** 반드시 지켜야 합니다.
```
밖에 나갈 때에는 꼭 **마스크**를 써야 한다
<br>
집에 들어오면 꼭 *손을 닦아*야 한다
<br>
***사회적 거리두기*** 반드시 지켜야 합니다.

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

## 5️⃣ Blockquotes
이메일에서 사용하는 ```>``` 블럭인용문자를 이용한다.
```
> This is a blockqute.
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.

Blockquote 안에서는 다른 마크다운 요소를 포함할 수 있다.

> ### This is a H3
> * List
>	```
>	code
>	```

---
---
## 6️⃣ Lists
순서가 있는 목록과 순서가 없는 목록을 만들어낼 수 있다.
### ● Ordered Lists
순서있는 목록은 숫자와 점을 사용한다.
```
1. 첫번째
2. 두번째
3. 세번째
```
1. 첫번째
2. 두번째
3. 세번째

숫자들은 순차적일 필요는 없으나, 첫번째 숫자는 항상 1로 시작해야 한다.
```
1. 첫번째
3. 세번째
2. 두번째
```
1. 첫번째
3. 세번째
2. 두번째

### ● Unordered Lists
(-), (*), (+) 을 목록 앞에 넣어주면 된다. 들여쓰기를 원하면 indent를 사용하면 된다.
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

혼합해서 사용하는 것도 가능
```
* 1단계
    - 2단계
    	+ 3단계
            = 4단계
```

* 1단계
    - 2단계
    	+ 3단계
			= 4단계


---
---
## 7️⃣ Code
- ```<pre><code></code></pre>``` : 4개의 공백 또는 하나의 탭으로 들여쓰기를 만나면 변환되기 시작하여 들여쓰지 않은 행을 만날때까지
- (```)를 쓰면 codeblock을 아예 만들어낼 수 있어 문법강조가 가능하다
- (`)backticks로 감싼 부분만 코드로 나타낼 수도 있다다

[Example]

한줄 띄어쓰면 인식이 제대로 안되는 문제가 발생하곤 합니다.

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

실제로 적용해보면,
This is a normal paragraph:

    This is a code block.
end code block.

---
---

## 8️⃣ Horizontal Rules (수평선)
수평선을 만들기 위해서는 모두 3개씩 쓰면 된다. (***) 또는 (---) 또는 (___). 보통 페이지를 나누기 위해서 많이 사용한다.
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
아무리 개수를 많이 친다고 하더라도 3개 이상이면 다 똑같이 rendered
* * *

***

*****

- - -

---------------------------------------
<br>
---
---
---


## 9️⃣ Links
[ ] 안에 링크를 연결할 텍스트를 넣고 바로 그 뒤에 ( ) 링크를 넣어준다.

[Example]
```
코딩 모를 때는 [구글링](https://google.com)이지
```
코딩 모를 때는 [구글링](htps://google.com)이지

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

## 🔟 Images
```
![Alt text](/path/to/img.jpg)
![Alt text](/path/to/img.jpg "Optional title")
```
![겨울 속 숭실대학교](https://scatch.ssu.ac.kr/wp-content/uploads/sites/5/2021/02/%EA%B9%80%ED%98%95%EB%AA%A83_2020%EC%88%AD%EC%8B%A4%EC%9D%98%EA%B2%A8%EC%9A%B8.jpg)
![숭덕경상관](https://scatch.ssu.ac.kr/wp-content/uploads/sites/5/2021/02/%EC%B5%9C%EC%9B%90%EC%9A%B05_%EB%B0%A4%EC%9D%98-%EA%B2%BD%EC%83%81%EA%B4%80.jpg "Soongsil Business")

사이즈 조절 기능은 없기 때문에 ```<img width="" height=""></img>```를 이용한다.

---
---

## ➰ Escaping Characters
마크다운에서 사용하는 단어들을 사용하고자 할 때 (\ )를 사용하여 탈출한다.
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

## 👾 GFM Summary in github
[Github LINK](https://github.com/jykim701/SE_assignment1)
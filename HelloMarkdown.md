# **Markdown** 기본 문법

# Markdown?
* 텍스트 기반의 가벼운 마크업(markup) 언어 
* 문서의 구조를 나타내기 위한 (간단한) 언어

## 1. 제목 나타내기

`# 글자` 의 형태로 작성하며, #1~#6 순으로 작아짐


예시)
## 제목 2
### 제목 3
##### 제목 5

```
## 제목2
### 제목 3
##### 제목5
```

---

## 2. 리스트

* **순서가 있는** 리스트

`1.` `2.` `3.` 으로 리스트 표현

예시)
1. 1월 1일
2. 1월 2일
3. 1월 3일
```
1. 1월 1일
2. 1월 2일
3. 1월 3일
```

* **순서가 없는** 리스트

`*` 또는 `-` 로 리스트 표현

예시)
* 2월 1일
* 2월 2일
* 2월 3일
```
* 2월 1일
* 2월 2일
* 2월 3일
```


# 3. 코드블럭

* 코드를 표현하기 위해 `backtick`을 한번 사용

예시)

`인라인 코드블럭`


* 소스 코드를 첨부하고 싶으면 backtick을 세번 넣음

예시) 

```
print("hello World") 
```
* 만약 어떤 언어인지 표현하고 싶다면, 해당 내용을 앞에 추가

예시)

Python
``` Python
Print("Hello world")
```
Markdown
```MD
# 제목 1
- 순서
- 없는
- 목록
```

# 4. 링크
```
[String](url)
```
[String]이 보여지는 부분, ()는 url

예시)

- [구글](https://www.google.com/)
- [네이버](https://www.naver.com/)
- [노션](https://notion.so/)
- [깃헙](https://github.com/)
- [팽지우](https://www.notion.so/hg-edu/8de7d8640dfc4ef9939a8b39b968b88e)

```
 [구글](https://www.google.com/)
- [네이버](https://www.naver.com/)
- [노션](https://notion.so/)
- [깃헙](https://github.com/)
- [팽지우](https://www.notion.so/hg-edu/8de7d8640dfc4ef9939a8b39b968b88e)
```

# 5. 이미지
```
![String](img_url)
```
[String]은 이미지 설명

 * 

예시)

![github 로고](github_logo.png)

```
![github 로고](images/github_logo.png)
```

* 이미지 하위 폴더에 존재할 경우 `/` 이용해 경로 추가

예시)

![cat](images/cccccat.jpg)

```
![cat](images/cccccat.jpg)
```

# 6. 텍스트 강조

* **굵은 글씨**

예시)

** 여러분 **
```
** 여러분 **
```

* *기울인 글씨*

예시)

*점심 식사*
```
*점심 식사*
```

* ~~취소선 글씨

예시)

~~배고파요~~
```
~~배고파요~~
```

# 7. 수평선

`---` 또는 `***`, `___` (underbar)

예시)

---
삼성 청년 SW 아카데미
***

```
---
삼성 청년 SW 아카데미
***
```

---
# 특수기호 부르는 법

```
"-" : 하이픈 (대시)
"/" : 슬래시
"*" : asterisk (별, star)
"`" : backtick
"\" : backslash
```
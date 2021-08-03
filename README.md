# 제목(Header)

# 제목 1
## 제목 2
### 제목 3

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)
<!-- 띄어쓰기 두번 or br태그 -->
동해물과 백두산이 마르고 닳도록<br>
하느님이 보우하사 우리나라 만세  
무궁화 삼천리

# 강조(Emphasis)
<!-- _문장_ (이텔릭) **문장** (굵게) 
    ~~문장~~ (취소선)-->
_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)
<!-- <a href="https://google.com">GOOGLE</a> -->
[GOOGLE](https://google.com)

<!-- <a href="https://google.com" title="google로 이동!">GOOGLE</a> -->
[GOOGLE](https://google.com "google로 이동")

<!-- target은 원시 html로 -->
<a href="https://google.com" title="google로 이동!"
target="_blank">GOOGLE</a>

# 이미지(Images)
![]()
<!-- 링크와 이미지의 차이는 코드 맨앞 ! 의 유무 -->
![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)
](https://heropy.blog/css/images/logo.png)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> 네이버 국어사전

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문


# 인라인(inline) 코드 강조

CSS에서 `background` 혹은  
`background-image` 속성으로..

# 블록(block) 코드 강조

```html
<a href="https://google.com" title="google로 이동!">GOOGLE</a>
```

```css
h1 {
  color: red;
}
```

``` javascript 
function name() {
  var a = 'aaa';
  return a;
}
```

# 표(table)

position 속성
<!-- ' :--: // 가운데정렬 ' , '--: // 오른쪽정렬' -->
값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)

동해물과 <u>백두산이</u> 마르고 닳도록<br>
하느님이 보우하사 <span style="text-decoration: underline">우리나라</span> 만세
<a href="https://google.com" title="google로 이동!"
target="_blank">GOOGLE</a>

<img width="70" src="https://heropy.blog/css/images/logo.png"
alt="heropy">

# 수평선(Horizontal Rule)

---
***
___
<hr>

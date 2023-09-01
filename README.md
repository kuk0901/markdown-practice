# 제목(Header)

# 제목 1

## 제목 2

### 제목 3

#### 제목 4

##### 제목 5

###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks): 띄어쓰기 2번 or br태그

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이텔릭_ : 언더바 2개 이텔릭체(기울기)  
**두껍게** : 에스터리스크 2개로 앞/뒤 감싸기  
**_이텔릭 + 두껍게_** : 기울기 + 두껍게  
~~취소선~~ : 틸드 2개로 앞/뒤 감싸기  
<u>밑줄</u> : 마크다운에서 밑줄 기능 X, HTML의 u태그로 감싸기

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록

<!-- ol태그와 같은 기능, 숫자 1과 .으로 만듦 -->

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록

<!-- 목록 안에서 공백 4개(띄어쓰기 4번) 후 같은 방식 작성 시 내부 목록 추가 가능 -->

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

<!-- 하이픈 기호 사용시 순서 없는 목록 생성 가능 -->

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

<!-- 목록 안에서 공백 4개(띄어쓰기 4번) 후 같은 방식 작성 시 내부 목록 추가 가능 -->

# 링크(Links)

[]()

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="네이버로 이동!">NAVER</a>

[NAVER](https://naver.com "네이버로 이동!")

<a href="https://naver.com" title="네이버로 이동!" target="_blank">NAVER</a>

# 이미지(Images): 맨 앞에 느낌표 차이

![]()

![HEROPY](https://heropy.blog/css/images/logo.png)

<!-- 이미지 -->

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog)

<!-- 삽입한 이미지에 링크 추가 -->

# 인용문(BlockQuote) : 꺽쇠 괄호 + 띄어쓰기

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

<!-- 인용문 -->

> 인용문을 작성하세요!
>
> > 중첩된 인용문
> >
> > > 중중첩된 인용문 1
> > > 중중첩된 인용문 2
> > > 중중첩된 인용문 3

<!-- 인용문 중첩법 -->

# 인라인(Inline) 코드 강조 :

css에서 `background` 혹은
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

<!-- 백틱 기호로 감싸기, 문장 긁어서 백틱 기호 사용시 자동으로 생성 -->

# 블록(block) 코드 강조

```html
<a href="https://google.com" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = "AAA";
  return a;
}
```

```bash
$ git commit -m 'study Markdown'
```

<!-- $은 터미널에 입력하라는 뜻 -->

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

| 값       |       의미        | 기본값 |
| -------- | :---------------: | -----: |
| static   |     기준 없음     |      O |
| relative |     요소 자신     |      X |
| absolute | 위치 상 부모 요소 |      X |
| fixed    |      뷰포트       |      X |

<!-- > --|--|-- < 머리열과 몸통열 구분, 행의 수만큼 하이픈 2개를 버티컬바로 구분
  : 콜론 기호로 정렬 가능 :x: = 가운데 정렬 / x: = 오른쪽 정렬 / 왼쪽 정렬이 기본값 -->

# 원시 HTML(Raw HTML): 마크다운 문법 안에서 HTML 문법 사용

동해물과 <span style="text-decoration: underline;">백두산이</span> 마르고 닳도록<br>
하느님이 보우하사 <u>우리나라</u> 만세

<a href="https://naver.com" title="네이버로 이동!" target="_blank">NAVER</a>

---

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY">

# 수평선 (Horizontal Rule)

---

---

---

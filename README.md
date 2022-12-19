<!-- github에서 README란 이름의 markdown 파일을 찾도록 설정되어 있음.
따라서, README로 이름 설정을 권장 -->



# 제목(Header)  <!-- # 제목 = HTML <h> 태그 -->

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6



# 문장(Paragraph) <!-- 문장 = HTML <p> 태그 -->

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세



# 줄바꿈(Line Breaks) <!-- 띄어쓰기 두번 또는 <br/> = 줄바꿈 되는 영역 -->

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세<br/>
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세



# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u> 



# 목록(List)
<!-- 숫자.내용 = HTML <ol> 태그 -->
<!-- - 내용 = 순서가 필요하지 않은 목록 -->

1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록 <!--Sub 목록 = 들여쓰기 두번 -->
    2. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록 <!--Sub 목록 = 들여쓰기 두번 -->
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록



# 링크(Links) <!-- [대체 텍스트](링크) -->

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동")

<a href="https://naver.com" title="NAVER로 이동" target="_blank">NAVER</a>  <!-- 새 탭에 열기 -->



# 이미지(Images)  <!-- ![대체 텍스트](링크) -->

![DEVYUNG](https://lh3.googleusercontent.com/ogw/AOh-ky2BiG9VUqGlXEgRe5wCJxzXsh8g8QcaOV4a8YGm=s32-c-mo)

<!-- 이미지를 클릭하면 링크(https://blog.naver.com/devyung)로 이동 -->
[![DEVYUNG](https://lh3.googleusercontent.com/ogw/AOh-ky2BiG9VUqGlXEgRe5wCJxzXsh8g8QcaOV4a8YGm=s32-c-mo)](https://blog.naver.com/devyung)



# 인용문(BlockQuote)  <!-- >띄어쓰기 -->

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중첩된 인용문 1  
>>> 중첩된 인용문 2  
>>> 중첩된 인용문 3



# 인라인(inline) 코드 강조  <!-- `` -->

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.



# 블록(block) 코드 강조 <!-- ```사용언어 작성할 코드 내용 ``` -->

```html
<a href="https://google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absoulte;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

<!-- 텍스트 블록 코드 강조 -->
```plaintext
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세
```



# 표(Table)
<!-- --|--|--를 사용해 표의 머리글과 내용을 구분 -->
<!-- :--: = 가운데 정렬 -->
<!-- --: = 오른쪽 정렬 -->

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absoulte | 위치 상 부모 요소 | X
fixed | 뷰포트 | X



# 원시 HTML(Raw HTML)
<!-- Markdown은 브라우저에서 출력이 되어야 하기 때문에 HTML로 변환됨.
그러나 브라우저가 제공하는 환경에 따라 정상적으로 출력되지 않을 가능성도 존재.
띠리서, HTML로 변환되기 전에 'Markdown 문법 내부에서 HTML 문법 사용'(원시 HTML). -->

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
<u>하느님</u>이 보우하사 우리나라 만세

<a href="https://naver.com" title="NAVER로 이동" target="_blank">NAVER</a>

<img width="70" src="https://lh3.googleusercontent.com/ogw/AOh-ky2BiG9VUqGlXEgRe5wCJxzXsh8g8QcaOV4a8YGm=s32-c-mo" alt="DEVYUNG" />



# 수평선(Horizontal Rule)

---

***

___


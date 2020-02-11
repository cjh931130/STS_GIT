# 마크다운 문서
    1. 장점
        - 간편하고 쉽다
        - 다양한 플랫폼에서 지원
    2. 단점
        - 표준이 없다.(표현 매체마다 다르게 보임)
        - 모든 HTML를 대체하진 못한다.

---

# 제목1
## 제목2
### 제목3
#### 제목4

# 수평선(Horizontal line)
각 기호를 3개 이상 입력

---

***
___


# 줄바꿈(line break)
'두번 띄어쓰기' 나 `<br>`로 사용하면 된다

동해물과 백두산이
마르고 닳도록 
하느님이 보우하사
우리나라 만세

동해물과 백두산이
마르고 닳도록 <br>
하느님이 보우하사
우리나라 만세

# 이탤릭, 굵게

이탤릭은 *별표* 사용 혹은 _언더바_사용
**이탤릭 굵게**<br>
~~취소선~~<br>
<u>밑줄</u>은 `<u></u>` 사용


# 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록
        - 순서가 필요하지 않은 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록


# 링크
[GOOGLE](https://google.com)

[GitHub](https://github.com)


# 이미지
![대체텍스트](https://www.w3schools.com/html/pic_trulli.jpg)


[![대체텍스트](https://www.w3schools.com/html/pic_trulli.jpg)](https://www.naver.com)


# 코드강조

### 인라인 코드 강조
    `background`혹은 `background-image` 속성으로 배경이미지 삽입

### 블럭 코드 강조
`를 3번 이상 입력하고 코드 종류도 적습니다.

```html
<a href="https://www.naver.com" target="_black">네이버</a>
```


```css
.list li {
    position : absolute;
    top : 40px;
}
```

```java
    public static void myFunc(int n, String str) {
        System.out.println("Hello World");
    }
```


# 표(테이블)
`<table>`로 변환


|aa|bb|
|--|--|
|1|2|
|3|4|

### 열병합

|Col1|Col2|Col3|Col4|
|----|----|----|----|
|No span|spanf    |||
<br>

|값|의미|기본값|
|---|:---:|---:|
|static|배치 불가|999|
|static|배치 불|9999|
|static|배치 불가임|99999|



# 인용문

> 남의 말이나 글에서 직접 따온 문장 

> 인용문 작성
>> 중첩 인용문
>>> 중중첩 인용문


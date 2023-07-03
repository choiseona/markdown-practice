# markdown-practice

# 1. text 입력하기   
text만 입력하면 줄을 바꾸고 싶은데 엔터를 눌러도 줄바꿈이 되지 않아요. 스페이스를 3번 누르면      
줄바꿈이 됩니다.

# 2. 제목
제목을 입력할 때는 '#'을 이용해서 강조해줍니다.
# 첫 번째로 큰 크기
## 두 번째로 큰 크기
### 세 번째로 큰 크기
#### 네 번째로 큰 크기
##### 다섯 번째로 큰 크기
###### 여섯 번째로 큰 크기

# 3. BlockQuote
> This is a BlockQuote
>   > This is a BlockQuote
>   >  >This is a BlockQuote

BlockQuote 안에서는 마크다운 요소를 포함할 수 있습니다.
> # This is a h3
> * star

# 4.목록
### - 순서 있는 목록(번호 목록) 
1. 첫 번째
2. 두 번째
3. 세 번째

   
번호 목록은 무조건 내림차순, 내용은 차순 안바뀜
1. 첫 번째
2. 세 번째
3. 두 번째

### - 순서 없는 목록(*, +, - 들여쓰기 순서대로 검정 동그라미, 빈 동그라미, 검정 네모)
  * 빨강
    * 녹색
      * 파랑

  + 빨강
    + 녹색
      + 파랑
     
  - 빨강
    - 녹색
      - 파랑
     
*, +, -를 혼합해서 사용하는 것도 가능하다   
* 1단계
  - 2단계
    + 3단계
      + 4단계

# 5. 코드
### 들여쓰기
4개의 공백으로 들여쓰기를 만나면 실질적인 들여쓰기로 변환되며 들여쓰지 않은 행을 만날때까지 변환된다.   
무조건 줄바꿈 해야 들여쓰기 적용됨(공백 3개가 아닌 그냥 enter 하기)   
   
This is a normal paragrah:

    (4개 공백 들여쓰기)I pressed tab key.
end code block.

### 코드블럭
코드블럭은 2가지 방식을 사용할 수 있음
1. pre tag와 code tag로 감싸주는 방식
<pre>
  <code>
    console.log("코드블럭")
  </code>
</pre>

2. 코드블럭코드(```) 을 이용하는방법
   
깃허브에서는 코드블럭코드(```) 시작점에 사용하는 언어를 선언하여 문법강조(Syntax highlighting)이 가능하다. 
```javascript
console.log("코드블럭코드);
```

# 6. 수평선
* * *
***
*****
- - -
--------------------------

# 7. 강조
*single asterisks*   
_single underscores_   
**double asterisks**   
__double underscores__   
~~cancelline~~   











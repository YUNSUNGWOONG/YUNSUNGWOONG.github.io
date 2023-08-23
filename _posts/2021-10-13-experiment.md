---
layout: single
title:  "실험실페이지"
author: cotes
date: 2019-08-09 20:55:00 +0800
categories: [getting started]
typora-root-url: ../
tag: markdown
toc: true
author_profile: false
sidebar: 
    nav: "docs"
search: false
---



# Notices: 블럭 속의 텍스트에 대해 관심을 불러일으킵니다.
**[공지사항]**[지킬블로그 신규 업데이트 안내 드립니다. default](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/){: .notice}   
<br>

**[공지사항]**[지킬블로그 신규 업데이트 안내 드립니다. primary](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/){: .notice--primary}   
<br>

**[공지사항]**[지킬블로그 신규 업데이트 안내 드립니다. info](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/){: .notice--info}   
<br>

**[공지사항]**[지킬블로그 신규 업데이트 안내 드립니다. default](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/){: .notice--warning}  
<br>

**[공지사항]**[지킬블로그 신규 업데이트 안내 드립니다. info](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/){: .notice--success}   
<br>

**[공지사항]**[지킬블로그 신규 업데이트 안내 드립니다. info](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/){: .notice--danger}   
<br>

<div class="notice">
공지사항입니다. - default
<ul>
    <li>김밥</li>
    <li>떡볶이</li>
    <li>순대</li>
</ul>
</div>

<div class="notice--primary">
공지사항입니다. - primary
<ul>
    <li>참깨라면</li>
    <li>짜빠구리</li>
    <li>신라면</li>
</ul>
<ol>
    <li>이불개기</li>
    <li>청소하기</li>
    <li>아침먹기</li>
</ol>
</div>

<div class="notice--info">
공지사항입니다. - info
<ul>
    <li>유즈카페</li>
    <li>커피특별시</li>
    <li>키아누카페</li>
</ul>
</div>

<div class="notice--warning">
공지사항입니다. - warning
<ul>
    <li>수소</li>
    <li>헬륨</li>
    <li>리튬</li>
</ul>
</div>

<div class="notice--success">
공지사항입니다. - success
<ul>
    <li>아메리카노</li>
    <li>미숫가루</li>
    <li>라임티</li>
</ul>
</div>

<div class="notice--danger">
공지사항입니다. - danger
<ul>
    <li>돈코츠라멘</li>
    <li>미소라멘</li>
    <li>열라면</li>
</ul>
</div>

[토스 기술 블로그, 토스 테크](https://toss.tech/){: .btn .btn--danger}

[직방 기술 블로그](https://medium.com/zigbang){: .btn .btn--primary .btn--x-large}


# '-': unordered list

- content-(1)
- content-(2) 
- content-(3)



# 'n': ordered list

1. content-(1)
2. content-(2)
3. content-(3)





# emoji (이모지 적용 안됨, 해결책 찾을 것)

:o::o2::ocean::octopus::oden::office::oil_drum::ok::ambulance::baby_chick:

:dagger::qatar::alembic::rabbit::e-mail::first_quarter_moon::eagle:





# image

![9901B0445BBD8A9924](/images/2021-10-13-experiment/9901B0445BBD8A9924.png)



# 유튜브 동영상
{% include video id="q0P3TSoVNDM" provider="youtube" %}

# quote(인용문)

```
> 이건 인용문이에요.
  >> 이건 인용문 속 인용문이에요.
```


```python
# x, y, z 변수에 값 1, 2, 3을 각각 저장
x, y, z = 1, 2, 3
print(x, y, z)
```

    1 2 3



# h1

## h2

### h3

#### h4

##### h5

###### h6



```python
# Python program to find H.C.F of two numbers

# define a function
def compute_hcf(x, y):

# choose the smaller number
    if x > y:
        smaller = y
    else:
        smaller = x
    for i in range(1, smaller+1):
        if((x % i == 0) and (y % i == 0)):
            hcf = i 
    return hcf

num1 = 54 
num2 = 24

print("The H.C.F. is", compute_hcf(num1, num2))
```

```markdown
코드를 감쌀 경우 백틱을 써서 감쌉니다.
```

```python
# Python Program to find the L.C.M. of two input number

def compute_lcm(x, y):

   # choose the greater number
   if x > y:
       greater = x
   else:
       greater = y

   while(True):
       if((greater % x == 0) and (greater % y == 0)):
           lcm = greater
           break
       greater += 1

   return lcm

num1 = 54
num2 = 24

print("The L.C.M. is", compute_lcm(num1, num2))
```



- Category: 포스팅의 주제에 대한 분류
- Tag: 포스팅에서 사용한 언어에 대한 분류(사용한 언어가 없을 경우, CS라고 분류)

> <만약 여러 언어를 태깅할 경우>
>
> python과 c/cpp를 태깅할 경우:
>
> tags: [python, c/cpp]





> 인용문을 사용할 경우, 단축키 [ctrl + shift + Q]를 입력합니다.
>



저의 블로그 링크입니다.

[네이버블로그(yhon89)](https://blog.naver.com/yhon89)

[네이버블로그(yhon89e)](https://blog.naver.com/yhon89e)

[티스토리블로그(#파이썬)](https://jack-channel-python.tistory.com/)

[Velog블로그(#C-series)](https://velog.io/@2170004487z)

[Blex블로그(#CS지식)](https://blex.me/@2170004487z)

[Steemit블로그(#경제#경영#정책)](https://steemit.com/@yunsungwoong)





<cite>Steve Jobs</cite> --- Apple Worldwide Developers' Conference, 1997
{: .small}

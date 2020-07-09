---
layout: posts
date: 2020-07-09 23:32:00+0900
title: "개발 블로그 테스트"
category: 
    - test
    - cate
tags:
    - test
    - markdown
---

[![대체 텍스트](https://img1.daumcdn.net/thumb/R720x0.q80/?scode=mtistory2&fname=http%3A%2F%2Fcfile22.uf.tistory.com%2Fimage%2F230D484956E2DA60176CC3 "링크 설명")](https://img1.daumcdn.net/thumb/R720x0.q80/?scode=mtistory2&fname=http%3A%2F%2Fcfile22.uf.tistory.com%2Fimage%2F230D484956E2DA60176CC3)   

1\. 개소리 목록
* 냐엉 일반
* **_이텔릭_ 볼드** 이텔릭 + 볼드 혼용 
    * _이텔릭_ 
        * __볼드__
---        
2\. 개소리 목록
* ~~취소줄~~
    * <u>밑줄</u>  
        * `강조`
***
* 코드 블럭 테스트
    * java
    * html
    * css
    * javascript
    * bash
    * python
___    
인용문(blockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK!

> 인용문을 작성하세요!
>> 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
>>> 중중첩된 인용문 1  
>>> 중중첩된 인용문 2  
>>> 중중첩된 인용문 3

```java
@SpringBootApplication
@EnableConfigServer
public class ConfigServerApplication {

    public static void main(String[] args) {
        SpringApplication.run(ConfigServerApplication.class, args);
    }

}
```

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
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
$ vim ./~zshrc
```

```python
s = "Python syntax highlighting"
print s
```

'테이블'

값 | 의미 | 기본값
---|:---:|---:
`static` | 유형(기준) 없음 / 배치 불가능 | `static`
`relative` | 요소 **자신**을 기준으로 배치 |
`absolute` | 위치 상 **_부모_(조상)요소**를 기준으로 배치 |
`fixed` | **브라우저 창**을 기준으로 배치 |
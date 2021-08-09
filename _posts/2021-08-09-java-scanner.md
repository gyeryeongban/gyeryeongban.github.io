---
defaults:
  # _posts
  - scope:
      path: ""
      type: posts
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: true
      share: true
      related: true

      title: [Java] Scanner
      layout: category
      permalink: /categories/java/
      taxonomy: java
---

## 오늘의 개념 정리 [Scanner]

### What's scanner?

> - 객체를 만들기 위한 클래스
> - 정수, 실수, 문자 입력 가능
> - 편한 예외 처리와 수행 속도 때문에 많이 사용

### How to use

```
import java.util.Scanner;

public class 파일 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
    }
}
```

### Types of method

```
nextLine() // 공백 포함 Enter 치기 전까지 변환
           // ex) What's up? → What's up?
```

```
next() // 공백 앞까지 변환
       // ex) What's up? → What's
```

```
nextInt() // 정수형으로 변환
```

```
nextFloat() // 실수형으로 변환
```

```
nextDouble() // 더 큰 범위의 실수형으로 변환
```

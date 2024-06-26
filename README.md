# 수업 내용 필기

수업내용 필기를 위한 마크다운(Markdown)을 작성하는 방법 연습

## 랜덤(Random)

랜덤은 뭐가 나올지 예측이 불가능한 값을 말한다.   
랜덤을 만드는 방법은 여러가지가 있다.
1. Random이라는 도구를 생성해 사용
2. Math.random() 명령을 사용
3. SecureRandom 도구를 생성해 사용

Random 도구 생성 방법
```java
Random r = new Random();
```

이 도구를 사용하기 위해서는 import가 필요

```java
import java.util.Random;
```
import는 직접 작성하지 않고 **단축키** 'ctrl+shift+o'를 누른다.

## 랜덤 정수 추첨

생성한 도구를 이용해 랜덤한 정수 추첨
단, 생성을 위해서는 범위를 정해야 함
- 사람은 범위를 이야기할 때 `a`부터 `b`까지 라고합니다.
- 자바는 범위를 이야기할 때 `a`부터 `b`개라고 합니다.

주요 랜덤 값들의 범위는 다음과 같이 표현될 수 있다.
| 항목 | 범위 |
| :---: | --- |
| 주사위 | `1`부터 `6`개 |
| 로또 | `1`부터 `45`개 |
| 두자리 정수 | `10`부터 `90`개 |

난수 생성의 원리가 궁금하면 [위키백과](https://ko.wikipedia.org/wiki/%EB%B6%84%EB%A5%98:%EB%82%9C%EC%88%98)에서 확인할수 있다
![카지노](https://github.com/jh011228/note/assets/170493602/4f53e7fe-bb1a-4b4d-9ed0-4c0099c7893a)

![빠이빠이](https://github.com/jh011228/note/assets/170493602/aea93c16-7c2b-4336-aa30-9ad034711e3e)


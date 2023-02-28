# bbpie 
깃허브 사용법입니다.
---
##아래는 마크다운 문법 사용법.
***
1. 안녕하세요.
2. 이주엽입니다.
3. 목록만들기

- +,-,*기호 아무거나 붙이면 됩니다.
- 이주엽입니다.
- 순서 없는 목록만들기

* 안녕하세요.
* 이주엽입니다.
  + 들여쓰기
    + 들여쓰기1
---
**텍스트 강조**하기

_텍스트 기울_ 이기

~~취소선~~ 보이기
---
**소스코드 삽입하기**
- 소스코드를 삽입하려면 backquote(`)키를 사용
1. 한 줄 소스 코드
`function add(x,y){return x+y}`
2. 여러 줄 소스코드
```java
String answer = "";
        HashMap<String, Integer> map = new HashMap<>();
        for(String key : participant){
            map.put(key,map.getOrDefault(key,0)+1);
        }
```        

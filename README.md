## ThreadLocal
쓰레드 로컬은 해당 쓰레드만 접근할 수 있는 특별한 저장소를 말한다.

```java
private ThreadLocal<String> nameStore = new ThreadLocal<>();
```


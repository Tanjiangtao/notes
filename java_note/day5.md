### 循环嵌套
> 注意： 在写循环嵌套时，要尽量保证外层的循环次数小于内层的循环次数
- [√] 对 
```java
for(int i=0; i<20; i++){
    for(int j=0; j<900; j++){
    System.out.println(i);
    }
}
```
- [ x ]  错 
```java
for(int i=0; i<900; i++){
    for(int j=0; j<20; j++){
    System.out.println(i);
    }
}
```


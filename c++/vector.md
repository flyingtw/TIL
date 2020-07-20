# vector 문법

*#include<algorithm>*





### sort

벡터 원소 정렬

```c++
v.sort(v.begin(),v.end());
```

------

### unique

벡터 원소 중복제거

연속된 중복 원소를 벡터의 제일 뒷부분으로 쓰레기값으로 보낸다.

------

### erase

벡터의 원소 삭제



> **활용**
>
> v.erase(unique(v.begin(),v.end(),v.end()));
>
> 벡터 v의 중복 값을 뒤로 옮긴 후 쓰레리값(중복 처리된 값)을 지운다.
>
> (int형이 아닌 문자도 중복제거가 가능하다)
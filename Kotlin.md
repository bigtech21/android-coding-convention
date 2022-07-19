#Kotiln

## Naming rules

### 변수 이름

- Boolean 변수의 시작은 is로 시작한다.
```kotiln
var isXXX: Boolean = false
```

- LiveData 계열 변수의 시작은 live로 한다.
```kotiln
var liveXXX : LiveData
```

- Flow 계열 변수의 끝은 flow로 한다.
```kotiln
var XXXFlow : Flow
```

### 함수 이름

- liveData observe할 때 사용하는 함수 이름
```kotiln
fun observeXXX()
```

- 서버에서 데이터 갖고오는 함수 이름
```kotiln
fun requestXXX()
```

- 특정 값을 갖고오는 함수 이름
```kotiln
fun getXXX()
```

- 특정 값을 찾는 함수 이름
```kotiln
fun findXXX()
```

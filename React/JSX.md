
# JSX

- 브라우저는 JSX를 이해할 수 없으며, Babel과 같은 패키지를 활용해서 JSX를 javascript의 함수로 변환시켜야 함

- 문법과 형태가 html과 매우 유사함


# HTML과 JSX의 차이점

|   |HTML|JSX|
|:---:|:---:|:---:|
|스타일 속성| "color:red" | {{color:'red'}} |
|클래스 속성|class="name"|className="name"|
|JS변수 참조| 불가능함 | 가능함 |

1. 스타일 속성 지정하기

1-1. HTML
```
<div style="background-color:red;"></div>
```

1-2. JSX
```
<div style={{ backgroundColor:'red'}}></div>
```


2. 클래스 속성 지정하기

2-1. HTML
```
<label class="label" for="name">Name:</label>
```

2-2. JSX
```
<label className="label" htmlFor="name">Name:</label>
```

  javascript에 class 키워드가 이미 존재하기 때문에 JSX에서는 className으로 지정.

3. Javascript 변수 참조하기

- JSX
```
{변수명 or 함수명}
```

  단, javascript 객체는 참조할 수 없다.

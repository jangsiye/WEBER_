### 데이터 입력

src/asset/data/ 의 js 파일에 변수로 등록하여 사용합니다

json 객체를 읽어와 렌더링하는 방식입니다


```
1주일 단위의 데이터
배열(0~6)마다 월요일~일요일까지 항목이 나열
img는 경로 그대로 넣고 파일명만 작성

json 파일 모델
http://www.objgen.com/json/models/Xd6z

예시 파일이라 1주만 만들어 놓았습니다
js 파일을 추가하셔서 만드셔도 되고, 변수를 추가하셔도 됩니다
```

<br>


---



### 세부 형식

```js
/*
변수 하나에 1주일치 데이터 저장
배열(0~6)마다 월요일~일요일까지 항목이 나열
*/
let 변수 = [
  [
    //월요일 데이터
  ],[
    //화요일 데이터
  ],[
    //수요일 데이터
  ],[
    //목요일 데이터
  ],[
    //금요일 데이터
  ],[
    //토요일 데이터
  ],[
    //일요일 데이터
  ]
]


```

각 요일의 상세 데이터는 다음과 같습니다

```json
{
  "name": "작품이름",
  "img": "src/asset/img/Gwacheon/이미지.png",
  "contents": {
    "date": "2019.09.10",
    "author": "누구누구",
    "numOfWorks": "10개",
    "price": "35,000",
    "host": "누구누구주최",
    "content": "내용ㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇㅇ"
  }
}
```

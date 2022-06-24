#HTML 구조
> h1 <br><br>
> div // map의 구역 지정


# Javascript
※ map을 추가하기 위한 함수
```
  function initMap()
```
1) map의 위치와 options을 지정
```
  var option = {} // map의 확대 정도와 중심 위치를 위도와 경도로 표시
  var map =       // map의 위치와 options를 함께 지정
```  
2) 마우스 클릭시 marker 표시

- marker : 화면에 표시되는 화살표


  ```
  .addListener(map, 'click', function(e){} // click이 되는 경우 실행되는 함수 function(e)
  ```
3) marker 표시 함수


- 매개변수 props : 위치, iconimage, content에 대한 표시가 나타나 있음
  
  
4) marker의 위치를 사전에 지정
- 위치를 markers 배열에 저장
- coords : 위치 지정
- iconImage : marker의 이미지 지정
- content : marker 클릭 시 나타나는 content html 형식으로 지정
  ```
  for(...){               // for문을 돌면서 markers의 각 요소들을 표시
    addMarker(markers[i]);
  } 
  ```

# watch
# 자바스크립트 디지털 시계 만들기
![time2](https://user-images.githubusercontent.com/104752580/174728008-a0d7738b-1a10-48ce-ba3a-eaa442336500.JPG)
![time](https://user-images.githubusercontent.com/104752580/174727663-d552522e-e7d6-403e-875c-387a6c7af2ef.JPG)



div 태그 안에 container와 clock이라는 클래스를 각 각 만들어 주고 style태그 안에서 클래스들을 각 각 알맞은 형태로 꾸며주는 코드를 작성합니다.

script 태그 안에는 디지털 시계를 만들 수 있는 코드를 작성합니다.

변수 handleld와 h1, go, stop을 선언해주고, handleld는 0으로 선언해서 go를 누르기 전에는 실행이 되지않게 만듭니다.

그리고 h1, go, stop 에는 document.getElementByld로 화면에 출력하게 하는 코드를 선언해줍니다.

go와 stop 이라는 버튼을 만들어 줍니다.

getTime이라는 함수를 만들어 줍니다.

함수 안에 date, hour, minutes, seconds, time 변수를 선언해 주고 h1.textContent 값을 time으로 선언합니다.

변수들은 현재 시각을 알 수 있는 date.get 코드를 통해 시, 분, 초를 나타내도록 선언해줍니다.

그리고 go를 클릭하면 handleld=setInterval(getTime,1000)이라는 코드를 통해 현재 시간을 흐르도록하고, stop을 누르면 handleld가 다시 0이 되기 때문에 시간이 멈추게 되는 코드를 씁니다.

# 실행화면
![time3](https://user-images.githubusercontent.com/104752580/174732095-812a74db-0678-4b69-abb1-962f668befd5.JPG)
![time4](https://user-images.githubusercontent.com/104752580/174732104-c11ff91a-cb6d-45fc-ba6a-b35214ff4f6f.JPG)

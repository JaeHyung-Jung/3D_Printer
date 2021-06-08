출처 : https://kgu0724.tistory.com/176   

(주)SierraBASE에서 사용하는 3Dprinter 모델은 Pro2_plus_pro이며 FDM출력방식을 사용한다.   
FDM은 필라멘트를 한층 한층 녹여서 출력하는 방식이며 이 층의 높이를 조절함으로써 출력물의 품질을 조절할 수 있다.   

Layer값은 Default가 0.2mm이며 노즐은 0.4mm이다.   

Layer높이를 낮게할수록 출력시간은 오래걸리지만 퀄리티가 상승하게 되고 특히 곡면부분에서 부드럽게 출력되는 경향을 가진다.   
하지만 단순히 Layer만을 낮출경우 오히려 압출불량의 이유로 품질이 낮아질 수 있다.   

따라서 상당한 수준의 품질이 필요한 출력물이라면 Flow_rate(압출량)을 낮추고 Layer높이도 낮춘다면 시간은 오래걸리지만 높은품질의 출력결과를 기대할 수 있다.   
![image](https://user-images.githubusercontent.com/79160507/121138296-81890680-c872-11eb-9541-a15e0f09f365.png)   
(이미지 출처 : https://kgu0724.tistory.com/176)   
위 그림은 왼쪽부터 각각 layer높이를 0.05mm / 0.1mm / 0.2mm로 설정한 후의 출력결과인데   
Layer높이가 낮을수록 출력품 내부에 빈공간이 많고 품질이 좋지못하다.   
이런 경우에 Layer높이를 낮추고 Flowrate까지 낮춰준다면 해결이 가능하다.   

![image](https://user-images.githubusercontent.com/79160507/121138581-ce6cdd00-c872-11eb-89f3-a90f6a376f19.png)
(이미지 출처 : https://kgu0724.tistory.com/176)   
위 그림은 압출량을 낮춘상태에서 왼쪽부터 순서대로 Layer를 0.2mm / 0.1mm  / 0.05mm이다.   
Layer높이가 낮아질수록 곡면의 수평방향 선과 같은 단층이 없어지고 부드럽게 출력된다.   

우리가 사용하는 프린터인 Pro2 PLus와 호환되는 IdeaMaker의 Layer높이 설정방법과 출력속도 설정방법을 아래에 설명하겠습니다.   
![image](https://user-images.githubusercontent.com/79160507/121138998-3de2cc80-c873-11eb-8fac-c2e6cfcfbc93.png)
IdeaMaker를 실행시킨 후의 첫 화면

첫 화면에서 상단메뉴의 슬라이스 -> 레이어 별 설정 -> 템플릿 선택을 누르면 다음과 같은 창이 생긴다. (왼쪽메뉴의 재생버튼 -> 템플릿 선택또한 동일)
![image](https://user-images.githubusercontent.com/79160507/121139349-9fa33680-c873-11eb-8638-d9036dd4cb7e.png)
다음과 같이 템플릿 선택창에서 레이어 층 높이를 원하는 대로 설정할 수 있다. (ex : 0.2mm / 0.05mm)









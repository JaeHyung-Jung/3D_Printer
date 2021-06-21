# RaiseCloud   
RaiseCloud를 통해 출력상황의 카메라를 통한 모니터링, 프린트, 파일관리, 출력의 정지 및 재개 등의 기능을 사용할 수 있습니다.

## 원격연결방법   
프린터와 PC가 같은 Wifi를 사용하고있다면 PC에서 ideamaker의 프린터 스캐닝 기능을 통해 같은 네트워크에 있는 프린터를 스캔하여 연결할 수 있다.
또는 동일한 이더넷을 사용하면 연결할 수 있다.

이 방법 외에 RaiseCloud를 사용하면 Wifi나 이더넷에 상관없이 Cloud를 통해서 연결을 할 수 있고
RaiseCloud는 모바일용 Application도있어 휴대폰에서도 출력이나 프린팅 과정 모니터링이 가능하다.
(프린트를 RaiseCloud의 계정과 Bind하는 작업이 필요한데 이미 Bind해줬으나 만약 어떠한 이유로 다시 Bind를 해야한다면 https://cloud.raise3d.com/html/howtobind.html 를 참고)   

RaiseCloud Web_Link(PC) : https://cloud.raise3d.com/raise3d.html   
RaiseCloud APP(Mobile) : https://play.google.com/store/apps/details?id=com.raise3d.raisecloud
   
Web기준으로 설명하겠습니다.
![image](https://user-images.githubusercontent.com/79160507/119068455-2dcb9000-ba1f-11eb-891d-6b32beb77aee.png)
웹에 접속한 후 로그인을 하면 다음과 같은 첫화면이 나옵니다.   
   
우측상단의 계정 이름부분을 클릭하면 
![image](https://user-images.githubusercontent.com/79160507/119068503-4c318b80-ba1f-11eb-8d4d-893a73894d73.png)   
이렇게 DashBoard, Sign out버튼이 나오는데 DashBoard를 눌러줍니다.   
   
![image](https://user-images.githubusercontent.com/79160507/119068544-679c9680-ba1f-11eb-9d9d-978e1676a635.png)
Dashboard에는 Printer의 작업상황과 시간별 Filament 사용량 그래프, Team Information이 나옵니다.
   
출력중인 작품의 진행상황 또는 설정변경, 정지, 재개등을 하려면 Printing(N)을 클릭해줍니다.   
![image](https://user-images.githubusercontent.com/79160507/119068701-adf1f580-ba1f-11eb-9e9a-4675175f6b17.png)   
Printing버튼을 클릭하면 다음과 같이 좌측, 우측노즐과 히팅베드, 기타 세부옵션등의 값들이 나오고   
프린트 진행상황, 좌측노즐과 우측노즐의 Filament 잔량이 뜹니다.   
   
   ![image](https://user-images.githubusercontent.com/79160507/119068810-daa60d00-ba1f-11eb-8535-1c3f8ce21060.png)   
우측상단의 동그라미친 버튼을 누르게되면   
![image](https://user-images.githubusercontent.com/79160507/119068846-ed204680-ba1f-11eb-9b3d-5fc01b0c299d.png)   
다음과 같이 현재 진행중인 작업의 일시정지, 정지, 재개등의 기능을 사용할 수 있고   
Raise-Pro시리즈의 제품에 포함된 프린트 내부 Camera를 통해 진행상황을 실시간으로 모니터링 할 수도 있습니다.    
(사진에서는 Camera를 Activate하지 않아 보이지 않음)   
   
진행상황과 카메라를 통한 모니터링 등 거의 모든 RaiseCloud의 기능들을 APP을 통해 모바일에서도 사용할 수 있습니다.

## RaiseCloud를 통해서 모델을 Slicing하고 출력하는 방법   
RaiseCloud에 .stl파일(모델)이 업로드되었다면 이 모델을 슬라이싱한 후 추출된 Gcode파일을 통해 프린트를 할 수 있습니다.   
   
![image](https://user-images.githubusercontent.com/79160507/119426376-10126980-bd44-11eb-9d94-dd0dda1908a2.png)   
위 그림과 같이 stl파일에 커서를올리면 동그라미 친 부분의 Slice버튼이 보이는데 이 버튼을 클릭해 모델을 Slice합니다.   
Slice는 Ideamaker를 통해서 할 수 있습니다.   
서포트를 대주고 모델의 출력품질 등을 설정한 후 슬라이싱하면 Gcode파일이 생성되는데 이 파일을 RaiseCloud로 업로드해줍니다.   
   
![image](https://user-images.githubusercontent.com/79160507/119426538-6384b780-bd44-11eb-8654-3259a7a7198a.png)   
업로드 된 Gcode파일에 커서를 올리면 프린트 버튼(동그라미 친 버튼)이 보입니다. 이제 출력을 위한 모든 준비가 끝났습니다.   

모바일 휴대폰에서는 slicing을 할 수 없어 Gcode파일로만 출력이 가능하고 노트북이나 데스크탑환경에서 ideamaker를 통해 slicindg한 후 gcode파일을 업로드 해주어야 합니다.    


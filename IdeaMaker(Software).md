# IdeaMaker\(Software\)

## What is IdeaMaker?

IdeaMaker는 Pro2 Plus 슬라이싱 프로그램이다.

3Dmodel file\(stl, obj 등\)을 출력 설정에 맞게 Z축 층으로 나누고 명령어로 변환해주는 프로그램이다.

IdeaMaker는 Raise3D에서 개발한 무료 프로그램으로, Raise3D 홈페이지에서 다운로드 할 수 있다.

## Install

먼저, [https://www.raise3d.com/download/](https://www.raise3d.com/download/)링크로 이동한다.

![](.gitbook/assets/image%20%282%29.png)

사용자의 OS에 맞게 선택해서 다운로드한다. \(필자는 Windows를 선택하였음\)

![](.gitbook/assets/image%20%2818%29.png)

다운로드된 파일을 실행하면 다음과 같은 언어 선택 창이 생긴다. 언어를 선택한다.

![](.gitbook/assets/image%20%2820%29.png)

언어를 선택한 후 다음 -&gt; 라이선스 동의함 버튼 클릭 -&gt; 설치 위치 선택 -&gt; 설치를 누른다.

설치가 끝나고 IdeaMaker를 실행하면 Dark, White 인터페이스를 선택하는데 취향에 맞게 고르면 된다.

\(참고로, 필자는 젊은데도 눈건강이 좋지않아 White를 선택함\)

![](.gitbook/assets/image%20%2812%29.png)

색을 고른후 다음과 같이 프린터를 선택해야 한다.

프린터 타입에 맞게 고르면 된다. 

![](.gitbook/assets/image%20%2817%29.png)

익스트루더 개수는 2개로 설정하고 히팅배드 사용 옵션을 체크한 상태\(default\)로 다음을 누른다.

익스트루더는 필라멘트를 압출하는 기능을한다. \(Extruder에 대한 자세한 내용은 뒤에 있음\)   

Pro2 plus에서는 듀얼 익스트루더를 사용하므로 개수를 2개로 설정해주었다.

![](.gitbook/assets/image%20%288%29.png)

익스트루더 개수를 설정해주고 나면 필라멘트 종류를 고르면 된다.

PLA, ABS, 등등 여러 종류의 필라멘트가 있고 필라멘트의 굵기에 맞게 설정하면 된다.

구성 마법사\(프린터타입과 익스트루더 설정\)을 끝냈으면 1\)프린터 설정. 2\)필라멘트 설정, 3\)출력 프로파일을 설정해야 한다.

설정을 위해 [IdeaMaker Library](https://www.ideamaker.io/profile.html?id=6778931459987087360) 링크로 이동.

![](.gitbook/assets/image%20%286%29.png)

링크로 이동했으면 위 그림과 같이 Only PLA Setting을 Click!

![](.gitbook/assets/image%20%2821%29.png)

Import to ideaMaker를 누르면                   

![](.gitbook/assets/image%20%2819%29.png)

다음과 같이 주소가 뜨는데 IdeaMaker를 실행중인 상태에서 Copy를 누른후 IdeaMaker로 들어가면

![](.gitbook/assets/image%20%284%29.png)

복사된 링크를 인식해서 ideaMaker에 다운로드 창을 띄운다. 다운로드하면 된다.

![](.gitbook/assets/image%20%2823%29.png)

다운로드 버튼을 클릭하고 다음을 누르면 다음과 같이 템플릿을 가져오는 창이 뜨는데

템플릿 이름은 -export를 제외하고 'Only PLA Setting'으로 설정해준다. \(사실 기능적 차이는없고 편의의 문제이다. -export가 붙은 이유는 링크를 import할때 자동으로 붙기 때문이다.\)

프린터와 필라멘트는 기존으로 둔 후에 'OK'버튼을 누르자.

## Function 

이 목차는 IdeaMaker의 주로 사용하는 기능들을 목록화하고 그 기능들을 설명한다.

*  뷰 : 모델링 화면의 카메라 시점 변경 / will be edited.
*  이동 : 객체의 이동 \(드래그를 통해 이동시키거나 정렬할 수 있다\)
  * flat : 면을 선택하여 해당면을 바닥으로 붙이는 기능 
  * flat을 사용할 때 넓고 평평한 면이 바닥으로 가게 하는것이 출력품의 완성도를 위해 좋다.
*  프리 컷 : 객체를 나누는 기능. 객체가 클경우 프리컷을 통해 여러 객체로 나누어 출력한 후 붙일수 있다.
*  서포트 :  모델에 서포트를 추가하는기능이다. 서포트의 기둥 너비\(mm단위\)를 설정한후 자동서포트하면 서포트가 생성된다. 수동으로 서포트를 추가하거나 제거할 수 있고 수동으로 추가 할경우 z축을 기준으로 서포트기둥이 생성되며 서포트의 높이는 처음 객체와 닿는 높이이다. 제거는 이미 생성된 서포트 객체를 누르면 제거를 할 수 있다.
* Lay flat : 3D프린팅의 구조적 한계\(z축을 단면으로 올라가면서 출력\)로 출력을 실패할 수 있는 모델의 무게중심을 낮춘다던가 넓고 평평한 면을 아래로 보낼때 사용하는 기능이다.


## 실제 사용법 (모델을 불러오고 Printer로 출력하기까지)

이제 위 Installation목차를 통해 설치를했거나 이미 ideamaker가 설치된 후에, 어떻게 프린터를 통해 실제로 모델을 load하고 출력하는지 알아봅시다.
![image](https://user-images.githubusercontent.com/79160507/115663883-19429c00-a37c-11eb-871e-c2d6bc050475.png)
ideamaker를 실행하면 다음과 같은 창이 나옵니다.
여기서 모델불러오기 버튼을 통해 PC의 local에 저장된 3D 모델(.stl, .obj)을 불러옵니다. 
* 만약 ideamaker에서 불러올 수 없는 확장자(ex: .stp)라면 CAD의 import를 통해 .stp파일을 불러온 후 영역을 지정하여 .stp파일을 .obj나 .stl로 변환하여 저장해준 후에 ideamaker로 열면 된다.

![image](https://user-images.githubusercontent.com/79160507/115664399-bac9ed80-a37c-11eb-8fff-70eff96936e0.png)
모델 불러오기 버튼을 누르고 PC에 저장된 3D모델 파일을 불러오면 다음과 같이 모델이 가상의 히팅베드 좌표위에 나오게된다. 

모델을 불러오면 슬라이싱 시작 버튼을 누르면 다음과 같은 화면이 뜨는데
![image](https://user-images.githubusercontent.com/79160507/115664529-eb118c00-a37c-11eb-9eb5-410995cac6a8.png)
원하는 품질을 선택한 후 오른쪽 밑의 '슬라이스'버튼을 클릭하면 
![image](https://user-images.githubusercontent.com/79160507/115664604-04b2d380-a37d-11eb-9f3c-2b4a67f39f68.png)
위의 그림과 같이 예상 소요시간과 필라멘트 사용량, 가격등의 정보가 뜬다. 
여기서 대부분은 미리보기를 통해 어떤식으로 모델이 슬라이스 됐는지 확인 한 후에 슬라이스된 모델을 프린터에 업로드해준다.
프린터에 sliced model이 업로드되면 Pro2 Plus를 직접 조작하여 load된 모델을 print하여 줄 수 있다.





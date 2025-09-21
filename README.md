# 절정3(Jeoljeong3)
Jeoljeong3 is PPT template for touch devices.\
If you need Korean explanation, go to <https://sooseongcom.com/post/jeoljeong3>.

## User Manual
### System Requirements
* Microsoft Powerpoint
* Display: 16:19

### How to install
아래의 설치파일 중 원하는 것을 내려받아 설치합니다.(Click the link which you want.)

* [절정3 빌드5(Jeoljeong3 Original Build5)](https://github.com/sooseongcom/jeoljeong3/releases/download/v3.0.5/Jeoljeong3.Build5.zip)
* [절정3 탭템플릿 빌드5(Jeoljeong3 Tab Template Build5)](https://github.com/sooseongcom/jeoljeong3/releases/download/v3.0.5/Jeoljeong3.Tab.Template.Build5.zip)
  * 태블릿에서도 PPT를 쉽게 넘길 수 있도록 이전/다음 단추 제공(Prev/Next button)
* [절정3 전자칠판템플릿 빌드5(Jeoljeong3 Electronic Board Template Build5)](https://github.com/sooseongcom/jeoljeong3/releases/download/v3.0.5/Jeoljeong3.Electronic.Board.Template.Build5.zip)
  * 전자칠판에서도 PPT를 쉽게 넘길 수 있도록 이전/다음 단추 제공(Prev/Next button)
  * 편리하게 판서할 수 있도록 펜/지우개/마우스 전환 단추 제공(pen/eraser/mouse button)

1\. First, extract files.

![같은 폴더 안에](https://sooseongcom.com/assets/images/20250830/1.png)\
2\. external folder and 절정3.pptx file should be in the same folder.\
3\. Install **NanumBarunGothic.ttf** please.\
4\. Comlete. Run 절정3.pptx.

### For 절정3 전자칠판템플릿(Jeoljeong3 Electric Board Template)
![절정3.pptm right click](https://sooseongcom.com/assets/images/20250830/7m.png)\
5\. If you installed 절정3 전자칠판템플릿(Jeoljeong3 Electric Board Template), right click 절정3.pptm and click **Properties**.

![절정3.pptm 속성](https://sooseongcom.com/assets/images/20250830/8편집.png)\
6\. Unblock it.

![Run 절정3.pptm](https://sooseongcom.com/assets/images/20250830/9.png)\
7\. Run **절정3.pptm**. Click **Enable Content**.

![차단된 콘텐츠](https://sooseongcom.com/assets/images/20250830/10.png)\
8\. Enter **Trust Center**.

![ActiveX 설정](https://sooseongcom.com/assets/images/20250830/11.png)\
9\. In **ActiveX Settings**, select **Prompt me before enabling all controls with minimal restrictions**.\
10\. Then, you can use pen buttons.

## Developer Manual
The files of this repository are 절정3 전자칠판템플릿(Jeoljeong3 Electric Board Template).

### Files
* 📁external
  * 절정3 사용설명서.pptx
* 절정3.pptm
* NanumBarunGothic.ttf

### How to modify code
1\. Run 절정3.pptm

2\. Click **Developer** tab.\
If there isn't Developer tab,
2.1. On the File tab, go to **Options**→**Customize Ribbon**.\
2.2. Under Customize the Ribbon and under Main Tabs, select the **Developer** check box.

3\. Click **Visual Basic**.

* Microsoft Powerpoint
  * **SlideMaster**: Command button(Red/Blue/Black/Other/Eraser/Mouse)
* Form
  * **UserFormCustomColor**: Select other color
* Module
  * **Module1**: scrollVal(inp) function

## License
1\. This repository contains 나눔바른고딕(NanumBarunGothic.ttf), which is copyrighted by Naver Corporation.

2\. Permission\
2.1. CC0 for offline\
2.2. CC0 for School assignment\
**2.3. If you modify and deploy this template, CC BY**
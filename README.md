
### 📌 HTML CSS JS 

* **웹 사이트의 구성 요쇼**

![image](https://user-images.githubusercontent.com/99783474/189499463-f60b0423-416e-4890-aded-311bc7835b42.png)

* [⏰ 웹의 역사](https://github.com/oiosu/HAPPY-WEB_MLP/blob/master/WEB_0829/WEB_0829.md)  [⚔ 브라우저 전쟁](https://github.com/oiosu/HAPPY-WEB_MLP/blob/master/WEB_0829/WEB_0829.md) 

* ✔ W3C(World Wide Web Consortium) 에서 웹 표준이 확정되는 순서 

![image](https://user-images.githubusercontent.com/99783474/189499617-a5cc04f4-b6de-4d27-8481-8f7092702e15.png)

####  **◼ 웹 표준의 장점** 

​	◾ 여러 브라우져를 통하여 같은 퀄리티의 기능이 사용 가능하다.

​	◾ 제공하는 정보를 모든 사람이 접근하여 보다 빠르고 즐겁게 웹 개발이 가능

​	◾ 사이트 업데이트 및 수정과 관리가 용이하다. 

​	◾ 검색 엔진 최적화 

​	◾ 웹을 이용하기 위해서 특별한 요구를 갖는 사람들이 보다 쉽게 웹을 이용할 수 있음

​	◾ 보편적인 웹 표준을 유지함으로써 기술 개발에 따른 상위호환성을 확보할 수 있음

---

#### (1) 웹 접근성이란?
    웹에 접근하는 누구나 (신체적, 환경적 제한없이) 불편없이 웹을 사용할 수 있도록 하는 방식

    장애인, 노인 등 정보 취약계층이 인터넷 상에서 차별없이 다르사용자와 동등하게 정보에 접근하고 이해할 수 있도록 
    보장하는 것으로 웹 접근성의 주 목적은 웹 컨텐츠를 이용하는 데에 어떠한 상황이나 환경에 구애받지 않고 접근할 수 있도록 하는 것이다. 
    
    
#### (2) 웹 접근성 준수 의무자 및 적용 시기 
    2013.04.11 : 병원(입원 30인 미만), 사립유치원, 평생교육시설, 연구기관, 직업훈련기관(1,000제곱미터 이상), 보육시설(100인 미만), 
    민간 일반 공연장, 소공연장, 상시 근로자 30~100인 사업장(고용관계), 모든 법인
    
    
#### (3) 웹 접근성 준수 시 기대 효과 
    * 장애인, 고령자 등을 포함한 사용자층 확대
    * 규정과 법적 요구 사항에 대한 준수 
    * 다양한 환경, 새로운 기기에서의 이용
    * 개발 및 운영의 효율성 제고 
    * 사회 공헌 및 복지 기업으로서의 기업 이미지 향상

✔ [W3C(World Wide Web Consortium) 접근성 지침(WCAG)](https://a11y.gitbook.io/wcag/international-standards)

    `시각 (Visual)` `청각 (Auditory)` `지체 (Physical)` `음성 (Speech)` `인지 (Cognitive)` `언어 (Language)` `학습 (Learning)` 
    `신경 (Neurological)` WCAG는 각 지침을 4가지 원칙의 범주로 분류하여 제공합니다.
     인식이 가능하고, 조작이 가능하며, 이해할 수 있고, 견고해야한다. 

---

#### [💡 개발 환경 설정](https://github.com/oiosu/HAPPY-WEB_MLP/blob/master/WEB_0829/WEB_0829.md) 

* **open in browser**  / **auto renmae tag**  / **auto close tag**  
* **IntelliSense for CSS class names in HTML**  / **html css support**

---

![image](https://user-images.githubusercontent.com/99783474/189499920-e2269c65-c490-42fa-a437-a72160fa09a9.png)

---

### [💡 HTML (Hyper Text Markup Language)](https://github.com/oiosu/HAPPY-WEB_MLP/blob/master/WEB_0829/WEB_0829.md)

    * Hyper Text : 참조(하이퍼링크)를 통해 사용자가 한 문서에서 다른 문서로 즉시 접근 할 수 있는 텍스트 

    * Markup Language : 태그 등을 이용하여 문서나 데이터의 구조를 명시하는 언어

![image](https://user-images.githubusercontent.com/99783474/189500022-a22360a5-5c32-4a16-be06-8615dc3e196c.png)

---

### [💡 CSS (Cascading Style Sheet)](https://github.com/oiosu/HAPPY-WEB_MLP/blob/master/WEB_0830/WEB_0830.md)


![image](https://user-images.githubusercontent.com/99783474/189606867-0c9ad22f-b88e-4c6e-88fe-561a7bd4d0c1.png)

#### ◾ 크기단위 

| **em**   | **부모 요소의 크기의 영향을 받아 크기가 변함**               |
| -------- | ------------------------------------------------------------ |
| **rem**  | **최상위 요소인 html 요소의 크기의 영향을 받아 크기가 변함 (익스 9.0이상 부터 지원)** |
| **%**    | **부모 요소의 크기의 영향을 받아 크기가 변함**               |
| **vw**   | **viewport width 의 약자 / 80vw = "뷰포트 영여의 80%" (익스 9.0이상 부터 지원)** |
| **vh**   | **viewport width 의 약자 / 80vw = "뷰포트 영여의 80%" (익스 9.0이상 부터 지원))** |
| **vmin** | **뷰포트의 최소값/설정한 viewport 값에 따라 변함 (익스 12.0이상 부터 지원)** |
| **vmax** | **뷰포트의 최대값/설정한 viewport 값에 따라 변함 (익스 12.0이상 부터 지원)** |



#### ◾ 색상단위 


![image](https://user-images.githubusercontent.com/99783474/189607188-14c4f61b-67c8-4d2b-92e0-c64ccce11950.png)


#### ◾  TEXT CSS 문서 표현

| font-family                            | 서체                          |
| :------------------------------------- | :---------------------------- |
| **font-style, font-weight**            | **서체 스타일**               |
| **letter-spacing**                     | **자간**                      |
| **word-spacing**                       | **단어 간격**                 |
| **line-height**                        | **행간**                      |
| **color**                              | **컬러**                      |
| **background-image, background-color** | **배경**                      |
| **li, table**                          | **기타 html 태그별 스타일링** |


#### ◾ Selector

![image](https://user-images.githubusercontent.com/99783474/189607817-ef602f75-df5c-4bd7-8744-a142fdb84837.png)


---

### ✔ CSS Box model

#### CSS 원칙 1) 모든 요소는 네모 박스 모델이고, 위에서 아래로, 왼쪽에서 오른쪽으로 쌓인다. 

![image](https://user-images.githubusercontent.com/99783474/189608157-bff15082-e214-49f8-8416-3f07d056065b.png)


#### ◼ BOX SIZING 

![image](https://user-images.githubusercontent.com/99783474/189608325-89d9ca56-9596-450c-b67c-47ab0b44e101.png)



### ✔ CSS Display 

#### CSS 원칙 2) 모든 요소는 네모 박스모델이고, 좌측상단에 배치, display에 따라 크기와 배치가 달라진다. 

![image](https://user-images.githubusercontent.com/99783474/189608660-205dfd62-dd26-4ad3-b678-54c94e1082ad.png)


#### ◼ 속성에 따른 수평 정렬 

![image](https://user-images.githubusercontent.com/99783474/189608929-f09c4a9b-efc5-4f29-b4fb-227981c5598b.png)






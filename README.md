# capstone_final🌟

------

![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmsmn1729%2Fcapstone_final&count_bg=%2306A1F1&title_bg=%23555555&icon=iconify.svg&icon_color=%23FFFFFF&title=hits&edge_flat=false)
![imge](https://img.shields.io/badge/ProjectType-TeamProject-green)
![imge](https://img.shields.io/badge/Language-python-yellow)
![imge](https://img.shields.io/badge/Tools-PyCharm-red)
![imge](https://img.shields.io/badge/Tools-Django-red)

## 프로그램 소개:memo:

- 주제 : 딥러닝 기반 열악 자동차 번호 이미지 복원 및 인식 기술  
(Deep Learning-Based Vehicle Number low resolution Image Restoration and Recognition Technology)

- 제9회 창의설계경진대회 우수상 수상(2020.06.19.)

------

## 필요성:bar_chart:

![자료](https://user-images.githubusercontent.com/59201008/95758637-af1db000-0ce3-11eb-9108-bc772c069537.png)

- 좌측부터 교통사고 건수, 뺑소니 교통사고 추이, 블랙박스 번호판 판독 요청 글입니다.
  - 교통사고는 꾸준히 발생하여 하한선 미만으로 내려가지 않습니다.
  - 자동차 커뮤니티의 블랙박스 영상 번호판 판독 요청도 매일 꾸준히 올라오는 것을 알 수 있습니다.
  
- 열악한 해상도의 이미지에서 번호판을 높은 정확도로 판독할 수 있다면 기대할 수 있는 효과는 다음과 같습니다.
  - 뺑소니와 같은 범죄 용의차량을 검거하는 데 일조하여 스마트 치안(SMART Policing) 실현에 도움을 줄 수 있습니다.
  - 저해상도의 성능을 가지고 있는 교통법규 단속 카메라의 번호판 인식률을 높일 수 있다.

------

## 개발 환경:computer:

![개발 환경](https://user-images.githubusercontent.com/59201008/95761527-6536c900-0ce7-11eb-902d-ef4bd5a69c6b.png)

------

## 시스템 구성도:mailbox:

![시스템 구성도](https://user-images.githubusercontent.com/59201008/95759743-112ae500-0ce5-11eb-8a64-cb33ddd15ccc.png)

------

## 주요 기능:dart:

![주요 기능](https://user-images.githubusercontent.com/59201008/95758927-028ffe00-0ce4-11eb-9ac3-3a769a8a6772.png)

- 주요 기능을 흐름 순서대로 3단계로 나눌 수 있습니다.

  - LP Detection : 이미지 상에서 번호판(License plate)을 감지해서 추출합니다.
  - Super Resolution : 전 단계에서 추출한 번호판을 고해상도로 변환합니다.
  - Recognition : 고해상도로 변환한 번호판의 문자와 숫자를 인식하여 원본 번호판의 문자와 숫자를 찾아냅니다.

------

## 흐름도(Flow chart):page_facing_up:

![흐름도](https://user-images.githubusercontent.com/59201008/95759992-71ba2200-0ce5-11eb-9a5c-90c66ab058c7.png)

------

## 시연 동영상:oncoming_police_car:

![시연 동영상](https://user-images.githubusercontent.com/59201008/95768583-88667600-0cf1-11eb-9c08-a4709f026d3a.gif)

- 발표 및 시연영상 : [YouTube](https://youtu.be/fghqxWO-deQ) (Shift를 누른 상태로 클릭해주세요:smile:)

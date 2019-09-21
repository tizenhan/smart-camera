

## I.o.T ( Initialize On Tizen )팀명 및 팀원
* 박신호 (기술조언 ,디버깅, 설계)
* 한민수 (발표, 개발, 디버깅, 설계,기획,디자인)
* 한은총 ( 기획, 디자인 ) 


# ***SmartSurveillanceCamera 아기 움직임 감지 관찰 카메라***


## 프로젝트 배경 혹은 목적
* 하루 수십번 씻기는 아기를 방에 홀로 놔두고 목욕준비 분유,이유식 준비 하러 가기 불안하다!
  
  실시간으로 아기의 움직임 확인하며 편하게 준비하자. 
* 아기가 자는 시간 = 유일한 휴식시간 "아기의 실시간 자는 모습을 보며 마음 편히 반신욕 하자 !"


## 타이젠 오픈소스에 컨트리뷰션한 내역

***반영 완료, [[적외선 온도센서](https://review.tizen.org/gerrit/#/c/apps/native/rcc/+/213558/)]***

***반영 완료, [[초음파 거리센서](https://review.tizen.org/gerrit/#/c/apps/native/rcc/+/214042/)]*** 

***반영 완료, [[릴레이제어](https://review.tizen.org/gerrit/#/c/apps/native/rcc/+/214279/)]***



## 파일 리스트  
* inc/resource_camera.h
* src/resource_camera.c



## 코드 기여자  
 * inc/resource_camera.h resource_camera_stop_preview 한민수	
 * src/resource_camera.c resource_camera_stop_preview 한민수


## 보드
  * RPI3 1 : [[이미지 분석 및 모션센서 연동](https://github.com/tizenhan/smart-camera)]
  * RPI3 2 : [[온도,거리센서 연동](https://github.com/tizenhan/smart-faucet)]


## 구현사항
  * GPIO / UART 사용
  * 누비슨 클라우드 사용
  * 카메라 사용
  * 이미지 분석 기능 사용

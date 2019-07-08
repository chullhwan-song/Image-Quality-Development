# Image-Qualtiy

## 목적
* [1]의 논문 구현/테스트/평가
* idea추가한 업그레이드

## 진행상황
* target논문으로 google Nima 논문[1]을 참고하고 있음.
* 관련 소스가 많지만 그중 tf slim base로 된 이[2] 소스(thanks..!!)를 참고. 논문재현 및 향상 시키려고 노력하고 있음.
  * 이외 다양한 관련 소스가 많으니 찾아보기 바람.
* 개발
  * tensorflow
  * AVA 데이터를 기반으로, 실서비스로 확장진행
* 실험 (진행중)
  * AVA 데이터 > 결과 3~4% 정도 논문보다 뛰떨어짐을 확인(1번학습)
    * SROCC: 0.59  
    * LCC : 0.61
    * binary : 0.77 

## Reference
* [1] [NIMA: Neural Image Assessment](https://github.com/chullhwan-song/Reading-Paper/issues/119)
* [2] https://github.com/master/nima


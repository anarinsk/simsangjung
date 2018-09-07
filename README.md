**Korean Taxation Info by Sang Jung Sim**

2018-09-05
Jun Sok Huhh | :house:[lostineconomics.com](http://lostineconomics.com)

&nbsp; 

# Purpose 

본 리포지터리는 심상정 의원이 블로그에 [공개한 자료](https://m.blog.naver.com/PostView.nhn?blogId=713sim&logNo=221350785950&proxyReferer=https%3A%2F%2Ft.co%2FQYfrnFqnnO%3Famp%3D1)에 기반을 두고 만들어 졌습니다.
원자료 이외의 코드와 관련된 모든 문제는 제 책임입니다. 

# Desc on data 

* 자료는 모두 천분위 자료입니다. 하나의 데이터 셋 내에서 각 분위별로 명 수를 맞춰 추출된 자료입니다. 
* 데이터 셋은 크게 두 종류입니다. 
  * 근로소득: 2013년 ~ 2016년 (4개 년도)
  * 이자소득, 배당소득 (2016년) 

# Directories of repo  

본 리포의 디렉토리 구조는 다음과 같습니다. 

* [raw_data](https://github.com/anarinsk/simsangjung/tree/master/raw_data): 아래 최초 입수처 원본파일
    * 작업을 위해 파일 이름만 알파벳으로 수정 
* [code](https://github.com/anarinsk/simsangjung/tree/master/code): 데이터 정리 코드 (ipynb)
* [rds](https://github.com/anarinsk/simsangjung/tree/master/rds): rds format for r 
* [csv](https://github.com/anarinsk/simsangjung/tree/master/csv): csv files preprocessed to melt and pivot data sets

# Analysis

코드와 간략한 분석 내용을 주피터 노트북으로 담았습니다. 자세한 내용은 아래 링크를 참고하시기 바랍니다. 

* [jupyter notebook](https://nbviewer.jupyter.org/github/anarinsk/simsangjung/blob/master/code/load_tidy.ipynb)

# Working logs 

이하 내용은 일종의 작업일지입니다. 굳이 참고하지 않으셔도 됩니다. 

## 20180903 

* [자료 최초 입수](https://m.blog.naver.com/PostView.nhn?blogId=713sim&logNo=221350785950&proxyReferer=https%3A%2F%2Ft.co%2FQYfrnFqnnO%3Famp%3D1)
* 파일명 영문 전환 및 현재 github 구축 완료 
* load_tidy.ipynb: 데이터 정리 코드 & 기본 시각화 

&nbsp; 

:feet:Jun Sok Huhh | :house:[lostineconomics.com](http://lostineconomics.com)
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTY4NjM2NjgzNiwzOTY3ODc4MDQsMTEwOD
c2NDcwMF19
-->

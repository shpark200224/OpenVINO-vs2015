# OpenVINO-vs2015

## OpenVINO 설치

1. full package 설치(홈페이지 이용)<br/>
2. 환경 변수 설정<br/>
```
cd C:\Program Files (x86)\IntelSWTools\openvino\bin\
```
설치 폴더에서 위의 경로에 있는
```
setupvars.bat
```
파일 실행<br/>

3. Model Optimizer 설정
Model Optimizer는 필수 요소.<br/>
MO 동작 없이는 추론 불가<br/>
MO에 pre-train된 모델을 실행시킬 때의 출력: 네트워크의 IR(Intermediate Representation)<br/>
xml : 신경망 형태 / bin : 가중치, 바이어스 이진 데이터<br/>

```
C:\Program Files (x86)\IntelSWTools\openvino_2020.1.033\deployment_tools\model_optimizer
```
의 reqirements.txt와 프레임워크에 맞는 reqirements_*.txt로 dependency 설치(파이썬)
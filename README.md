# OpenVINO-vs2015

## 1. OpenVINO 설치
홈페이지 이용

## 2. 환경 변수 설정<br/>
```
cd C:\Program Files (x86)\IntelSWTools\openvino\bin\
```
설치 폴더에서 위의 경로에 있는
```
setupvars.bat
```
파일 실행

## 3. C++ 샘플 프로젝트 빌드
```
cd C:\Program Files (x86)\IntelSWTools\openvino_2020.1.033\inference_engine\samples\cpp
```
위 경로로 이동 후 빌드 파일 실행
```
build_samples_msvc.bat VS2015
```
Cmake 환경 변수 등록 필요

## 4. C++ 샘플 프로젝트 실행파일 빌드

C:\Users\USER\Documents\Intel\OpenVINO\inference_engine_cpp_samples_build <br>
Samples.sln 실행 > ALLBUILD 컴파일
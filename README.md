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

C:\Users\USER\Documents\Intel\OpenVINO\inference_engine_cpp_samples_build <br/>
Samples.sln 실행 > ALLBUILD 컴파일

## 5. hello_classification
* 필요 dll파일<br/>
clDNNPlugin.dll<br/>
inference_engine.dll<br/>
inference_engine_nn_builder.dll<br/>
inference_engine_preproc.dll<br/>
ngraph.dll<br/>
opencv_core420.dll<br/>
opencv_imgcodecs420.dll<br/>
opencv_imgproc420.dll<br/>
tbb.dll<br/>
plugins.xml<br/>

* 가중치 파라미터(xml, bin) - Model Optimizer로 변환한 것<br/>
* bmp 이미지<br/>

실행 명령어 예
```
hello_classification ./IR/alexnet.xml cat.bmp GPU
```

실행 결과
<img src="/doc/result.png" title="result" alt="result"></img><br/>
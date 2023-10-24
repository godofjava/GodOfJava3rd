# 자바의 신 실행기 
## JDK 17 이상 버전 다운로드 
* corretto 17 에서 컴파일 했기 때문에 corretto 다운로드 추천
  * https://docs.aws.amazon.com/corretto/latest/corretto-17-ug/downloads-list.html

## 사용법 - 1 (맥 사용자) 
* release 에 있는 jar 파일을 다운로드
* 터미널을 실행
  * 맥 : 터미널 실행
* 다음의 명령을 실행하여 프로그램 수행

```
$ java -jar godofjava-230902.jar
```
> 여기서 $ 은 입력하는 것이 아님

## 사용법 - 2 (윈도 사용자. 실행이 잘 안되는 경우나 아래의 오류가 발생할 경우)

```
Graphics Device initialization failed for :  d3d, sw
Error initializing QuantumRenderer: no suitable pipeline found
```

* JavaFX 다운로드 사이트로 이동
  * https://gluonhq.com/products/javafx/
  * 본인의 OS에 맞는 SDK 를 다운로드하여 압축 해제 
* release 에 있는 jar 파일을 다운로드
* 커맨드 창을 실행
  * 윈도우 : 돋보기 눌러서 cmd
* 다음의 명령을 실행하여 프로그램 수행
  * 아래의 예시는 javafx 모듈을 C:\AmazonCorretto\javafx-sdk-21.0.1 에 압축해제한 경우의 예임
  * 본인이 다운로드한 버전에 맞추어 내용 수정하여 사용
```
$ java --module-path C:\AmazonCorretto\javafx-sdk-21.0.1\lib --add-modules javafx.controls,javafx.fxml,javafx.base,javafx.web -jar godofjava-230902.jar
```
> 여기서 $ 은 입력하는 것이 아님


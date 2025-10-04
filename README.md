# H2O compare

한글파일을 비교하거나 내용을 출력하는 Java 바이너리입니다.

* 소스를 받습니다.

```
$ git pull origin main
$ git submodule update --init --recursive
$ git submodule update --remote --merge
```
* jar 파일을 빌드합니다.

```
$ mvn clean package
```

* 한글파일을 비교하여 차이점을 화면에 출력합니다.(-diff)
* 한글파일의 텍스트 내용을 화면에 출력합니다.(-print) 

```
사용예1) $ java -jar H2Ocompare-0.0.1.jar -diff Sample1.hwpx Sample2.hwpx
사용예2) $ java -jar H2Ocompare-0.0.1.jar -print Sample1.hwpx
```

* H2Orestart 소스에서 빌드합니다.
* 확장 바이너리의 사용은 무료이며, 자유롭게 사용하시면 됩니다.
* 오류나 불편사항은 이 github의 issue에 등록해주시면 주기적으로 개선하겠습니다.

## 라이선스
소스코드는 GNU GPLv3 라이선스로 공개합니다.

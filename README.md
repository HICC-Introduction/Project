# 구매목록 
## 1. 아두이노 UNO
[아두이노 UNO(usb 케이블 포함)](https://smartstore.naver.com/openidea/products/4828947299)
가격 : 6400원
수량 : 1개
## 2. 7segment module
[TM1637 FND display module](https://smartstore.naver.com/openidea/products/4840519637)
가격 : 900원
수량 : 1개
## 3. 맴브레인 숫자 키패드
[4X4 맴브레인 숫자 키패드 ](https://smartstore.naver.com/openidea/products/4833221581)
가격 : 670원
수량 : 1개
## 4. 점퍼 케이블
보유 중
## 5. 1k Ohm 저항
보유 중
# 총 결제 금액
![화면 캡처 2021-03-28 155829](https://user-images.githubusercontent.com/81162498/112744887-ddb3ec80-8fde-11eb-88cd-83b39ce5da30.jpg)

# Hardware - Calculator
## 목표 및 목적
[어떤 프로그램을 만들어야 하는지, 만들어진 프로그램은 어떤 역할을 하게 될지 작성해주세요]
### 문제 분석
[프로그램을 만들 때 예상할 수 있는 문제들을 최대한 쪼개서 어떤 문제를 해결해야 결과를 이루어낼 수 있을까. 에 대해 작성해주세요.]
* 최종 목적 : 계산기를 구현하도록 한다.
    * 상위 목적 : 하드웨어 연결을 통해 계산기를 물리적으로 구성한다.
        * 하위 목적 : ...
    * 상위 목적 : 소프트웨어 구현을 통해 계산기 내부 로직을 구현한다.
        * 하위 목적 : ...
## 개발 사양
### 하드웨어 - 개발
* CPU :  AMD Ryzen 5 4500u 6-Core Processor, 2375Mhz, 6 코어, 6 논리 프로세서
* RAM : 8GB
* HDD/SSD :SSD 256GB
* GPU : AMD Radeon Graphics Processor(0x1636)
### 하드웨어 - 부품
|인덱스|역할|모델명|가격|상세|링크|
|---|---|---|---|---|---|
|1|MCU|아두이노 UNO|6,400원|   |https://smartstore.naver.com/openidea/products/4828947299%7C
|2|입출력: 디스플레이|TM1637 FND / OPEN-TR02-001|900원|   |https://smartstore.naver.com/openidea/products/4840519637%7C
|3|입출력: 키패드|OPEN-TC06-013|670원|   |https://smartstore.naver.com/openidea/products/4833221581%7C
|4|케이블|점퍼 케이블|원|   |비고: 재고 보유로 인해 구매하지 않음|
|5|기타|1k Ohm|원|   |비고: 재고 보유로 인해 구매하지 않음|
|총합|   |   |10,470원|   |   |
### 소프트웨어
* OS : [Microsoft Windows 10 Pro 10.0.18363 build 18363]
* 개발 스택 : Arduino Uno
* 개발 프로그램 : Arduino / IDLE / PyCharm / Visual Studio / 기타
* 개발 언어 : C/C++
### 코드룰
* 예시 프로그램
```
    # 변수명
    test_variable = 13
    # 클래스명
    class TestClass:
        def __init__(self):
            # 프로퍼티명
            self.testProperty = 41
        # 메소드명
        def TestMethod(self):
            print(self.testProperty)
    if __name__ == "__main__":
        test_variable = TestClass(43)
        test_variable.TestMethod()
```
* 본인의 코드 룰
[위의 코드를 본인의 스타일로 직접 짜보세요]

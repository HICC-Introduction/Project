
# Hardware - Calculator
## 목표 및 목적
사칙연산을 모두 수행할 수 있는 코드를 짜고 이 코드가 성공적으로 7segment에 표현되도록 한다. 이 계산기는 4자리수 이하의 정수를 입력받아 5자리수 이하의 정수을 display에 표현한다.
어떤 프로그램을 만들어야 하는지, 만들어진 프로그램은 어떤 역할을 하게 될지 작성해주세요
### 문제 분석
[프로그램을 만들 때 예상할 수 있는 문제들을 최대한 쪼개서 어떤 문제를 해결해야 결과를 이루어낼 수 있을까. 에 대해 작성해주세요.]
* 최종 목적 : 계산기를 구현하도록 한다.
    * 상위 목적 : 하드웨어 연결을 통해 계산기를 물리적으로 구성한다.
        1. 4x4 맴브레인 키패드를 아두이노와 연결 후 아두이노 IDE에서 키패드가 작동되는지 확인한다.
        2. FND display를 아두이노 UNO의 pin과 연결하고 display에 고장이 없는지 확인한다.
        3. 7segment는 부호를 나타내므로 G에 해당하는 pin만 아두이노와 연결하고 LED 고장 여부를 확인한다.
        4. 
    * 상위 목적 : 소프트웨어 구현을 통해 계산기 내부 로직을 구현한다.
        1. 맴브레인 키패드에 존재하는 숫자들이 각각 0~9와 1:1 대응이 되도록 코딩한다.
        2. 키패드에 입력한 숫자가 연결된 FND display에 출력이 되도록 코딩한다. 
        3. 키패드에 존재하는 기호들을 누르면 사칙연산(+,-,*,/)이 되도록 코딩한다. 이 때 사칙연산 기호를 누르면 LED가 한번 깜빡이도록 한다. 
        4. 키패드의 #기호를 누르면 사칙연산의 결과(등호의 역할)가 출력되도록한다. 이 때 곱하기로 출력되는 결과는 4자리의 수 이하만 출력되고 그 이상의 자리수는 표현하지 않는다. 나누기로 출력되는 결과는 나머지는 버림하고 몫만 출력되도록 한다.
## 개발 사양
### 하드웨어 - 노트북
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
* 개발 프로그램 : Arduino IDE 
* 개발 언어 : C/C++
### 코드룰


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
        

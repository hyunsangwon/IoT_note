### AWS IoT Core
- AWS IoT Core는 서버를 프로비저닝하거나 관리할 필요 없이 IoT 디바이스를 AWS 클라우드에 연결할 수 있게 해 줌.  

### AWS IoT Core 특징
- 최대 최대 128KB(킬로바이트) 크기의 메시지를 송신 및 수신할 수 있음.

### AWS IoT Core 요금
- 최소 요금, 의무 서비스 사용량 없음.
- 연결 시간과 메시징 으로 요금을 부과.
- 연결 요금 
    0.096 USD(연결 100만 분당)  
    ex) 연중무휴 24시간 연결 시 1년에 디바이스당 0.050 USD를 지불.(연결 1개 * 0.096 USD/연결 1,000,000분 * 525,600분/년)

- 메세징
    메시지 100만 개당 1.20 USD  
    메시지가 40억 개를 넘으면 100만 개당 0.96  
    메시지 50억 개 초과 100만 개당 0.84  
    메시지는 5KB 단위로 측정 ex) 8KB 메시지는 메시지 2개로 측정
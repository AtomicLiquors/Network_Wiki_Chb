
SPoF Single Point of Failure  

혼자만 고장나도 전체 시스템이 함께 고장나는 시스템 구성요소.

## **왜 필요한가?**
FT Fault Tolerance  : 결함허용  
특정 인프라에 문제가 발생하더라도 다른 인프라를 통해 서비스가 지속되도록 해 준다.  

데이터 센터 이중화

## **형태**
Active-Standby
Active-Active 

 
&nbsp;
 


### **LACP**
액티브-액티브 구조 

Link Aggregation Control Protocol  
두 개 이상의 물리 인터페이스로 구성된 논리 인터페이스를 이용해,  
모든 물리 인터페이스를 Active 상태로 사용한다.  
- 스위치-스위치 또는 스위치-서버 간 네트워크 대역폭이 물리 인터페이스 수량만큼 확장된다.
- 물리 인터페이스 한쪽이 고장나도 다른 물리 인터페이스가 서비스를 유지한다.

구성을 위해 LACPDU라는 프레임을 사용한다.

PXE : Pre-boot eXecution Environment

 
&nbsp;
 
 
&nbsp;
 
네트워크 이중화 설정
- 윈도우 : 팀/티밍 team
- 리눅스  : 본드/본딩


서버 인터페이스의 이중화는 네트워크 인터페이스의 이중화와 다르다.
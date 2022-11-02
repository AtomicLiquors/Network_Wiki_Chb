[<<메인으로](https://github.com/AtomicLiquors/Network_Wiki_Chb)

&nbsp;  
&nbsp;  
# DNS
Domain Name System

도메인 주소를 IP주소로 변환  

도메인 주소 예시 : www.naver.com  

 
&nbsp;
 

### **중요해진 배경**
- 클라우드 환경에서 빈번한 인프라 변경
- MSA 환경에서 다수의 API 사용

 
&nbsp;

 
&nbsp;
 

## **동작 방식**
- DNS 서버에 '도메인 쿼리'하는 과정을 거친다. 

또는 

- DNS서버 없이 로컬의 'hosts 파일'에 도메인과 IP 주소를 직접 설정한다.

DNS 캐시 확인
```
ipconfig /displaydns
```
 
&nbsp;
 
## **DNS 구조와 명명 규칙**
각 계층의 경계를 .으로 표시하고, 뒤에서 앞으로 해석한다.

|www|naver|com||
|--|--|--|--|
|Third-level Domain|Second-level Domain|Top-level Domain|Root(생략)

 
&nbsp;
 

### **루트 도메인** 
도메인을 구성하는 최상위 영역  
루트 도메인을 관리하는 루트 DNS는 전 세계에 13개가 있다.


### **TLD Top-level Domain**
IANA에서 6가지로 구분
- gTLD : 일반적
- ccTLD : 국가 
- sTLD : 스폰서
- grTLD :
- tTLD : 테스트


 
&nbsp;
 
 
&nbsp;
 
## **DNS 서버 구분**
### **마스터(프라이머리)** 
### **슬레이브(세컨더리)** 

 
&nbsp;
 

## **DNS 주요 레코드**

 
&nbsp;
 
## **관련 개념**
- 도메인 위임
- TTL
- 화이트 도메인
- 한글 도메인
- GSLB(인텔리전스 DNS), DNS 로드밸런싱
- DHCP(IP 동적 할당)

&nbsp;  

Linux에서 bind 패키지로 DNS 서버 구축
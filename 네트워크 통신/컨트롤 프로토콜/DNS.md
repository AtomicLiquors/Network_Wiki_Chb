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
 
### **DNS 구조와 명명 규칙**
각 계층의 경계를 .으로 표시하고, 뒤에서 앞으로 해석한다.

|www|naver|com||
|--|--|--|--|
|Third-level Domain|Second-level Domain|Top-level Domain|Root(생략)

 
&nbsp;
 

루트 도메인 : 도메인을 구성하는 최상위 영역  
루트 도메인을 관리하는 루트 DNS는 전 세계에 13개가 있다.
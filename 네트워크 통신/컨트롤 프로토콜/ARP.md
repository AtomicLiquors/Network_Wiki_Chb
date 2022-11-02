


### **ARP** 
*Address Resolution Protocol*

상대의 IP 주소를 바탕으로,   
상대의 MAC 주소를 알아내는 프로토콜.

- GARP *Gratuitous ARP* :   
자신의 IP와 MAC 주소를 알리는 프로토콜.  
IP 충돌 감지, 상대의 ARP 테이블 갱신, 고가용성 용도의 클러스터링  
등등을 위해 필요하다. 

- RARP *Reverse ARP* :   
자신의 MAC 주소를 바탕으로,   
자신이 할당받아야 할 IP를 서버에게 문의하는 프로토콜.  
<br>
기능이 한정적이라 지금은 BOOTP, DHCP를 쓰며 RARP를 쓰지 않는다.

- 프록시 ARP : 라우터에 기본으로 활성화된, ARP를 대행해 주는 기능.  
게이트웨이 관련 참고. 



&nbsp;
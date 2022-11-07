[<<메인으로](https://github.com/AtomicLiquors/Network_Wiki_Chb)

&nbsp;  
&nbsp;  

# OSI 7계층 

데이터 전송 과정을 7가지 단계로 나눔.

현재 가장 많이 사용되는 프로토콜 스택인 TCP/IP 스택과 연관지어 설명해 보겠다. 


&nbsp;

> 현대 네트워크는 대부분 패킷 기반의 "패킷 네트워크"입니다.   
데이터를 패킷 단위로 쪼개 보내고,  
받는 쪽에서 패킷을 재결합해 원본 데이터를 사용할 수 있습니다.

 
&nbsp;
 

Q. 어떤 장점이 있나요?

A. **하나의 통신이 회선 전체를 점유하지 않습니다.**  
- 동시에 여러 단말이 통신할 수 있다.  



 
&nbsp;
  
&nbsp;
   
&nbsp;

   

## 상위 계층 / 애플리케이션 계층 (5-7)
애플리케이션 개발자들이 고려할 영역.  
따라서 개발자는 하향식(bottom-up)으로 네트워크를 파악한다.


&nbsp;
### [**7계층 : 애플리케이션 계층** *Application Layer*](https://github.com/AtomicLiquors/Network_Wiki_Chb/blob/main/1.OSI%207%EA%B3%84%EC%B8%B5/7계층.md)

&nbsp;
### [**6계층 : 표현 계층** *Presentation Layer*](https://github.com/AtomicLiquors/Network_Wiki_Chb/blob/main/1.OSI%207%EA%B3%84%EC%B8%B5/6계층.md)


&nbsp;
### [**5계층 : 세션 계층** *Session Layer*](https://github.com/AtomicLiquors/Network_Wiki_Chb/blob/main/1.OSI%207%EA%B3%84%EC%B8%B5/5계층.md)

 
&nbsp;
## 하위 계층 / 데이터 플로 계층 (1-4)


네트워크 엔지니어가 관여할 영역.  
따라서 네트워크 엔지니어는 상향식(bottom-up)으로 네트워크를 파악한다.

 
&nbsp;
### [**4계층 : 전송 계층** *Transport Layer*](https://github.com/AtomicLiquors/Network_Wiki_Chb/blob/main/1.OSI%207%EA%B3%84%EC%B8%B5/4계층.md)

↓ 헤더를 추가하고 3계층으로 내려보낸다.

### [**3계층 : 네트워크 계층** *Network Layer*](https://github.com/AtomicLiquors/Network_Wiki_Chb/blob/main/1.OSI%207%EA%B3%84%EC%B8%B5/3계층.md)


"IP 주소"   



### [**2계층 : 데이터링크 계층** *Data Link Layer*](https://github.com/AtomicLiquors/Network_Wiki_Chb/blob/main/1.OSI%207%EA%B3%84%EC%B8%B5/2계층.md)



"MAC 주소"


 
&nbsp;
### [**1계층 : 물리 계층** *Physical Layer*](https://github.com/AtomicLiquors/Network_Wiki_Chb/blob/main/1.OSI%207%EA%B3%84%EC%B8%B5/1계층.md)

전기 신호를 재생성하여 정확히 전달.  
주소 개념이 없으므로 모든 포트에 같은 전기 신호를 전송한다.  
(물론 전기 신호가 들어온 포트는 제외)

허브, 리피터, 케이블, 커넥터, 트랜시버, 탭


&nbsp;

**Q. 2계층 통신 / 3계층 통신이란?**  
**A.** 정확히는 "로컬 네트워크 통신", "원격지 네트워크 통신"으로  
원래 정확한 표현은 아닌데 실무에서 많이 쓰는 표현입니다.  
- 로컬 네트워크에서 직접 통신할 경우,  
출발지와 목적지가 같은 네트워크에 존재합니다.  
<br>
이 때 라우터와 같은 3계층 네트워크 장비의 도움이 필요하지 않으므로,  
2계층까지만 정보를 확인해 통신하며  
브로드캐스트를 이용해 ARP요청을 보냅니다.
 
&nbsp;
 

- 원격지 네트워크와 통신할 경우,  
출발지와 목적지가 다른 네트워크에 존재합니다.  
<br>
이 때는 라우터와 같은 3계층 네트워크 장비의 도움이 필요하여,   
3계층까지 정보를 확인해야 통신이 가능합니다.
 
&nbsp;
  

[<<메인으로](https://github.com/AtomicLiquors/Network_Wiki_Chb)

&nbsp;  
&nbsp;  
# 네트워크 연결과 구성요소
 
예전에는 LAN, MAN, WAN에서 사용하는 기술이 모두 달랐습니다.  
(소모 비용, 신뢰도, 구축과 관리 등)   
사용하는 프로토콜이나 전송 기술에 따라 쉽게 구분할 수 있었습니다.    

현재는 대부분의 기술이 이더넷으로 통합되면서   
사용자가 전송 기술을 구분하는 건 무의미해지고,   
관리 범위 기준으로 통용되는 개념입니다.  

 
## 네트워크 연결 구분
&nbsp;
 
### **LAN** *Local Area Network*
사용자 내부 네트워크

과거에는 스위치같이 비교적 간단한 정비로 연결하였다.
관리 범위 기준으로는 
 
&nbsp;
 
### **MAN** *Metro Area Network*
도시 단위 네트워크
 
&nbsp;
 
### **WAN** *Wide Area Network*
멀리 떨어진 LAN을 연결하는 네트워크.
자기 땅이나 자기 건물이 아닌 곳과 통신해야 할 때.

웬만하면 직접 구축할 수 없기 때문에   
통신사(KT, SKB 등) 회선을 임대한다.
 
&nbsp;
 
&nbsp;
 
## 네트워크 회선
### 인터넷 회선
통신사와 케이블만 연결한다고 인터넷이 가능한 것이 아니다.  
통신사가 판매하는 인터넷과 연결하는 회선을 사용해야 한다. 
인터넷 전용 회선
광랜(ㅒ이더넷), FTTH, 동축 케이블 인터넷, xDSL
 
&nbsp;
 


## 전용회선
가입자와 통신사업자 간 **대역폭을 보장**해주는 서비스

## 인터넷 전용회선
인터넷 연결 회선에 대해 대역폭을 보장해주는 서비스
'가입자가 통신사와 연결되고, 이 연결이 다시 인터넷과 연결되는 구조'  

일반 가정의 접속기술과 달리, 다른 가입자와 경쟁하지 않고도 연결 품질이 보장된다. 

TDM *Time Division Multiplexing* : 시분할 다중화 


## VPN
### 통신사업자 VPN
### 가입자 VPN

## WDM, DWDM *(Dense) Wavelength Division Multiplex*
파장 분할 다중화 기술

하나의 광케이블에 다양한 파장을 가진 빛을 이용해 여러 개의 채널을 만든다.  
많은 데이터를 전송할 수 있다.  
 
&nbsp;
DWDM은 WDM보다 채널이 많다. 
 
&nbsp;
 

그전에는 하나의 광케이블에 하나의 통신만 가능했다.  
통신사는 가입자들을 구분하고 대역폭 높은 통신을 제공해야 해서  
케이블 여러 대를 포설해야 하는 어려움이 있었다.  

- FTTH *Fibre To The Home*  
- PTP *Point-to-Point*  
- AON *Active Optical Network*  
- PON *Passive Optical Network*  

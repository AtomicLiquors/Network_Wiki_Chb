[<<메인으로](https://github.com/AtomicLiquors/Network_Wiki_Chb)

&nbsp;  
&nbsp;  

# **Loop**
네트워크에 연결된 모양이 고리처럼 되돌아오는 형태로 구성되는 상황  

 
&nbsp;
 

## **루프의 원인**
### **브로드캐스트 스톰**
스위치는 브로드캐스트가 발생하면 플러딩을 일으킨다.  

루프 구조의 네트워크에서 브로드캐스트가 발생하면,  
스위치에서 다른 스위치로 연쇄적으로 플러딩이 발생한다.  
플러딩된 패킷이 계속 돌아가며 패킷 하나가 전체 대역폭을 차지하고,  
모든 단말이 시스템 리소스를 소모하면서  
단말 간 통신이 불가능에 이르게 된다.  

증상 
- 단말 속도가 느려짐, CPU 사용률 증가
- 네트워크 접속 속도 느려짐
- 네트워크에 설치된 스위치에 모든 LED가 동시에 빠르게 점멸

 
&nbsp;
 
### **MAC 어드레스 플래핑**
스위치는 MAC 주소를 습득하고 출발지 포트 정보를 저장한다..  

루프 구조를 따라가면  
스위치에 동일한 MAC 주소가 여러 포트를 통해 유입되고  
학습이 정상적으로 이루어지지 않는다.  
 
&nbsp;
 
&nbsp;
 

 
## **관련 프로토콜**
**STP** *Spanning Tree Protocol*  
루프를 자동 감지하고 적절하게 포트를 닫았다가 다시 열어서 장애를 예방하는 프로토콜.  

 
&nbsp;
 

**BPDU** *Bridge Protocol Data Unit*  
스위치끼리 정보를 전달받아 전체 네트워크 트리를 파악하고,  
루프 구간을 확인하는 프로토콜. 

**RSTP, MST**  
*Rapid Spanning Tree Protocol*
*Multiple Spanning Tree*
Vlan 개수와 상관없이 하나만 동작하는 일반적인 Spanning Tree(CST)와   
VLAN마다 지정되는 Per Vlan Spanning Tree의 단점을 보완.
향상된 STP.


**SLPP Extreme STP Loop Guard BPDU Guard**
### 인코딩은 암호화와 다른가
**인코딩:**   
공개적으로 사용 가능한 방법을 통해 데이터를 변환하는 것.   
다른 시스템에서의 데이터 유용성을 높이고 저장에 필요한 공간을 줄이려는 의도로 이루어진다.   
예를 들어 문자 'A'는 아스키코드 65번으로 표시된다.   
인코딩된 데이터는 표준방법을 사용하여 쉽게 디코딩할 수 있다.

**암호화:**   
데이터를 비밀로 유지하려는 의도로 데이터를 변환하는 것.   
암호 알고리즘을 이용해 데이터를 암호화하고 특수 키를 사용하여 암호를 해독한다.   
예를 들어 대칭키, 공개키 방식.

&nbsp;  

### Authentication v Authorization
인증(authentication)은 자신이 누구라고 주장하는 사람을 확인하는 절차이다.   
권한부여(authorization)는 가고 싶은 곳으로 가도록 혹은 원하는 정보를 얻도록 허용하는 과정이다.

&nbsp;  


### Password 보안
단순한 ID/PW 기반 인증체계에서 PW(패스워드)는 웹사이트 관리자에게 무방비하게 노출되며, 키 입력 감지 등을 통해 외부로 유출될 위험도 높습니다. 반면 한번 PW를 취득하면 해당 계정에 대해 무제한적인 권한을 얻게 됩니다. 게다가 대부분의 인터넷 이용자는 여러 사이트에 걸쳐 동일한 ID와 패스워드를 사용하므로, PW가 한 번 노출되는 것만으로도 여러 사이트의 계정이 피해를 입을 수 있습니다.


&nbsp;  

504 Timeout

백엔드 서버 측 호출을 만든 Ajax 자바스크립트를 검토하기 시작했습니다. 불행히도 자바 스크립트에는 오류 처리 코드가 없습니다. 따라서 오류 코드가 발생하면 처리되지 않고 화면에 진행률 표시줄이 영원히 표시됩니다.
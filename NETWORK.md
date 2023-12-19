<details>
  <summary><h3>1. OSI 7계층?</h3></summary>
  <ul>
    <li> OSI 7계층은 네트워크의 통신 과정을 7개의 계층으로 나눈 모델입니다. </li>
    <ul>
      <li> Physical Layer (물리 계층) : 실제 장치들을 통해 데이터를 전송합니다. </li>
      <li> Data Link Layer (데이터 링크 계층) : 네트워크 기기들 사이의 데이터 전송 및 물리 주소를 관리합니다. </li>
      <li> Network Layer (네트워크 계층) : 다양한 네트워크 간의 통신 경로를 선택합니다. </li>
      <li> Transport Layer (전송 계층) : 호스트 간의 신뢰성 있는 데이터 전송을 담당합니다. </li>
      <li> Session Layer (세션 계층) : 통신 세션을 구성하고 관리합니다. </li>
      <li> Presentation Layer (표현 계층) : 데이터의 표현 방식을 관리하고 암호화합니다. </li>
      <li> Application Layer (응용 계층) : 사용자와 가장 가깝게 위치하며, 사용자의 요청과 응답을 처리합니다. </li>
    </ul>
    <li> Transport Layer는 데이터의 신뢰성 있는 전송을 담당하며, 이를 위해 세그먼트라는 단위로 데이터를 분할하고, 오류 검출, 재전송, 흐름 제어 등을 수행합니다. </li>
    <li> Network Layer는 다양한 네트워크 간의 통신 경로를 선택하고, 이를 위해 패킷이라는 단위로 데이터를 분할합니다. 라우팅, IP 주소 할당 등의 역할을 합니다. </li>
    <li> L3 스위치는 기본적으로 스위치의 기능을 가지면서 라우터의 기능을 일부 가지고 있는 장비로, 빠른 속도로 데이터를 전송하면서도 라우팅 기능을 수행할 수 있습니다. </li>
    <li> 라우터는 네트워크 계층에서 동작하며, 다양한 네트워크 간의 통신 경로를 선택하는 역할을 합니다. </li>
    <li> 각 계층의 단위 </li>
    <ul>
      <li> Physical Layer : Bit </li>
      <li> Data Link Layer : Frame </li>
      <li> Network Layer : Packet </li>
      <li> Transport Layer : Segment </li>
    </ul>
    <li> 헤더의 Packing Order는 데이터가 송신자로부터 수신자로 전송되는 과정에서 각 계층에서 헤더가 추가되는 순서를 의미합니다. 송신 측에서는 Application Layer에서 Physical Layer로 내려가며 헤더가 추가되고, 수신 측에서는 Physical Layer에서 Application Layer로 올라가며 헤더가 제거됩니다. </li>
    <li> ARP (Address Resolution Protocol)는 IP 주소를 물리적 네트워크 주소로 변환하는 프로토콜입니다. 네트워크에서 통신을 하려면 이 두 주소가 모두 필요하기 때문에 ARP는 중요한 역할을 합니다. </li>
  </ul>
</details>

# CentOS7 install on VirtualBox

다운로드 경로 : "D:\VirtualBox VMs"

### VirtualBox Install

- VirtualBox 6.0.8 [install](https://www.virtualbox.org/wiki/Downloads)
- 



### CentOS7 ISO INSTALL

##### ISO

- ISO Image란 국제 표준화 기구(ISO)가 제정한 광학 디스크의 압축 파일(디스크 이미지)
- 압축된 BD나 CD를 비슷한 디스크 포맷에 포함된 모든 파일을 담고 있고, 압축되지 않은 형태로 저장됨
- 현대에 출시된 가정 및 기업용 컴퓨터 운영 체제에서 기본으로 지원함

##### DVD ISO 설치

- CentOS 7.6.1810 [install](http://isoredirect.centos.org/centos/7/isos/x86_64/CentOS-7-x86_64-DVD-1810.iso)



### VirtualBox 설정

##### 도구 > 환경설정

- 입력
  - 가상머신
    - 호스트 키 조합 : Right Shift (Right Ctrl이 먹지 않아서..)



### 가상머신 만들기

##### 새로 만들기

- 이름 및 운영체제
  - 이름 : CentOS_190621
  - 머신폴더 : D:\VirtualBox VMs
  - 종류 : Linux
  - 버전 : Red Hat (64-bit)
- 메모리 크기
  - 2048MB
- 하드 디스크
  - 지금 새 가상 하드 디스크 만들기
- 하드 디스크 파일 종류
  - VDI(VirtualBox 디스크 이미지)
- 물리적 하드 드라이브에 저장
  - 고정 크기
- 파일 위치 및 크기
  - 경로 : D:\VirtualBox VMs\CentOS7_190621\CentOS7_190621.vdi
  - 크기 : 8.00 GB
- 만들기



##### 만든 가상머신 선택하고 설정

- 저장소
  - 컨트롤러 IDE > 비어 있음
    - 속성 아래 오른쪽 끝 CD모양 클릭 > 가상 광 디스크 파일 선택
    - 아까 다운받아놓은 CentOS-7-x86_64-DVD-1810.iso 선택
- 네트워크
  - 어댑터 2
    - V 네트워크 어댑터 사용하기
    - 호스트 전용 어댑터



##### 시작

- 가상머신 > 시작
- <https://offbyone.tistory.com/30> 참고하여 설치할 것
- <https://www.inflearn.com/course/%EC%9D%B4%EA%B2%83%EC%9D%B4-%EB%A6%AC%EB%88%85%EC%8A%A4%EB%8B%A4/lecture/666> 강의도 참고










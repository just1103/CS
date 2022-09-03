# OS

[http://www.kocw.net/home/search/kemView.do?kemId=1046323](http://www.kocw.net/home/search/kemView.do?kemId=1046323)
이화여대 반효경
2022/09 ~

# Operating System

- OS, 운영체제란?
    
    컴퓨터 하드웨어 바로 위에 설치되어 사용자 및 다른 모든 스프트웨어, 하드웨어를 연결하는 소프트웨어 계층
    
    하드웨어 바로 윗단의 소프트웨어이다. 
    
    ![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/10479cc1-791e-4fda-b514-a67ee7a732cc/Untitled.png)
    
    - 좁은 의미 : 커널. 운영체제 핵심으로 메모리에 상주하는 부분
    - 넓은 의미 : 커널 + 주변 시스템 유틸리티 포함
- OS의 목적
    - 컴퓨터 시스템을 편리하게 사용할 수 있는 환경을 제공
        
        하드웨어를 직접 다루는 복잡한 부분을 OS가 대행
        
    - 컴퓨터 시스템의 자원을 효율적으로 관리
        
        - 하드웨어 자원인 프로세서 (CPU (central processing unit) 기억, 해석, 연산, 제어), 기억장치, 입출력 장치를 관리
           - 사용자간 형평성 있는 자원 분배, 한정된 자원으로 최대한 성능을 내도록
        - 사용자, OS 자신을 보호
        - 소프트웨어 자원인 (프로세스, 파일, 메시지) 관리
        
- OS 분류
    - 동시작업 가능여부
        - 단일 작업 (single tasking) : 예전에는 한 번에 1개 프로그램만 처리 가능했음 (ex. MS-DOS 프롬프트, 옛날 핸드폰, 엘리베이터 등 특수목적의 기기) → 단일 사용자만 접속 가능
        - 다중 작업 (multi tasking) : 동시에 2개 이상의 작업 처리 (ex. UNIX, MS Windows)
    - 사용자의 수
        - 단일 (MS-DOS) 사용자 / 다중 (UNIX 여러 계정을 생성 가능) 사용자
    - 처리방식
        - 일괄 처리 (batch processing) : 작업을 일정량 모아서 한꺼번에 처리
        - 시분할 (time sharing) : 여러 작업 수행할 때 OS가 작은 시간 단위로 컴퓨터 처리능력을 분할하여 사용. 물리적으로 동시에 진행되지 않지만, 사람이 느끼기에는 interactive함 (짧은 응답시간)
        - 범용 컴퓨터
        - 실시간 (realtime) : 정해진 시간 내 작업이 반드시 종료됨을 보장해야 하는 시스템을 위한 OS
        - 특수목적 컴퓨터. 원자로/미사일 제어
- 용어
    - multi tasking : 다중 작업. 물리적으로 동시에 진행되지 않지만, 사람이 느끼기에는 interactive함
    - multi programming : 메모리에 여러 프로그램이 올라가 있음을 강조
    - time sharing : 시분할 CPU 강조
    - multi process
    - multi processor : 1개 PC에 여러개 CPU가 붙어있음
- UNIX 유닉스 계열의 OS
    - 다중 사용자, 유닉스 OS를 만들기 위해 C언어가 개발됨, 높은 이식성 (다른 PC에서도 사용 가능), 최소한의 커널 구조
    - 다양한 버전 (Linux 등) *안드로이드도 Linux 커널을 사용함
- DOS 계열의 OS
    - 단일 사용자, MS사에서 개인 PC용으로 개발
- OS의 구조
    - CPU 스케줄링에서는 선착순으로 처리하면 비효율적
    → CPU는 너무 빠르니까 여러 작업을 조금씩 번갈아가면서 처리하는 게 효율적
    - 메모리 관리
    → 한정된 메모리. 프로그램이 늘어날수록 용량을 관리. 그때그때 사용중인 프로그램에게 몰아주기
    - 파일 관리. 디스크에 파일을 어떻게 보관할까?
    → 디스크의 특성에 맞게 관리, 디스크 스케쥴링해서 head가 덜 이동하도록 할까
    - 입출력 관리. I/O Device는 느린데, 컴퓨터와 어떻게 정보를 주고 받게 할까?
    → interupt를 걸어서 CPU가 방해받지 않도록 함
    - 프로세스 관리, 보호 시스템, 네트워킹, 명령어 해석기…

# System Structure & Program Execution

# Process

# Process Management

# CPU Scheduling

# Process Synchronization

# Deadlocks

# Memory Management

# Virtual Memory

# File System

# Disk Management & Scheduling

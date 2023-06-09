# [ 📖 알고리즘/자료구조 백과사전 📖 ]

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fmclub4%2FBaekjoon%2Ftree%2Fmain%2F%25EB%25B0%25B1%25EC%25A4%2580%2F%25EC%2595%258C%25EA%25B3%25A0%25EB%25A6%25AC%25EC%25A6%2598%2520%25EC%25A0%2595%25EB%25A6%25AC&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

<br>

------------------------

## ⚠️ 주의사항 ⚠️ 

- 본 문서는 개인적인 공부를 위해 이곳저곳에 흩어져있는 컴퓨터 관련 전공 지식을 한곳에 정리해 둔 문서임. 그니깐 뭐가 어쨌고 딴지 ㄴㄴ

- 간단한 기초 알고리즘 부터 어려운 알고리즘까지 익힐 수 있는 기본 문제들과 그 알고리즘을 응용하는 문제들을 난이도 별로 모아서 공부하기 위해서 만듦. 플레티넘에 해당하는 알고리즘은 잘 모르는데 일단 집어 넣은거라 질이 안좋을 수도 있음. 

- 문서의 길이가 길어서 왔다갔다 편하게 할려고 중간에 버튼을 만들어둠. 목차에서 원하는 항목 선택하면 그곳으로 워프함. 또한, 각 장 맨 처음에 목차로 돌아오는 버튼을 만들고, 각 장의 각 난이도마다 맨 밑에 장의 처음으로 돌아가는 버튼을 만들어둠.

- ☢️기초적인 것 부터 대회용 어려운 알고리즘까지 존재하는 거의 모든 알고리즘 다 있으니 왠만하면 플래티넘부턴 알잘딱으로 거를 것. 보통 코딩 테스트는 골드에 있는 알고리즘들 까지만 츨제되고 난이도는 어려운건 골드1~3정도, 가끔가다 플레5정도 나온다고 함☢️

----------------------------------

<br>

# 📌 < 목차 >

[ 1.시작하기 전에 ](#--시작하기-전에-)

[ 2. 기초 알고리즘 ](#--기초-)

[ 3. 자료구조 ](#--자료구조-)

[ 4. 그래프 ](#--그래프-)

[ 5. DP/분할 ](#--dp분할-)

[ 6. 수학 ](#--수학-)

[ 7. 기하학 ](#--기하학-)

[ 8. 문자열 알고리즘 ](#--문자열-알고리즘-)

[ 9. 기타 알고리즘 ](#--기타-알고리즘-)

<br>

-----------------------------------------------

<br>

# 📌 < 시작하기 전에 >

[ * 목차로 가기 ](#--목차-)

### - 시작하기 전에

- #### 설명

  - [PS의 기초](https://anz1217.tistory.com/147)
  - [시간 복잡도](https://bblackscene21.tistory.com/7)
  - [백준 푼 문제 자동으로 git에 올리기](https://github.com/BaekjoonHub/BaekjoonHub)
  
### - IDE

- #### 설명

  - [VS Code (통합 개발 IDE)](https://code.visualstudio.com/)
  - [Vs Code 단축키](https://www.youtube.com/watch?v=mh-0twurNRE&t=172s&ab_channel=%EC%BD%94%EB%94%A9%EC%95%A0%ED%94%8C)
  - [IntelliJ (Java, Kotlin)](https://www.jetbrains.com/ko-kr/idea/download/#section=windows)
  - [IntelliJ 한글화](https://zero-iron.tistory.com/5)
  - [IntelliJ 자동 import](https://tychejin.tistory.com/340)
  - [CLion (C++)](https://www.jetbrains.com/clion/promo/?source=google&medium=cpc&campaign=11960744627&term=clion&content=489240779909&gclid=Cj0KCQjwuLShBhC_ARIsAFod4fJ3eyp3YRm7c2KZOLPlZ0CJYdXOnQE-fcLTU_Mx0xwzzDGrY8b-T2gaAgc2EALw_wcB)
  - [CLion WSL 설정](https://nnnlog.tistory.com/54)
  - [PyCharm (Python)](https://www.jetbrains.com/ko-kr/pycharm/download/#section=windows)
  - [Jetbrains IDE 학생 라이센스 등록](https://www.jetbrains.com/ko-kr/community/education/#students)

### - C++

- #### 설명

  - [STL](https://anz1217.tistory.com/22)
  - [포인터](https://boycoding.tistory.com/199)
  - [네임스페이스](https://blockdmask.tistory.com/474)

### - Java

- #### 설명
  
  - [BufferedReader (빠른 I/O)](https://blog.naver.com/ka28/221850826909)
  - [StringTokenizer (문자열 분리)](https://jhnyang.tistory.com/entry/JAVA-StringTokenizer-%ED%81%B4%EB%9E%98%EC%8A%A4%EB%A1%9C-%EB%AC%B8%EC%9E%90%EC%97%B4-%EB%B6%84%EB%A6%AC%ED%95%98%EA%B8%B0-split-%EB%B9%84%EA%B5%90)
  - [StringBuilder (I/O 모았다가 한번에 출력)](https://onlyfor-me-blog.tistory.com/317)
  - [Iterator](https://onlyfor-me-blog.tistory.com/319)
  - [Comparator](https://lookingfor.tistory.com/entry/%EC%9E%90%EB%B0%94-%EB%AC%B8%EC%9E%90%EC%97%B4-%EB%B9%84%EA%B5%90-%ED%95%A8%EC%88%98-compare-compareTo)
  - [Collection](https://gangnam-americano.tistory.com/41)
  - [Long보다 큰 수 비교하기 (BigInteger)](https://coding-factory.tistory.com/604)

### - 코딩 문제 사이트

- #### 설명
 
  - [백준](https://www.acmicpc.net/)
  - [Solved AC(백준 난이도 티어)](https://solved.ac/)
  - [프로그래머스](https://school.programmers.co.kr/learn/challenges?order=recent)
  - [CodeForces](http://codeforces.com/)
  - [AtCoder](https://atcoder.jp/)
  - [LeetCode](https://leetcode.com/)
 
### - 백준 문제 내 풀이

  - [백준 문제 내 풀이 정리](https://somber-purple-9f8.notion.site/36cbcd2d6b0d4bb9b9b3db6d77ff54fd?pvs=4)
    
<br>

-----------------------------------------------

<br>

# 📌 < 기초 >

[ * 목차로 가기 ](#--목차-)

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/1.svg"/> [ 브론즈 ]

### - 진법 변환

- #### 알고리즘 설명

  - [진법 변환](https://blog.naver.com/icbanq/221727893563)
  - [2의 보수](https://life-with-coding.tistory.com/298)

- #### 기본 문제

   - [[브론즈4] 이진수 연산](https://www.acmicpc.net/problem/12813)

### - 브루트포스 알고리즘 (⭐ 중요 ⭐)

- #### 알고리즘 설명

  - [브루트포스](https://foreverhappiness.tistory.com/104)
  
- #### 참고 자료

  - [백트래킹과 매우 유사함](#--백트래킹)

- #### 기본 문제
  
  - [[브론즈2] 블랙잭](https://www.acmicpc.net/problem/2798)
  - [[실버4] 설탕배달](https://www.acmicpc.net/problem/2839)

- #### 응용 문제
 
  - [[브론즈2] 블랙잭](https://www.acmicpc.net/problem/2798)
  - [[브론즈2] 분해합](https://www.acmicpc.net/problem/2231)
  - [[브론즈1] 일곱 난쟁이](https://www.acmicpc.net/problem/2309) (!!추천!!)
  - [[실버4] 체스판 다시 칠하기](https://www.acmicpc.net/problem/1018)
  - [[실버2] 마인크래프트](https://www.acmicpc.net/problem/18111)
  - [[골드5] 리모컨](https://www.acmicpc.net/problem/1107) (!!추천!!)
  - [[골드5] 틱택토](https://www.acmicpc.net/problem/7682)
  - [[골드4] 램프](https://www.acmicpc.net/problem/1034)
  - [[플레5] 쿨한 물건 구매](https://www.acmicpc.net/problem/1214) (!!추천!!)
 
## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/6.svg"/> [ 실버 ]

### - 재귀 (🌟🌟 진짜 중요 🌟🌟)

- #### 알고리즘 설명

  - [재귀](https://medium.com/@sunnkis/%EB%8D%B0%EC%9D%B4%ED%84%B0-%EA%B5%AC%EC%A1%B0-%EC%9E%AC%EA%B7%80-8d96633be4cd)

- #### 참고 자료

  - [하노이탑](https://mgyo.tistory.com/185)

- #### 기본 문제

  - [[실버5] 재귀함수가 뭔가요?](https://www.acmicpc.net/problem/17478)
- #### 응용 문제
 
  - [[실버1] 하노이탑 이동 순서](https://www.acmicpc.net/problem/11729) (!!추천!!)
  - [[골드5] 별 찍기 - 10](https://www.acmicpc.net/problem/2447)
  - [[골드2] 하노이탑](https://www.acmicpc.net/problem/2270)
  
### - 그리디 알고리즘 (⭐ 중요 ⭐)

- #### 알고리즘 설명

  - [그리디](https://velog.io/@cha-suyeon/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-%EA%B7%B8%EB%A6%AC%EB%94%94Greedy-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%EA%B3%BC-%EC%98%88%EC%A0%9C-%ED%8C%8C%EC%9D%B4%EC%8D%AC)

- #### 기본 문제

  - [[실버4] 동전 0](https://www.acmicpc.net/problem/11047)

- #### 응용 문제
 
  - [[실버4] ATM](https://www.acmicpc.net/problem/11399)
  - [[실버3] 안테나](https://www.acmicpc.net/problem/18310) (!!추천!!)
  - [[실버3] 주유소](https://www.acmicpc.net/problem/13305) (!!추천!!)
  - [[실버1] 회의실 배정](https://www.acmicpc.net/problem/1931) (!!추천!!)
  - [[골드5] 주사위](https://www.acmicpc.net/problem/1041)
  - [[골드5] 강의실 배정](https://www.acmicpc.net/problem/11000)
  - [[골드5] A와 B](https://www.acmicpc.net/problem/12904) (!!추천!!)
  - [[골드5] 센서](https://www.acmicpc.net/problem/2212) (!!추천!!)
  - [[골드5] 행복 유치원](https://www.acmicpc.net/problem/13164)
  - [[골드5] 도서관](https://www.acmicpc.net/problem/1461)
  - [[골드5] 꿀 따기](https://www.acmicpc.net/problem/21758)
  - [[골드5] 전구와 스위치](https://www.acmicpc.net/problem/2138)
  - [[골드4] 정육점](https://www.acmicpc.net/problem/2258)
  - [[골드4] 우체국](https://www.acmicpc.net/problem/2141)
  - [[골드4] 돌의 정령 줄세우기](https://www.acmicpc.net/problem/24025)
  - [[골드3] 공주님의 정원](https://www.acmicpc.net/problem/2457)
  - [[골드2] 보석 도둑](https://www.acmicpc.net/problem/1202) (!!추천!!)
  - [[골드2] 택배](https://www.acmicpc.net/problem/8980)
  - [[골드2] 컵라면](https://www.acmicpc.net/problem/1781)
  - [[골드1] 멀티탭 스케줄링](https://www.acmicpc.net/problem/1700)
  - [[골드1] 소가 길을 건너간 이유 4](https://www.acmicpc.net/problem/14464) 

<br>

-----------------------------------------------

<br>

# 📌 < 자료구조 >

[ * 목차로 가기 ](#--목차-)

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/1.svg"/> [ 브론즈 ]

### - 배열

- #### 알고리즘 설명

  - 

- #### 기본 문제

 [* 해당 장 맨 위로 바로가기](#--자료구조-)

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/6.svg"/> [ 실버 ]

### - 링크드 리스트

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - [[실버3] 풍선 터뜨리기](https://www.acmicpc.net/problem/2346)

- #### 응용 문제

### - 스택 (🌟🌟 진짜 중요 🌟🌟)

- #### 알고리즘 설명

  - [ 스택 ](https://roi-data.com/entry/%EC%9E%90%EB%A3%8C%EA%B5%AC%EC%A1%B0-4-%EC%8A%A4%ED%83%9DStack%EC%9D%B4%EB%9E%80-%EC%97%B0%EC%82%B0-%EA%B5%AC%ED%98%84%EB%B0%A9%EB%B2%95)

- #### 기본 문제

  - [[실버4] 스택](https://www.acmicpc.net/problem/10828)

- #### 응용 문제

  - [[실버4] 괄호](https://www.acmicpc.net/problem/9012)
  - [[실버2] 스택 수열](https://www.acmicpc.net/problem/1874)
  - [[실버1] 외계인의 기타 연주](https://www.acmicpc.net/problem/2841)
  - [[골드5] 탑](https://www.acmicpc.net/problem/2493)
  - [[골드5] 옥상 정원 꾸미기](https://www.acmicpc.net/problem/6198) (!!추천!!)
  - [[골드5] 괄호 제거](https://www.acmicpc.net/problem/2800)
  - [[골드5] 스카인라인 쉬운거](https://www.acmicpc.net/problem/1863)
  - [[골드4] 문자열 폭발](https://www.acmicpc.net/problem/9935)
  - [[골드4] 오큰수](https://www.acmicpc.net/problem/17298)
  - [[골드4] PPAP](https://www.acmicpc.net/problem/16120)
  - [[골드3] 크게 만들기](https://www.acmicpc.net/problem/2812)
  - [[골드2] 후위 표기식](https://www.acmicpc.net/problem/1918) (!!추천!!)
  - [[플레5] 오아시스 재결합](https://www.acmicpc.net/problem/3015) (!!추천!!)

### - 큐/덱 (🌟🌟 진짜 중요 🌟🌟)

- #### 알고리즘 설명

  - [큐](https://monsieursongsong.tistory.com/5)
  - [원형큐](https://velog.io/@mcc919/Data-Structure-%EC%9B%90%ED%98%95-%ED%81%90Circular-Queue-%EC%95%8C%EC%95%84%EB%B3%B4%EA%B8%B0)
  - [덱](https://leejinseop.tistory.com/39)

- #### 참고 자료

  - [파이썬에서 큐와 덱의 속도 차이](https://programming119.tistory.com/184)

- #### 기본 문제

  - [[실버4] 큐2](https://www.acmicpc.net/problem/18258)
  - [[실버4] 회전하는 큐](https://www.acmicpc.net/problem/1021)
  - [[실버4] 덱](https://www.acmicpc.net/problem/10866)
  
- #### 응용 문제
 
  - [[실버5] 요세푸스 문제 0](https://www.acmicpc.net/problem/11866)
  - [[실버4] 큐](https://www.acmicpc.net/problem/10845)
  - [[실버4] 카드2](https://www.acmicpc.net/problem/2164)
  - [[실버1] 트럭](https://www.acmicpc.net/problem/13335) (!!추천!!)
  - [[골드5] AC](https://www.acmicpc.net/problem/5430)
  - [[골드4] 뱀](https://www.acmicpc.net/problem/3190)
  - [[골드1] 정렬 게임](https://www.acmicpc.net/problem/13415)

### - 우선순위 큐/힙 (🌟🌟 진짜 중요 🌟🌟)

- #### 알고리즘 설명

  - [우선 순위 큐](https://suyeon96.tistory.com/31)

- #### 기본 문제

  - [[실버2] 최소힙](https://www.acmicpc.net/problem/1927)
  - [[실버2] 최대힙](https://www.acmicpc.net/problem/11279)

- #### 응용 문제
 
  - [[실버1] 절대값 힙](https://www.acmicpc.net/problem/11286)
  - [[골드4] 이중 우선순위 큐](https://www.acmicpc.net/problem/7662)
  - [[골드4] 화장실의 규칙](https://www.acmicpc.net/problem/19640)
  - [[골드2] 최대 클리크 구하기](https://www.acmicpc.net/problem/13160)
  - [[플레5] 최솟값 찾기](https://www.acmicpc.net/problem/11003)

### - 트리 (⭐ 중요 ⭐)

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - 

- #### 응용 문제

### - 해싱

- #### 알고리즘 설명

  - [해싱](https://ratsgo.github.io/data%20structure&algorithm/2017/10/25/hash/)

- #### 참고 자료

  - [딕셔너리 (파이썬)](https://blockdmask.tistory.com/450)

- #### 기본 문제

  - [[실버4] 숫자 카드 2](https://www.acmicpc.net/problem/10816)

- #### 응용 문제

  - [[실버4] 나는야 포켓몬 마스터 이다솜](https://www.acmicpc.net/problem/1620)
  - [[실버4] 비밀번호 찾기](https://www.acmicpc.net/problem/17219)
  - [[실버4] 듣보잡](https://www.acmicpc.net/problem/1764)
  - [[실버3] 수강신청](https://www.acmicpc.net/problem/13414)
  - [[실버3] 패션왕 신해빈](https://www.acmicpc.net/problem/9375)

 [* 3장으로 바로가기](#--자료구조-)

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/11.svg"/> [ 골드 ]

### - 이진 트리 (⭐ 중요 ⭐)

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - [[골드5] 이진 검색 트리](https://www.acmicpc.net/problem/5639)

- #### 응용 문제

### - 세그먼트트리 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - [[골드1] 구간 합 구하기](https://www.acmicpc.net/problem/2042)

- #### 응용 문제

  - [[플레2] 화성 지도](https://www.acmicpc.net/problem/3392)

 ### - 펜윅 트리

- #### 알고리즘 설명

  - 

- #### 기본 문제


### - 희소배열

- #### 알고리즘 설명

  - [희소배열](https://hello-capo.netlify.app/algorithm-sparse-table/)
  - 최소 공통 조상 (LCA)와 연관이 깊습니다.

- #### 기본 문제

  - [[골드1] 합성함수와 쿼리](https://www.acmicpc.net/problem/17435)

- #### 응용 문제

  - [[골드1] YouTube](https://www.acmicpc.net/problem/3117)
  - [[플레5] 개미](https://www.acmicpc.net/problem/14942)

### - 최소 공통 조상 (LCA)

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - [[골드4] 가장 가까운 공통 조상](https://www.acmicpc.net/problem/3584)
  - [[플레5] LCA 2](https://www.acmicpc.net/problem/11438)

- #### 응용 문제

 [* 3장으로 바로가기](#--자료구조-)
 
<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/16.svg"/> [ 플레티넘 ]
 
 ### - 레이지 프로퍼게이션 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - 

- #### 기본 문제

 ### - 퍼시스턴트 세그먼트 트리

- #### 알고리즘 설명

  - 

- #### 기본 문제

 ### - 머지 소트 트리

- #### 알고리즘 설명

  - 

- #### 기본 문제

 ### - 블록 컷 트리

- #### 알고리즘 설명

  - 

- #### 기본 문제

<br>

-----------------------------------------------

<br>

# 📌 < 그래프 >

[ * 목차로 가기 ](#--목차-)

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/6.svg"/> [ 실버 ]

### - 그래프와 순회 (DFS와 BFS) (🌟🌟 진짜 중요 🌟🌟)

- #### 알고리즘 설명

  - [그래프](https://leejinseop.tistory.com/43)
  - [DFS와 BFS](https://velog.io/@lucky-korma/DFS-BFS%EC%9D%98-%EC%84%A4%EB%AA%85-%EC%B0%A8%EC%9D%B4%EC%A0%90)

- #### 기본 문제

  - [[실버2] DFS와 BFS](https://www.acmicpc.net/problem/1260)

- #### 응용 문제

  - [[실버3] 바이러스](https://www.acmicpc.net/problem/2606)
  - [[실버2] 유기농 배추](https://www.acmicpc.net/problem/1012)
  - [[실버2] 섬의 개수](https://www.acmicpc.net/problem/4963)
  - [[실버2] 연결 요소의 개수](https://www.acmicpc.net/problem/11724)
  - [[실버1] 미로 탐색](https://www.acmicpc.net/problem/2178)
  - [[실버1] 나이트의 이동](https://www.acmicpc.net/problem/7562)
  - [[실버1] 그림](https://www.acmicpc.net/problem/1926) (!!추천!!)
  - [[실버1] 미로 탐색](https://www.acmicpc.net/problem/2178) (!!추천!!)
  - [[실버1] 현수막](https://www.acmicpc.net/problem/14716) (!!추천!!)
  - [[실버1] 안전영역](https://www.acmicpc.net/problem/2468)
  - [[골드5] 적록색약](https://www.acmicpc.net/problem/10026)
  - [[골드5] MooTube (Silver)](https://www.acmicpc.net/problem/15591)
  - [[골드5] 토마토](https://www.acmicpc.net/problem/7576) (!!추천!!)
  - [[골드5] 토마토 (3차원)](https://www.acmicpc.net/problem/7569)
  - [[골드5] 인구 이동](https://www.acmicpc.net/problem/16234) (!!추천!!)
  - [[골드5] 상범 빌딩](https://www.acmicpc.net/problem/6593)
  - [[골드5] 파이프 옮기기1](https://www.acmicpc.net/problem/17070)
  - [[골드5] 맥주 마시면서 걸어가기](https://www.acmicpc.net/problem/9205) 
  - [[골드5] 뱀과 사다리 게임](https://www.acmicpc.net/problem/16928)
  - [[골드4] 연구소](https://www.acmicpc.net/problem/14502)
  - [[골드4] 불](https://www.acmicpc.net/problem/5427)
  - [[골드4] 빙산](https://www.acmicpc.net/problem/2573) (!!추천!!)
  - [[골드4] 테트리미노](https://www.acmicpc.net/problem/14500) (!!추천!!)
  - [[골드4] 탈출](https://www.acmicpc.net/problem/3055)
  - [[골드3] 치즈](https://www.acmicpc.net/problem/2638) (!!추천!!)
  - [[골드3] 전단지 돌리기](https://www.acmicpc.net/problem/19542)
  - [[골드3] 말이 되고픈 원숭이](https://www.acmicpc.net/problem/1600)
  - [[골드3] 성곽](https://www.acmicpc.net/problem/2234)
  - [[골드3] 소문난 칠공주](https://www.acmicpc.net/problem/1941)
  - [[골드3] 벽 부수고 이동하기](https://www.acmicpc.net/problem/2206) (!!추천!!)
  - [[골드3] 아기상어](https://www.acmicpc.net/problem/16236) (!!추천!!)
  - [[골드2] 빵집](https://www.acmicpc.net/problem/3109)
  - [[골드2] 불켜기](https://www.acmicpc.net/problem/11967)
  - [[골드2] 미네랄](https://www.acmicpc.net/problem/2933)
  - [[골드2] 아맞다우산](https://www.acmicpc.net/problem/17244)
  - [[골드2] 스타트 택시](https://www.acmicpc.net/problem/19238)
  - [[골드1] 구슬 탈출2](https://www.acmicpc.net/problem/13460)
  - [[골드1] 달이 차오른다, 가자](https://www.acmicpc.net/problem/1194)
  - [[골드1] 열쇠](https://www.acmicpc.net/problem/9328) (!!추천!!)
  - [[골드1] Metroidvania Extreme](https://www.acmicpc.net/problem/20130)
  - [[골드1] 원수의 원수](https://www.acmicpc.net/problem/23818) (!!추천!!)
  - [[플레5] 백조의 호수](https://www.acmicpc.net/problem/3197) (!!추천!!)

### - BFS와 최단경로 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - [BFS는 왜 최단경로인가?](https://nulls.co.kr/graph/141)
  - 참고로 다엑스트라랑의 차이점은 가중치가 없을때 쓰는 것이다.

- #### 기본 문제

  - [[실버1] 숨바꼭질](https://www.acmicpc.net/problem/1697)
   
- #### 응용 문제

  - [[실버1] 미로 탐색](https://www.acmicpc.net/problem/2178) (!!추천!!)
  - [[골드5] 공주님을 구해라!](https://www.acmicpc.net/problem/17836) (!!추천!!)
  - [[골드5] 물통](https://www.acmicpc.net/problem/2251)
  - [[골드5] 숨바꼭질3](https://www.acmicpc.net/problem/13549)
  - [[골드4] 숨바꼭질2](https://www.acmicpc.net/problem/12851)
  - [[골드4] 숨바꼭질4](https://www.acmicpc.net/problem/13913)
  - [[골드4] 이모티콘](https://www.acmicpc.net/problem/14226) (!!추천!!)
  - [[플레5] 숨바꼭질5](https://www.acmicpc.net/problem/17071)
 

### - DFS와 백트래킹 (⭐ 중요 ⭐)

- #### 알고리즘 설명

  - [백트래킹](https://fomaios.tistory.com/entry/Algorithm-%EB%B0%B1%ED%8A%B8%EB%9E%98%ED%82%B9Backtracking%EC%9D%B4%EB%9E%80)

- #### 기본 문제

  - [[실버3] N과 M (1)](https://www.acmicpc.net/problem/15649) 

- #### 응용 문제
   
  - [[실버3] N과 M(2)](https://www.acmicpc.net/problem/15650)
  - [[실버3] N과 M(3)](https://www.acmicpc.net/problem/15651)
  - [[실버3] N과 M(4)](https://www.acmicpc.net/problem/15652)
  - [[실버3] N과 M(5)](https://www.acmicpc.net/problem/15654) (!! 추천 !!)
  - [[실버3] N과 M(6)](https://www.acmicpc.net/problem/15655)
  - [[실버3] N과 M(7)](https://www.acmicpc.net/problem/15656)
  - [[실버3] N과 M(8)](https://www.acmicpc.net/problem/15657)
  - [[실버3] N과 M(9)](https://www.acmicpc.net/problem/15663)
  - [[실버2] 로또](https://www.acmicpc.net/problem/6603)
  - [[실버2] 스타트와 링크](https://www.acmicpc.net/problem/14889)
  - [[실버1] 연산자 끼워넣기](https://www.acmicpc.net/problem/14888)
  - [[골드5] 치킨 배달](https://www.acmicpc.net/problem/15686) (!! 추천 !!)
  - [[골드5] ABCDE](https://www.acmicpc.net/problem/13023)
  - [[골드5] 암호 만들기](https://www.acmicpc.net/problem/1759)
  - [[골드5] 계란으로 계란치기](https://www.acmicpc.net/problem/16987)
  - [[골드4] N-Queen](https://www.acmicpc.net/problem/9663) (!! 추천 !!)
  - [[골드4] 스도쿠](https://www.acmicpc.net/problem/2580)
  - [[골드4] 연구소](https://www.acmicpc.net/problem/14502)
  - [[골드4] 감시](https://www.acmicpc.net/problem/15683)
  - [[골드4] 알파벳](https://www.acmicpc.net/problem/1987)
  - [[골드4] 사격 연습](https://www.acmicpc.net/problem/27958) (!! 추천 !!)
  - [[골드3] 사다리 조작](https://www.acmicpc.net/problem/15684)
  - [[골드2] 2048(Easy)](https://www.acmicpc.net/problem/12100) (!! 추천 !!)
  - [[골드1] 비숍](https://www.acmicpc.net/problem/1799) (!! 추천 !!)
  - [[플레4] 2048(Hard)](https://www.acmicpc.net/problem/12094)

### - DFS와 순열사이클

- #### 알고리즘 설명

  - [DFS로 사이클 찾기](https://velog.io/@since-1994/%EA%B7%B8%EB%9E%98%ED%94%84-Detection-cycle-%EC%82%AC%EC%9D%B4%ED%81%B4-%EC%B0%BE%EA%B8%B0)

- #### 기본 문제

 - [[실버3] 순열 사이클](https://www.acmicpc.net/problem/10451)
 
- #### 심화 문제

  - [[실버1] 마니또](https://www.acmicpc.net/problem/5107)
  - [[골드4] 섞기 수열](https://www.acmicpc.net/problem/2487)
  - [[골드3] 서울 지하철 2호선](https://www.acmicpc.net/problem/16947) (!! 추천 !!)
  - [[골드2] Swapity Swapity Swap](https://www.acmicpc.net/problem/18783)
  - [[플레4] 사이클의 개수](https://www.acmicpc.net/problem/14441)
  - [[플레1] 짐정리](https://www.acmicpc.net/problem/2569)

[* 4장으로 바로가기](#--그래프-)

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/11.svg"/> [ 골드 ]

### - 분리 집합 (유니온 & 파인드) (🌟🌟 진짜 중요 🌟🌟)

- #### 알고리즘 설명

  - [분리 집합](https://4legs-study.tistory.com/94?category=886581)
  - [최소 스패닝 트리와 연계됨](#--최소-스패닝-트리-mst)

- #### 기본 문제

  - [[골드5] 집합의 표현](https://www.acmicpc.net/problem/1717)

- #### 응용 문제
  
  - [[실버2] 연결 요소의 개수](https://www.acmicpc.net/problem/11724) (유니온 파인드로 더 쉽게 풀림)
  - [[골드4] 여행 가자](https://www.acmicpc.net/problem/1976) (❗추천❗)
  - [[골드4] 사이클 게임](https://www.acmicpc.net/problem/20040) (❗추천❗)
  - [[골드4] 거짓말](https://www.acmicpc.net/problem/1043)
  - [[골드4] 친구비](https://www.acmicpc.net/problem/16562)
  - [[골드3] 피리 부는 사나이](https://www.acmicpc.net/problem/16724) (❗추천❗)
  - [[골드2] 친구 네트워크](https://www.acmicpc.net/problem/4195) (❗추천❗)
  - [[골드2] 공항](https://www.acmicpc.net/problem/10775)
  - [[골드1] 통신말 분할](https://www.acmicpc.net/problem/17398)
  - [[플레5] 네트워크 연결](https://www.acmicpc.net/problem/3780)
  - [[플레3] 교수님은 기다리지 않는다](https://www.acmicpc.net/problem/3830) (❗추천❗)

### - 최소 스패닝 트리 (MST) (⭐ 중요 ⭐)

- #### 알고리즘 설명
  
  - [스패닝 트리](https://limecoding.tistory.com/123)
  - [크루스칼 알고리즘](https://4legs-study.tistory.com/111)
  - [프림 알고리즘](https://4legs-study.tistory.com/112)

- #### 참고 자료

  - [솔린 알고리즘](https://limecoding.tistory.com/127)
  - [네트워크에 스패닝 트리 프로토콜 (참고만)](https://blog.naver.com/spahqhdl/221975163336)

- #### 기본 문제

  - [[골드4] 최소 스패닝 트리](https://www.acmicpc.net/problem/1197)

- #### 응용 문제
 
  - [[골드4] 네트워크 연결](https://www.acmicpc.net/problem/1922)
  - [[골드4] 전력난](https://www.acmicpc.net/problem/6497)
  - [[골드4] 행성 연결](https://www.acmicpc.net/problem/16398)
  - [[골드4] 세부](https://www.acmicpc.net/problem/13905)
  - [[골드4] 도시 분할 계획](https://www.acmicpc.net/problem/1647)
  - [[골드3] 별자리 만들기](https://www.acmicpc.net/problem/4386) (!!추천!!)
  - [[골드3] 슬슬 가지를 먹지 않으면 죽는다](https://www.acmicpc.net/problem/27945)
  - [[골드3] 우주신과의 교감](https://www.acmicpc.net/problem/1774)
  - [[골드3] 정복자](https://www.acmicpc.net/problem/14950)
  - [[골드3] 나만 안되는 연애](https://www.acmicpc.net/problem/14621)
  - [[골드3] Watering the Fields](https://www.acmicpc.net/problem/10021)
  - [[골드3] 학교 탐방하기](https://www.acmicpc.net/problem/13418) (!!추천!!)
  - [[골드3] 불우이웃돕기](https://www.acmicpc.net/problem/1414)
  - [[골드2] 전기가 부족해](https://www.acmicpc.net/problem/10423)
  - [[골드2] 물대기](https://www.acmicpc.net/problem/1368)
  - [[골드1] 다리 만들기 2](https://www.acmicpc.net/problem/17472)
  - [[플레5] 행성 터널](https://www.acmicpc.net/problem/2887) (!!추천!!)
  - [[플레3] 레드 블루 스패닝 트리](https://www.acmicpc.net/problem/4792)

### - 위상 정렬 (⭐ 중요 ⭐)

- #### 알고리즘 설명

  - [위상정렬](https://4legs-study.tistory.com/89)

- #### 기본 문제

  - [[골드3] 줄 세우기](https://www.acmicpc.net/problem/2252)

- #### 응용 문제

  - [[골드3] ACM craft](https://www.acmicpc.net/problem/1005)
  - [[골드3] 게임 개발](https://www.acmicpc.net/problem/1516) (!!추천!!)
  - [[골드3] 음악 프로그램](https://www.acmicpc.net/problem/2623)
  - [[골드2] 문제집](https://www.acmicpc.net/problem/1766) (!!추천!!)
  - [[골드2] 장난감 조립](https://www.acmicpc.net/problem/2637)
  - [[골드2] 쿠키런 킹덤](https://www.acmicpc.net/problem/23632)
  - [[골드1] 최종 순위](https://www.acmicpc.net/problem/3665)

### - 다익스트라 알고리즘/밸만-포드 알고리즘 (최단 경로) (⭐ 중요 ⭐)

- #### 알고리즘 설명

  - [다익스트라 알고리즘](https://velog.io/@717lumos/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-%EB%8B%A4%EC%9D%B5%EC%8A%A4%ED%8A%B8%EB%9D%BCDijkstra-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98)
  - [밸만-포드 알고리즘](https://velog.io/@kimdukbae/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-%EB%B2%A8%EB%A7%8C-%ED%8F%AC%EB%93%9C-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-Bellman-Ford-Algorithm)

- #### 기본 문제

  - [[골드4] 최단 경로](https://www.acmicpc.net/problem/1753) (다익스트라 알고리즘)
  - [[골드4] 타임머신](https://www.acmicpc.net/problem/11657) (밸판-포드 알고리즘)

- #### 응용 문제

  - [[골드5] 숨바꼭질3](https://www.acmicpc.net/problem/13549)
  - [[골드4] 특정한 최단 경로](https://www.acmicpc.net/problem/1504)
  - [[골드3] 웜홀](https://www.acmicpc.net/problem/1865)
  - [[골드3] 거울 설치](https://www.acmicpc.net/problem/2151)
  - [[골드2] 미확인 도착지](https://www.acmicpc.net/problem/9370)
  - [[골드2] 골목길](https://www.acmicpc.net/problem/1738)
  - [[플레5] 할로윈 묘지](https://www.acmicpc.net/problem/3860)
  - [[플레5] KCM Travel](https://www.acmicpc.net/problem/10217)
  - [[플레4] K번째 최단경로 찾기](https://www.acmicpc.net/problem/1854)

### - 폴로이드-위셜 알고리즘 (모든 최단 경로) 

- #### 알고리즘 설명

  - [폴로이드-위셜](https://velog.io/@kimdukbae/%ED%94%8C%EB%A1%9C%EC%9D%B4%EB%93%9C-%EC%9B%8C%EC%85%9C-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-Floyd-Warshall-Algorithm)

- #### 기본 문제

  - [[골드4] 폴로이드](https://www.acmicpc.net/problem/11404)

- #### 응용 문제

  - [[골드4] 운동](https://www.acmicpc.net/problem/1956)
  - [[골드4] 서강 그라운드](https://www.acmicpc.net/problem/14938)
  - [[골드4] 키 순서](https://www.acmicpc.net/problem/2458)
  - [[골드2] 폴로이드 2](https://www.acmicpc.net/problem/11780)

### - 이분 그래프

- #### 알고리즘 설명

  - [이분 그래프](https://gmlwjd9405.github.io/2018/08/23/algorithm-bipartite-graph.html)
  - [레드 블랙 트리](https://blogshine.tistory.com/102)

- #### 참고 자료

  - [리눅스 커널에서 쓰이는 레드 블랙 트리](https://smile2x.tistory.com/36)

- #### 기본 문제

  - [[골드4] 이분 그래프](https://www.acmicpc.net/problem/1707)

- #### 응용 문제

[* 4장으로 바로가기](#--그래프-)

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/16.svg"/> [ 플레티넘 ]

### - 오프라인 쿼리 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - [오프라인 쿼리](https://blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=kks227&logNo=221400731767)

- #### 기본 문제

  - [[플레4] 트리](https://www.acmicpc.net/problem/13306)

- #### 응용 문제

  - [[골드1] 통신망 분할](https://www.acmicpc.net/problem/17398) (❗추천❗)
  - [[골드1] XOR 그룹](https://www.acmicpc.net/problem/14258)
  - [[플레5] Closing the Farm(Gold)](https://www.acmicpc.net/problem/12012) (❗추천❗)
  - [[플레5] Pilot](https://www.acmicpc.net/problem/19670)
  - [[플레4] 꼼꼼한 쿠기의 졸업여행](https://www.acmicpc.net/problem/25172)
  - [[플레4] 수열과 쿼리 22](https://www.acmicpc.net/problem/16978) (❗추천❗)
  - [[플레4] MooTube(Gold)](https://www.acmicpc.net/problem/15586)
  - [[플레4] Snow Boots](https://www.acmicpc.net/problem/15745)
  - [[플레3] 마블](https://www.acmicpc.net/problem/2843)
  - [[플레3] 교수님은 기다리지 않는다](https://www.acmicpc.net/problem/3830)(오프라인쿼리로 더 쉽게풀림) (❗추천❗)
  - [[플레3] 일기예보](https://www.acmicpc.net/problem/14577) (❗추천❗)
  - [[플레3] 라운드 로빈 스케줄러](https://www.acmicpc.net/problem/12016)
  - [[플레3] 트리의 색깔과 쿼리](https://www.acmicpc.net/problem/17469)
  - [[플레3] 강수량](https://www.acmicpc.net/problem/2094)
  - [[플레2] 부스터](https://www.acmicpc.net/problem/15955)

### - 최대 유량 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - [[플레4] 도시 왕복하기 1](https://www.acmicpc.net/problem/17412)

- #### 응용 문제

### - 최소 컷 정리

- #### 알고리즘 설명

  - 

- #### 기본 문제

### - 최소 비용과 최대 유량 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - 

- #### 기본 문제


### - 다닉 알고리즘

- #### 알고리즘 설명

  - 

- #### 기본 문제

### - 강한 연결 요소

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - [[플레5] Strongly Connected Component](https://www.acmicpc.net/problem/2150)

- #### 응용 문제

### - 이중 연결 요소

- #### 알고리즘 설명

  - 

- #### 기본 문제

### - 2-SAT

- #### 알고리즘 설명

  - 

- #### 기본 문제

### - 이분매칭

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - [[플레4] 열혈강호4](https://www.acmicpc.net/problem/11378)

- #### 응용 문제

### - 오일러 경로

- #### 알고리즘 설명

  - [오일러 경로](https://blog.naver.com/PostView.naver?blogId=kks227&logNo=220800097205&categoryNo=0&parentCategoryNo=299&viewDate=&currentPage=8&postListTopCurrentPage=1&from=postList&userTopListOpen=true&userTopListCount=5&userTopListManageOpen=false&userTopListCurrentPage=8)

- #### 기본 문제

  - [[플레4] 오일러 회로](https://www.acmicpc.net/problem/1199)

- #### 응용 문제

[* 4장으로 바로가기](#--그래프-)

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/21.svg"/> [ 다이아 ]

### - A* 알고리즘

- #### 알고리즘 설명

  - [A* 알고리즘](https://itmining.tistory.com/66)

- #### 기본 문제

  - [[다이아1] Product](https://www.acmicpc.net/problem/3764)

[* 4장으로 바로가기](#--그래프-)

<br>

------------------------------------------------------------------

<br>

# 📌 < DP/분할 >

[ * 목차로 가기 ](#--목차-)

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/6.svg"/> [ 실버 ]

### - 동적 계획법 (DP) (🌟🌟 진짜 중요 🌟🌟)

- #### 알고리즘 설명

  - [DP](https://hongjw1938.tistory.com/47)

- #### 참고 자료

  - [DP의 최적화](https://anz1217.tistory.com/130)
  - [LCS 문제랑 냅색 문제랑 연계됨](#--냅색-문제-배낭-문제)
  - [컨벡스 헐 트릭과 연계됨](#--컨벡스-헐-트릭convex-hull-trick)

- #### 기본 문제

  - [[실버3] 피보나치 함수](https://www.acmicpc.net/problem/1003)

- #### 응용 문제
 
  - [[실버3] 1로 만들기](https://www.acmicpc.net/problem/1463)
  - [[실버3] 2xn 타일링](https://www.acmicpc.net/problem/11726) (!!추천!!)
  - [[실버3] 2xn 타일링2](https://www.acmicpc.net/problem/11727)
  - [[실버3] 계단 오르기](https://www.acmicpc.net/problem/2579)
  - [[실버1] 포도주 시식](https://www.acmicpc.net/problem/2156) (!!추천!!)
  - [[실버1] RGB 거리](https://www.acmicpc.net/problem/1149)
  - [[실버1] 동물원](https://www.acmicpc.net/problem/1309)
  - [[실버1] 스티커](https://www.acmicpc.net/problem/9465) (!!추천!!)
  - [[실버1] 카드 구매하기](https://www.acmicpc.net/problem/11052)
  - [[실버1] 구간 합 구하기 5](https://www.acmicpc.net/problem/11660)
  - [[골드5] 알약](https://www.acmicpc.net/problem/4811)
  - [[골드5] 전깃줄](https://www.acmicpc.net/problem/2565)
  - [[골드4] RGB 거리 2](https://www.acmicpc.net/problem/17404)
  - [[골드3] 파일 합치기](https://www.acmicpc.net/problem/11066)
  - [[골드3] 행렬 곱셈 순서](https://www.acmicpc.net/problem/11049) (!!추천!!)
  - [[골드3] Dance Dance Revolution](https://www.acmicpc.net/problem/2342) (!!추천!!)
  - [[골드3] 색상환](https://www.acmicpc.net/problem/2482)
  - [[골드2] 로봇 조종하기](https://www.acmicpc.net/problem/2169)
  - [[골드2] 사전](https://www.acmicpc.net/problem/1256)
  - [[골드1] 방법을 출력하지 않는 숫자 맞추기](https://www.acmicpc.net/problem/13392)
  - [[골드1] 플레이리스트](https://www.acmicpc.net/problem/12872)
  - [[골드1] 펠린드롬 분할](https://www.acmicpc.net/problem/1509)
  - [[플레5] 숫자 맞추기](https://www.acmicpc.net/problem/2494)
  - [[플레5] 연세워터파크](https://www.acmicpc.net/problem/15678)
  - [[플레4] 경찰차](https://www.acmicpc.net/problem/2618)
  
### - 분할 정복 (🌟🌟 진짜 중요 🌟🌟)

- #### 알고리즘 설명

  - [분할 정복](https://anz1217.tistory.com/17)
  - [분할 정복을 이용한 거듭제곱](https://velog.io/@expertinpyo/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-%EC%A0%95%EB%A6%AC-%EB%B6%84%ED%95%A0-%EC%A0%95%EB%B3%B5%EC%9D%84-%EC%9D%B4%EC%9A%A9%ED%95%9C-%EA%B1%B0%EB%93%AD%EC%A0%9C%EA%B3%B1)

- #### 참고 자료

  - [L-트리미노 퍼즐, 최근접 점 쌍 찾기, 분할 정복의 최적화와 연계됨](#--l-트리미노-퍼즐)
  
- #### 기본 문제

  - [[실버2] 색종이 만들기](https://www.acmicpc.net/problem/2630)

- #### 응용 문제
 
  - [[실버2] 종이의 개수](https://www.acmicpc.net/problem/1780)
  - [[실버1] 쿼드트리](https://www.acmicpc.net/problem/1992) (!!추천!!)
  - [[실버1] Z](https://www.acmicpc.net/problem/1074) (!!추천!!)
  - [[실버1] 종이 접기](https://www.acmicpc.net/problem/1802)
  - [[골드5] 별 찍기 - 10](https://www.acmicpc.net/problem/2447)
  - [[골드2] 피보나치의 수 6](https://www.acmicpc.net/problem/11444)
  - [[골드2] 너 봄에는 캡사이신이 맛있단다](https://www.acmicpc.net/problem/15824)
  - [[골드1] 스카이라인](https://www.acmicpc.net/problem/1933)
  - [[골드1] 트리의 순회](https://www.acmicpc.net/problem/2263)
  - [[플레5] 히스토그램에서 가장 큰 직사각형](https://www.acmicpc.net/problem/6549) (!!추천!!)
  - [[플레5] 버블 소트](https://www.acmicpc.net/problem/1517)

### - 분할정복을 이용한 거듭제곱 (⭐ 중요 ⭐)

- #### 알고리즘 설명

  - [분할 정복을 이용한 거듭제곱](https://velog.io/@expertinpyo/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-%EC%A0%95%EB%A6%AC-%EB%B6%84%ED%95%A0-%EC%A0%95%EB%B3%B5%EC%9D%84-%EC%9D%B4%EC%9A%A9%ED%95%9C-%EA%B1%B0%EB%93%AD%EC%A0%9C%EA%B3%B1)

- #### 기본 문제

  - [[실버1] 곱셈](https://www.acmicpc.net/problem/1629)

- #### 응용 문제

  - [[골드5] 비요뜨의 징검다리 건너기](https://www.acmicpc.net/problem/18291) (!!추천!!)
  - [[골드4] 행렬 제곱](https://www.acmicpc.net/problem/10830)
  - [[골드1] 이항 계수 3](https://www.acmicpc.net/problem/11401) (!!추천!!)

### - 비트 마스킹 (⭐ 중요 ⭐)

- #### 알고리즘 설명

  - [비트마스킹](https://rebro.kr/63)

- #### 참고 자료

  - [외판원 순회 문제랑 연계됨](#--외판원-순회) 

- #### 기본 문제

  - [[실버5] 집합](https://www.acmicpc.net/problem/11723)

- #### 응용 문제
 
  - [[실버5] 막대기](https://www.acmicpc.net/problem/1094)
  - [[실버1] 물병](https://www.acmicpc.net/problem/1052)
  - [[골드4] 가르침](https://www.acmicpc.net/problem/1062)
  - [[골드1] 달이 차오른다, 가자.](https://www.acmicpc.net/problem/1194)
  - [[골드1] 계단 수](https://www.acmicpc.net/problem/1562)
  - [[플레5] 박성원](https://www.acmicpc.net/problem/1086)
  - [[플레4] 컨닝](https://www.acmicpc.net/problem/1014)

### - 병합 정렬/버블 정렬/삽입 정렬 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - [분할 정복](https://anz1217.tistory.com/17)

- #### 기본 문제

  - 

- #### 응용 문제
 
  - [[골드1] 달이 차오른다, 가자.](https://www.acmicpc.net/problem/1194)

### - 이분 탐색 (🌟🌟 진짜 중요 🌟🌟)

- #### 알고리즘 설명

  - [완전 탐색](https://anz1217.tistory.com/13)
  - [이분 탐색](https://velog.io/@kimdukbae/%EC%9D%B4%EB%B6%84-%ED%83%90%EC%83%89-%EC%9D%B4%EC%A7%84-%ED%83%90%EC%83%89-Binary-Search)

- #### 기본 문제

  - [[실버4] 수 찾기](https://www.acmicpc.net/problem/1920)

- #### 응용 문제

### - 상한선/하한선 (Upper Bound/Lower Bound) (⭐ 중요 ⭐)

- #### 알고리즘 설명

  - [상한선/하한선](https://jackpot53.tistory.com/m/33)

- #### 기본 문제


- #### 응용 문제

  - [[골드4] 공유기 설치](https://www.acmicpc.net/problem/2110)

[* 5장으로 바로가기](#--dp분할-)

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/11.svg"/> [ 골드 ]

### - 냅색 문제 (배낭 문제) (⭐ 중요 ⭐)

- #### 알고리즘 설명

  - [냅색](https://gsmesie692.tistory.com/113)

- #### 기본 문제

  - [[골드5] 평범한 배낭](https://www.acmicpc.net/problem/12865)

- #### 응용 문제

  - [[골드5] 호텔](https://www.acmicpc.net/problem/1106)
  - [[골드5] 동전](https://www.acmicpc.net/problem/9084)
  - [[골드5] Conins](https://www.acmicpc.net/problem/3067)
  - [[골드5] 벼락치기](https://www.acmicpc.net/problem/14728)
  - [[골드5] 수강 과목](https://www.acmicpc.net/problem/17845)
  - [[골드4] 사탕 가게](https://www.acmicpc.net/problem/4781)
  - [[골드3] 시로코와 은행털기](https://www.acmicpc.net/problem/26607) 
  - [[골드3] 앱](https://www.acmicpc.net/problem/7579)
  - [[골드3] 양팔저울](https://www.acmicpc.net/problem/2629) (!!추천!!)
  - [[골드2] 기업투자](https://www.acmicpc.net/problem/2662)
  - [[골드2] 메이플스토리](https://www.acmicpc.net/problem/20925)
  - [[플레5] 행운 쿠키 제작소](https://www.acmicpc.net/problem/10982)
  - [[플레4] 평범한 배낭2](https://www.acmicpc.net/problem/12920)
  - [[플레4] MT](https://www.acmicpc.net/problem/10265)

### - 최장 공통 부분 수열 (LCS)

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - [[골드5] LCS](https://www.acmicpc.net/problem/9251)

- #### 응용 문제

### - 가장 긴 증가하는 부분 수열 (LIS) (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - [가장 긴 증가하는 부분 수열 (LIS)](https://rebro.kr/33)

- #### 기본 문제
 
  - [[실버2] 가장 긴 증가하는 부분 수열](https://www.acmicpc.net/problem/11053)
  - [[골드2] 가장 긴 증가하는 부분 수열 2](https://www.acmicpc.net/problem/12015)(시간복잡도 : o(nlong n))
  - [[플레5] 가장 긴 증가하는 부분 수열 5](https://www.acmicpc.net/problem/14003)

- #### 응용 문제
  
  - [[골드5] 전깃줄](https://www.acmicpc.net/problem/2565)
  - [[골드4] 가장 긴 증가하는 부분 수열 4](https://www.acmicpc.net/problem/14002)
  - [[골드2] 가장 긴 증가하는 부분 수열 3](https://www.acmicpc.net/problem/12738)
  - [[골드2] 반도체 설계](https://www.acmicpc.net/problem/2352)
  - [[골드2] 꼬인 전깃줄](https://www.acmicpc.net/problem/1365)
  - [[플레5] 전깃줄 - 2](https://www.acmicpc.net/problem/2568)

### - 비트마스킹 DP (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - [DP와 비트마스킹](https://anz1217.tistory.com/39)

- #### 기본 문제

  - [[골드1] 계단수](https://www.acmicpc.net/problem/1562)

- #### 응용 문제

  - [[골드1] 그림 교환](https://www.acmicpc.net/problem/1029)
  - [[골드1] 할 일 정하기 1](https://www.acmicpc.net/problem/1311)
  - [[골드1] 보석 모으기](https://www.acmicpc.net/problem/1480)
  - [[골드1] 끝말잇기](https://www.acmicpc.net/problem/2320)
  - [[골드1] 섞기](https://www.acmicpc.net/problem/1176)
  - [[골드1] 울타리](https://www.acmicpc.net/problem/1139)
  - [[플레5] 발전소](https://www.acmicpc.net/problem/1102)
  - [[플레5] 007](https://www.acmicpc.net/problem/3056)
  - [[플레5] 박성원](https://www.acmicpc.net/problem/1086)
  - [[플레5] 파산하는 왕국](https://www.acmicpc.net/problem/3405)
  - [[플레4] 체스로 도미노를 타자](https://www.acmicpc.net/problem/9936)
  - [[플레4] 프리스비](https://www.acmicpc.net/problem/10649)
  - [[플레3] 두부장수 장홍준](https://www.acmicpc.net/problem/1657)
  - [[플레3] 격자판 채우기](https://www.acmicpc.net/problem/1648)
  - [[플레2] 막대 정사각형](https://www.acmicpc.net/problem/4348)
  - [[다이아5] 내가 어렸을 때 가지고 놀던 장난감](https://www.acmicpc.net/problem/2803)


### - 외판원 순회 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - [[골드1] 외판원 순회](https://www.acmicpc.net/problem/2098)

- #### 응용 문제

  - [[골드1] 외판원 순회3](https://www.acmicpc.net/problem/16991)
  - [[골드1] KUBC League (Small)](https://www.acmicpc.net/problem/14590)
  - [[골드1] 문시티 건설](https://www.acmicpc.net/problem/4888)
  - [[골드1] Pokemon Go Go](https://www.acmicpc.net/problem/16385)
  - [[플레5] 두 단계 최단 경로 4](https://www.acmicpc.net/problem/23840)
  - [[플레5] Bottleneck Travelling Salesman Problem (Large)](https://www.acmicpc.net/problem/24519) (❗추천❗)
  - [[플레4] Island Travels](https://www.acmicpc.net/problem/5852)


[* 5장으로 바로가기](#--dp분할-)

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/16.svg"/> [ 플레티넘 ]

### - L-트리미노 퍼즐

- #### 알고리즘 설명

  - [트리미노 퍼즐](https://velog.io/@qlwb7187/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-L-tailing%ED%8A%B8%EB%A1%9C%EB%AF%B8%EB%85%B8C)

- #### 기본 문제

  - [[플레5] 샤워실 바닥 깔기 (Large)](https://www.acmicpc.net/problem/14601)

### - 최근접 점의 쌍 찾기(Closest Pair of Points)

- #### 알고리즘 설명

  - [최근접 점의 쌍 찾기](https://bblackscene21.tistory.com/11)

- #### 기본 문제

  - [[플레2] 가장 가까운 두 점](https://www.acmicpc.net/problem/2261)

### - 컨벡스 헐 트릭(Convex Hull Trick) (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - [컨벡스 헐 트릭](https://anz1217.tistory.com/143)

- #### 기본 문제

  - [[플레2] 컨벡스 헐 트릭](https://www.acmicpc.net/problem/13263)

- #### 응용 문제

  - [[다이아5] 특공대](https://www.acmicpc.net/problem/4008)
  - [[다이아4] 수열 나누기](https://www.acmicpc.net/problem/10067)

### - 분할 정복 최적화

- #### 알고리즘 설명

  - [분할 정복 최적화](https://anz1217.tistory.com/144)

- #### 기본 문제

  - [[플레1] 탈옥](https://www.acmicpc.net/problem/13261)

- #### 응용 문제

  - [[플레1] 김치](https://www.acmicpc.net/problem/11001)
  - [[플레1] 수열의 OR 점수](https://www.acmicpc.net/problem/13262)
  - [[다이아5] 지사 배정](https://www.acmicpc.net/problem/12766)
  - [[다이아5] 우체국 3](https://www.acmicpc.net/problem/18444)
 
[* 5장으로 바로가기](#--dp분할-)
 
< 
 
------------------------------------------------------------------

<br>

# 📌 < 수학 >

[ * 목차로 가기 ](#--목차-)

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/1.svg"/> [ 브론즈 ]

### - 약수 구하기

- #### 알고리즘 설명

  - [약수 구하기](https://kbw1101.tistory.com/32)

- #### 기본 문제

  - [[브론즈3] 약수 구하기](https://www.acmicpc.net/problem/2501)


### - 소인수 분해 (🌟🌟 진짜 중요 🌟🌟)

- #### 알고리즘 설명

  - [소인수 분해](https://velog.io/@sangwoo_le/%EC%86%8C%EC%9D%B8%EC%88%98%EB%B6%84%ED%95%B4)

- #### 기본 문제

  - [[브론즈1] 소인수 분해](https://www.acmicpc.net/problem/11653)

### - 최대 공약수와 최소공배수 (유클리드 호제법) (🌟🌟 진짜 중요 🌟🌟)

- #### 알고리즘 설명

  - [유클리드 호제법](https://imkh.dev/algorithm-gcd-lcm/)
  - 골드의 "확장 유클리드 호제법"으로도 연결됨

- #### 기본 문제

  - [[브론즈1] 최대공약수와 최소공배수](https://www.acmicpc.net/problem/2609)

- #### 응용 문제

  - [[실버1] 최대공약수](https://www.acmicpc.net/problem/1850)
  - [[골드5] 공약수](https://www.acmicpc.net/problem/2436)
  - [[골드2] 최대공약수 하나 빼기](https://www.acmicpc.net/problem/14476)
  
<br>  
  
## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/6.svg"/> [ 실버 ]

### - 소수 판별 (에라토스테네스의 체)

- #### 알고리즘 설명

  - [소수 판별](https://velog.io/@changhee09/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-%EC%86%8C%EC%88%98%EC%9D%98-%ED%8C%90%EB%B3%84-%EC%97%90%EB%9D%BC%ED%86%A0%EC%8A%A4%ED%85%8C%EB%84%A4%EC%8A%A4%EC%9D%98-%EC%B2%B4)

- #### 기본 문제

  - [[실버4] 에라토스테네스의 체](https://www.acmicpc.net/problem/2960)

- #### 응용 문제
 
  - [[실버3] 소수 구하](https://www.acmicpc.net/problem/1929)
  - [[실버1] 골드바흐의 추측](https://www.acmicpc.net/problem/6588)
  - [[골드5] 신기한 소수](https://www.acmicpc.net/problem/2023)
  - [[골드1] 제곱 ㄴㄴ 수](https://www.acmicpc.net/problem/1016)

### - 선형대 수학

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - [[실버5] 행렬 곱셈](https://www.acmicpc.net/problem/2740)

- #### 응용 문제

  - [[실버5] 부울행렬의 부울곱](https://www.acmicpc.net/problem/14492)
  - [[골드4] 행렬 제곱](https://www.acmicpc.net/problem/10830)
  - [[플레5] 선형 연립 방정식](https://www.acmicpc.net/problem/22940)

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/11.svg"/> [ 골드 ]

### - 확장 유클리드 호제법

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - 

- #### 응용 문제

### - 모듈러 역원 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - 

- #### 응용 문제

### - 페르마의 소정리 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - 

- #### 응용 문제

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/16.svg"/> [ 플레티넘 ]

### - 고속 푸리에 변환

- #### 알고리즘 설명

  - [ 고속 푸리에 변환 ](https://blog.naver.com/PostView.naver?blogId=kks227&logNo=221633584963&categoryNo=299&parentCategoryNo=299&viewDate=&currentPage=1&postListTopCurrentPage=&from=postList&userTopListOpen=true&userTopListCount=5&userTopListManageOpen=false&userTopListCurrentPage=1)

- #### 기본 문제

  - [[플레1] 이동](https://www.acmicpc.net/problem/1067)

- #### 응용 문제

### - 뤼카의 정리

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - 

- #### 응용 문제

### - 중국인의 나머지 정리

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - 

- #### 응용 문제

<br>

------------------------------------------------------------------

<br>

# 📌 < 기하학 >

[ * 목차로 가기 ](#--목차-)

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/1.svg"/> [ 브론즈 ]

### - 기하

 - #### 기본 문제
   
   - [[브론즈5] 사분면 고르기](https://www.acmicpc.net/problem/14681)
   - [[브론즈3] 직사각형에서 탈출](https://www.acmicpc.net/problem/1085)
   - [[브론즈3] 직각삼각형](https://www.acmicpc.net/problem/4153)
   - [[브론즈3] 삼각형과 세 변](https://www.acmicpc.net/problem/5073)

 - #### 응용 문제
   
   - [[실버3] 터렛](https://www.acmicpc.net/problem/1002)
   - [[실버3] 어린 왕자](https://www.acmicpc.net/problem/1004)
   - [[실버2] 참외밭](https://www.acmicpc.net/problem/2477)
   - [[실버2] 겉넓이 구하기](https://www.acmicpc.net/problem/16931)
   - [[골드5] 3차원 막대기 연결하기](https://www.acmicpc.net/problem/19950)
   - [[골드3] 집으로](https://www.acmicpc.net/problem/1069)
   - [[골드2] 두 원](https://www.acmicpc.net/problem/7869)
   - [[골드1] 원뿔 좌표계상의 거리](https://www.acmicpc.net/problem/1798)
   - [[플레4] 석양이 진다..](https://www.acmicpc.net/problem/13352)

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/11.svg"/> [ 골드 ]

### - CCW/선분 교차 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - [CCW](https://snowfleur.tistory.com/98)
  - [신발끈 공식](https://ko.wikipedia.org/wiki/%EC%8B%A0%EB%B0%9C%EB%81%88_%EA%B3%B5%EC%8B%9D)
  - [넓이에 따른 CCW](https://www.acmicpc.net/blog/view/27)
  - [선분 교차](https://gaussian37.github.io/math-algorithm-line_intersection/)

- #### 참고 자료

  - [신발끈 공식 증명](https://omath.tistory.com/105)
  - [백터의 외적](https://blog.naver.com/mindo1103/90103361104)

- #### 기본 문제

  - [[골드5] CCW](https://www.acmicpc.net/problem/11758) (기본 CCW)
  - [[골드3] 선분의 교차1](https://www.acmicpc.net/problem/17386) (CCW를 이용한 선분교차 판정)

- #### 응용 문제
  
  - [[골드5] 다각형의 면적](https://www.acmicpc.net/problem/2166) (!!추천!!)
  - [[골드4] 사과나무](https://www.acmicpc.net/problem/2987)
  - [[골드4] 방사형 그래프](https://www.acmicpc.net/problem/25308)
  - [[골드2] 선분의 교차2](https://www.acmicpc.net/problem/17387) (!!추천!!)
  - [[골드1] 교차](https://www.acmicpc.net/problem/6439)
  - [[골드1] 대피소 찾기](https://www.acmicpc.net/problem/16491)
  - [[플레5] 선분 그룹](https://www.acmicpc.net/problem/2162) (!!추천!!)
  - [[플레4] 석양이 진다..](https://www.acmicpc.net/problem/13352)
  - [[플레3] 선분의 교차3](https://www.acmicpc.net/problem/20149)

### - 삼분 탐색

- #### 알고리즘 설명

  - [삼분 탐색](https://velog.io/@blankspxcx/%EC%82%BC%EB%B6%84-%ED%83%90%EC%83%89-Tenary-Search)
  - [삼분 탐색의 기하학적 의미](https://blog.naver.com/PostView.nhn?blogId=kks227&logNo=221432986308&proxyReferer=https:%2F%2Fwww.google.com%2F)

- #### 기본 문제

  - [[골드4] 민호와 강호](https://www.acmicpc.net/problem/11662) 

- #### 응용 문제

  - [[골드3] 블록 쌓기](https://www.acmicpc.net/problem/9998)
  - [[골드2] 국민 랜드](https://www.acmicpc.net/problem/13421)
  - [[플레5] 전봇대](https://www.acmicpc.net/problem/8986)
  - [[다이아5] 먼 별](https://www.acmicpc.net/problem/13310)

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/16.svg"/> [ 플레티넘 ]

### - 컨벡스 헐

- #### 알고리즘 설명

  - [컨벡스 헐](https://anz1217.tistory.com/106)

- #### 기본 문제

  - [[플레5] 볼록 껍질](https://www.acmicpc.net/problem/1708)

- #### 응용 문제

  - [[플레5] 맹독 방벽](https://www.acmicpc.net/problem/7420)
  - [[플레4] 단순 다각형](https://www.acmicpc.net/problem/3679)
  - [[플레2] 고속도로](https://www.acmicpc.net/problem/10254)

### - 다각형 내부 점 판정 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - [다각형 내부 점 판정](https://anz1217.tistory.com/107)

- #### 기본 문제

  - [[플레5] 지민이의 테러](https://www.acmicpc.net/problem/1688)

- #### 응용 문제
  
  - [[플레4] 감옥 건설](https://www.acmicpc.net/problem/2254)
  - [[플레3] 미스테리 싸인](https://www.acmicpc.net/problem/20670)
  - [[플레3] 걷기](https://www.acmicpc.net/problem/3700)
  - [[플레2] 점 분리](https://www.acmicpc.net/problem/3878)
  - [[플레1] 넓이](https://www.acmicpc.net/problem/1077)

<br>

-------------------------------------

<br>

# 📌 < 문자열 알고리즘 >

[ * 목차로 가기 ](#--목차-)

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/6.svg"/> [ 실버 ]

### - 정규 표현식

- #### 알고리즘 설명

  - [정규 표현식](https://soooprmx.com/%EC%A0%95%EA%B7%9C%ED%91%9C%ED%98%84%EC%8B%9D%EC%9D%98-%EA%B0%9C%EB%85%90%EA%B3%BC-%EA%B8%B0%EC%B4%88-%EB%AC%B8%EB%B2%95/)

- #### 참고 자료

  - [정규 표현식 모음 요약](https://hamait.tistory.com/342)

- #### 기본 문제

  
- #### 응용 문제

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/11.svg"/> [ 골드 ]

### - 트라이 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - [트라이](https://velog.io/@kimdukbae/%EC%9E%90%EB%A3%8C%EA%B5%AC%EC%A1%B0-%ED%8A%B8%EB%9D%BC%EC%9D%B4-Trie)

- #### 기본 문제

  - [[골드3] 개미굴](https://www.acmicpc.net/problem/14725)

- #### 응용 문제

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/16.svg"/> [ 플레티넘 ]

### - KMP 알고리즘 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - [KMP 알고리즘](https://bowbowbow.tistory.com/6)
  - [위에꺼 잘 이해 안될때 비교해서 읽으면 좋은 글](https://chanhuiseok.github.io/posts/algo-14/)
  - [KMP Failure Function의 응용 (31분 부터)](https://www.youtube.com/watch?v=OhMFeV8VeAc&t=1869s)

- #### 참고 자료

  - [보이어 무어 알고리즘](https://bblackscene21.tistory.com/3)

- #### 기본 문제

  - [[플레5] 찾기](https://www.acmicpc.net/problem/1786) (기본 KMP)
  - [[플레5] 문자열 제곱](https://www.acmicpc.net/problem/4354) (KMP Failure Function 이용하기)
  - [KMP 기본 코드](https://github.com/mclub4/Baekjoon/blob/main/%EB%B0%B1%EC%A4%80/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%20%EC%A0%95%EB%A6%AC/KMP/KMP.java)

- #### 응용 문제

  - [[플레5] 속타는 저녁 메뉴](https://www.acmicpc.net/problem/11585) (!!추천!!)
  - [[플레4] 광고](https://www.acmicpc.net/problem/1305)
  - [[플레4] 시계 사진들](https://www.acmicpc.net/problem/10266) (!!추천!!)
  - [[플레3] 문자열 장식](https://www.acmicpc.net/problem/17233)

### - 접미사 배열/LCP 배열

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - 

- #### 응용 문제

### - Manacher 알고리즘

- #### 알고리즘 설명

  - [Manacher](https://anz1217.tistory.com/100)

- #### 기본 문제

  - [[플레5] 가장 긴 팰린드롬 부분 문자열](https://www.acmicpc.net/problem/13275)

- #### 응용 문제

### - Z 알고리즘

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - 

- #### 응용 문제

### - 야호-코라식 알고리즘

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - 

- #### 응용 문제

<br>

## 📌 < 기타 알고리즘 >

[ * 목차로 가기 ](#--목차-)

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/nr.svg"/>[ 번외 ]

### - 구현/시뮬레이션 (🌟🌟 진짜 중요 🌟🌟)

- #### 알고리즘 설명

  - [구현/시뮬레이션](https://velog.io/@jehjong/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-%EA%B5%AC%ED%98%84Implementation-%EC%8B%9C%EB%AE%AC%EB%A0%88%EC%9D%B4%EC%85%98%EA%B3%BC-%EC%99%84%EC%A0%84-%ED%83%90%EC%83%89)
  - 딱히 알고리즘은 아니지만, 코딩 테스트에서 굉장히 많이 나오는 유형이라 중요한 넣을데 없어서 여기 넣음. 참고로 위에 나와있는 문제와 중복이 많음.
  - 대부분이 골드5 이상이며, 대부분 기본문제가 골드 4 이하의 모든 알고리즘들 중 골라서 잘 응용해서 풀어야되는 문제임. 따라서 적어도 기본 문제가 골드4인 알고리즘들까지 완벽히 숙지하고 풀어볼 것!
  
- #### 문제들

  - [[골드5] 주문은 토기입니까](https://www.acmicpc.net/problem/27447)
  - [[골드5] 틱택토](https://www.acmicpc.net/problem/7682)
  - [[골드5] 인구이동](https://www.acmicpc.net/problem/16234)
  - [[골드5] 컨베이어 벨트 위의 로봇](https://www.acmicpc.net/problem/20055)
  - [[골드5] 치킨 배달](https://www.acmicpc.net/problem/15686) (!!추천!!)
  - [[골드5] 로봇 청소기](https://www.acmicpc.net/problem/14503)
  - [[골드5] 톱니바퀴](https://www.acmicpc.net/problem/14891)
  - [[골드5] 치노의 라떼아트(Easy)](https://www.acmicpc.net/problem/27311)
  - [[골드4] 뱀](https://www.acmicpc.net/problem/3190)
  - [[골드4] 테트리미노](https://www.acmicpc.net/problem/14500) (!!추천!!)
  - [[골드4] 마법사 상어와 파이어볼](https://www.acmicpc.net/problem/20056)
  - [[골드4] 감시](https://www.acmicpc.net/problem/15683)
  - [[골드4] 미세먼지 안녕](https://www.acmicpc.net/problem/17144)
  - [[골드4] 드래곤 커브](https://www.acmicpc.net/problem/15685)
  - [[골드4] 주사위 굴리기](https://www.acmicpc.net/problem/14499)
  - [[골드4] 연구소](https://www.acmicpc.net/problem/14502)
  - [[골드4] 사격 연습](https://www.acmicpc.net/problem/27958) (!!추천!!)
  - [[골드3] 아기 상어](https://www.acmicpc.net/problem/16236) (!!추천!!)
  - [[골드3] 경사로](https://www.acmicpc.net/problem/14890)
  - [[골드3] 나무 재태크](https://www.acmicpc.net/problem/16235)
  - [[골드3] 치즈](https://www.acmicpc.net/problem/2638) (!!추천!!)
  - [[골드3] 마법사 상어와 토네이도](https://www.acmicpc.net/problem/20057)
  - [[골드3] 체인소맨](https://www.acmicpc.net/problem/27448)
  - [[골드2] 2048(Easy)](https://www.acmicpc.net/problem/12100)
  - [[골드2] 청소년 상어](https://www.acmicpc.net/problem/19236)
  - [[골드2] 어른 상어](https://www.acmicpc.net/problem/19237)
  - [[골드1] 구슬 탈출2](https://www.acmicpc.net/problem/13460)
  - [[골드1] 낚시왕](https://www.acmicpc.net/problem/17143)
  - [[플레2] RPG EXTREME](https://www.acmicpc.net/problem/17081)

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/6.svg"/> [ 실버 ]

### - 게임 이론

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - [[실버5] 돌 게임](https://www.acmicpc.net/problem/9655)

- #### 응용 문제

### - 투포인터/슬라이딩 윈도우 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - [투포인터](https://butter-shower.tistory.com/226)
  - [슬라이딩 윈도우](https://velog.io/@zwon/%EC%8A%AC%EB%9D%BC%EC%9D%B4%EB%94%A9-%EC%9C%88%EB%8F%84%EC%9A%B0Sliding-Window)

- #### 기본 문제

  - [[실버3] 두 수의 합](https://www.acmicpc.net/problem/3273)
  - [[실버3] 꿀 아르바이트](https://www.acmicpc.net/problem/12847)

- #### 응용 문제
  
  - [[실버3] 수열](https://www.acmicpc.net/problem/2559)
  - [[실버2] DNA 비밀번호](https://www.acmicpc.net/problem/12891)
  - [[실버1] 귀여운 라이언](https://www.acmicpc.net/problem/15565)
  - [[골드5] 두 용액](https://www.acmicpc.net/problem/2470)
  - [[골드4] 도둑](https://www.acmicpc.net/problem/13422)
  - [[골드4] 부분합](https://www.acmicpc.net/problem/1806)
  - [[골드4] 회전초밥](https://www.acmicpc.net/problem/15961)
  - [[골드4] 내려가기](https://www.acmicpc.net/problem/2096)
  - [[골드3] 연속한느 소수의 합](https://www.acmicpc.net/problem/7512)
  - [[골드1] 점 나누기](https://www.acmicpc.net/problem/1723)

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/11.svg"/> [ 골드 ]

### - 스위핑 (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - [스위핑](https://byeo.tistory.com/entry/%EC%8A%A4%EC%9C%84%ED%95%91-Sweeping)

- #### 기본 문제

  - [[골드5] 선 긋기](https://www.acmicpc.net/problem/2170)

- #### 응용 문제
  
  - [[골드5] 최소 회의실 개수](https://www.acmicpc.net/problem/19598)
  - [[골드5] 아우으 우아으이야!!](https://www.acmicpc.net/problem/15922)
  - [[골드4] 겹치는 선분](https://www.acmicpc.net/problem/1689)
  - [[골드3] 수상 택시](https://www.acmicpc.net/problem/2836)
  - [[골드3] 개구리 점프](https://www.acmicpc.net/problem/17619)
  - [[골드2] 최대 클리크 구하기](https://www.acmicpc.net/problem/13160)
  - [[골드2] 철로](https://www.acmicpc.net/problem/13334)
  - [[플레4] 북서풍](https://www.acmicpc.net/problem/5419)
  
### - 중간에서 만나기 (MITM) (👍 알면 좋음 👍)

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - 

- #### 응용 문제

<br>

## <img height="28px" width="28px" src="https://static.solved.ac/tier_small/16.svg"/> [ 플레티넘 ]

### - Mo's 알고리즘

- #### 알고리즘 설명

  - [Mo's 알고리즘](https://anz1217.tistory.com/141)

- #### 기본 문제

  - [[플레4] 수열과 쿼리 22](https://www.acmicpc.net/problem/16978)

- #### 응용 문제

### - 스프라그-그런디 정리

- #### 알고리즘 설명

  - 

- #### 기본 문제

  - [[플레4] 님 게임 2](https://www.acmicpc.net/problem/11868)

- #### 응용 문제

<br>

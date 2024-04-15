Weekly-I-Learned 4
================  
Git Flow Vs GitHub Flow
----------------------  
  
__Git Flow__  
2010년 Vincent Drissen(빈센트 드리센)이 고안한 브랜치를 관리하기 위한 전력이다.  
Git flow 에서는 총 다섯가지의 Branch를 사용한다.  
Branch|특징|브랜치구분
---|:---:|---
'main'|영원히 존재하는 기본으로 생성되는 브랜치|'MAIN'
'develop'|영원히 존재하는 feature 브랜치의 기반이되는 브랜치|'MAIN'
'feature'|develop 브랜치에서 분기,작업 후 병합|'SUPPORTING'
'release'|배포준비를 위한 브랜치, 자잘한 버그 수정, QA 작업, develop 분기 후 main에 병합|'SUPPORTING'
'hotfix'|즉각적인 수정이 필요할 때 사용, main에서 분기후 main과 develop에 병합|'SUPPORTING'
![GitFlow](https://github.com/chae54/2024-1-Beginner-Study/assets/128768148/bed0be72-29d8-4fb5-ab6b-045ed49a2c72)  
  
__GitHub Flow__  
배포가 수시로 이루어지는 현시대에 맞춰 위의 Vincent Drissen이 고안한 브랜치 관리 전략  
GitFlow와 다르게 두 종류의 Branch를 사용한다.  
Branch|특징|브랜치구분
---|:---:|---  
'main'|항상 배포 가능한 상태로 유지, 충분한 test 후 병합|'MAIN'
'feature'|main에서 분기하여 작업 후 병합, 이외 브랜치들을 구분하지 않기에 목적을 이름에 잘 담아야 함, 꼼꼼한 코드리뷰 필요|'SUPPORTING'
![GitHubFlow](https://github.com/chae54/2024-1-Beginner-Study/assets/128768148/bf7f8a07-abff-46c0-b0be-2192f4d65ca5)  
  
__번외:개발자의 태도__  
<span style="background-color:#FFE6E6"> 'Convention'을 사용하자! 시간이 지나도 쉽게 의도를 파악할 수 있다.</span>
<span style="background-color:#fff5b1"> '구글링'을 꼼꼼히 하자! 직접 검색하여 찾은 정보들을 쉽게 휘발되지 않는다. </span>  
<span style="background-color:#DCFFE4"> 코드에 대한 '주인의식'을 가지자! 코드는 곧 내 얼굴이다. 남보기 부끄럽지 않게 짜보자. </span>  
<span style="background-color:#E6E6FA"> '질문'을 잘하자! 같은 문제에 대해 질문을 하더라도 좋은 질문을 하여 상호 모두 얻는 것이 있도록 하자. </span>
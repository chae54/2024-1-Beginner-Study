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
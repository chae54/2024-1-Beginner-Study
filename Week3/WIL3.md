Weekly-I-Learned 3
================

사전지식
-------
__Git log__  
commit 기록을 확인할 수 있다.  
--online 을 붙이면 한줄에 요약 가능 
  
__Commit Id__  
commit들을 구별하기 위해 사용하는 40자 길이의 16진수  
시간과 관련이 있고 SHA-1 알고리즘으로 변환된 값   
  
__HEAD__  
현재 작업 중인 위치를 가리키며 현재 Branch의 가장 최근 commit  
  
Commit 되돌리기
--------------  
__Commit --amend__  
가장 최근 커밋을 수정할 때 사용되고 commit id가 바뀌면서 새로운 커밋으로 대체된다.  
Vim이라는 편집기로 커밋명을 수정해야 되지만 -m 을 사용하여 편집기 없이 수정할 수 있고  
--no-edit 을 사용하여 수정 없이 커밋을 수정할 수 있다.  
  
__Git reset__  
$ git reset ‘--option’ “<commit id>" 로 사용가능하며 option에는 soft, mixed, hard를 쓸 수 있다.  
mixed가 default 값이며 reset을 하면 해당 커밋으로 돌아가는데 soft는 Staging area, mixed는 working directory, hard는 모두 제거한다.  
  
__Git revert__  
$ git rever "<commit id>" 로 사용하며 해당 커밋을 되돌리기 위한 커밋을 생성한다.  
마찬가지로 --no-edit 을 사용하여 바로 revert가 가능하고 --no-commit을 사용하면 바로 Staging area로 올라간다.

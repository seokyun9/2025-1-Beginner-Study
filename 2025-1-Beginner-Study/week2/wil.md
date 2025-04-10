# Weekly I Learn
==============
## # 1. Fork, star, Issue
--------------------  
   Fork : 다른 사용자의 repository를 복사해 독립적으로 수정/관리    
   Star : 관심있는 repository 나 프로젝트에 star를 달아 “북마크” 처럼 관리  
   Issue : Repository에서 작업 계획/ 토론/추적을 위해 활용    
***
## 2. Branch
-------

 - 기존 브랜치에서 분기되어 생성되는 별도의 작업 공간
 - fork 와 달리 같은 repository에 생성됨
 - convention : “type/이슈번호-간략한설명”
          
	#. pull request      
		- 분기된 branch 를 다시 병합하기 위한 절차    
		- 새로운 변경을 제안하거나 병합 시 발생하는 충돌을 해결         
		- merge에 앞서 코드 리뷰    
            
	#. merge    

    1 . Merge commit     
            두 브랜치를 공통 부모로 하는 새로운 commit ‘E’를 만듦    
            A, B, C의 커밋이 그대로 main 브랜치로 병합

	2 . Squash and merge   
            A, B, C의 커밋을 'squash' => 하나의 커밋을 통해 main 브랜치로 병합        
                    
	  3 . Rebase and Merge   
            A, B, C 커밋의 base를 재설정     
            모두 새로운 커밋으로 변경

***
      
## # 실습  
https://github.com/seokyun9/2025-1-Beginner-Study/pull/2

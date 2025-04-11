# Weekly I Learn          
      
  개발입문 스터디 4주차 wil         
       
           
  브랜치 전략
----------

### #1 Git Flow
    
#### Main Branches

    - main (master)
        프로젝트 생성 시 기본으로 생성되는 브랜치
        영원히 존재하는 첫 번째 브랜치
        병합될 때마다 제품의 새로운 버전이 탄생
    
    - develop
        
        영원히 존재하는 두 번째 브랜치
        feature의 기반
        
#### Supporting branches

    - feature
        develop에서 분기하여 작업 후 다시 develop으로 병합
       
    
    - release - 배포용
        배포 준비, 자잘한 버그 수정
        
        — develop에서 분기하여 main으로 병합
        
    - hotfix - 빠른 수정용
        
        — 배포 환경에서 즉각적 수정 필요시
        
        — main에서 분기 main,develop 모두에 병합
        
  ***

### #2 GitHub Flow

    only Main 과 Feature 브랜치만 사용

    배포를 자주 해야하는 환경에 good

    - main
    
        항상 배포 가능하게
    
        병합 전 충분한 test 필요
    
    - feature
    
        Git Flow와 달리 이외 브랜치들을 구분하지 않음
        main에서 분기하여 작업 후 다시 main으로 병합
        브랜치의 목적을 이름에 잘 담아야 함
        Git Flow에 비해 코드 리뷰가 더 중요함
    
        hotfix..등등 필요한 모든 걸 feature로 → main에 병합
# 데이터 크롤링, 댓글 분석 프로젝트
> '코카콜라와 제로콜라'의 댓글 반응 분석(텍스트 분석)

## 분석 주제 : 
   - 제로콜라 이후 제로 칼로리 음료에 대한 여론이 어떻게 바뀌었는지, 제로 음료수 관련 동영상 댓글 수집과 분석을 진행하고자 한다.


## 1. 프로젝트 진행 동기

- 새롭게 떠오른 언론 매체 - 유튜브
 - “요즘 검색은 다 여기서 해요”…포털 안 찾는다는 MZ세대
   
![이미지2](https://github.com/maker-lee/project/assets/63797441/95686d67-8993-46aa-b68d-c1ab10a100c7)
  - 특히 10대, 20대 등 젊은층을 중심으로 전통 검색 플랫폼인 네이버, 구글, 다음이 아닌 동영상 플랫폼 유튜브를 비롯해 인스타그램, 틱톡 등을 정보 탐색(검색)의 용도로 활용하는 경우가 갈수록 두드러지고 있다. 

  - <연합뉴스> 구글 진격에 카톡·네이버 '흔들'…유튜브, 첫 사용자 1위 눈앞(종합)
    
![이미지1](https://github.com/maker-lee/project/assets/63797441/0598e56e-e716-4953-8ee4-655714f15e3f)
  - 5일 모바일 빅데이터 플랫폼 기업 아이지에이웍스의 데이터 분석 설루션인 모바일인덱스 통계에 따르면 지난달 카카오의 카톡 MAU(월간 실사용자 수)는 4천145만8천675명으로 1위를 기록했지만, 2위인 구글의 유튜브(4천95만1천188명)와 격차는 50만7천487명에 불과했다. MAU는 한 달에 최소 1차례 서비스를 쓴 사람 수다.



## 2. 분석 결과

-  단어 빈도 분석 
     
-  워드 클라우드 분석 결과
   
-  단어 별 네트워크 분석 결과(지지도 )
   
- 나이브 베이즈 분류 결과

  


## 3. 데이터 수집 프로세스 및 구조도
   - 수집 대상 및 기간 
        - item: 개별 동영상들의 제목, 링크, 댓글 남긴 사람 id, 댓글, 좋아요 수
        - 기간: 2020년에 업로드된 '타다 금지법' 관련 모든 동영상 댓글 크롤링 후, 분석에는 3/6(법안 통과일) ~ 3/31 기간에 올라온 영상 댓글만 사용
        
   - 크롤링 방법
        - AWS EC2 환경에서 YouTube '타다 금지법' 영상 댓글 크롤링
        - scrapy 프레임워크 + module 혼합하여 사용

   - 데이터의 저장
        - DB: mongodb 데이터 베이스에 크롤링한 데이터 저장하는 파이프라인 구축
        

## 4. 폴더 설명

 
## 5. 아쉬웠던 점


## 6. 결과


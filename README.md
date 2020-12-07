# 안드로이드 앱만들기 프로젝트

### 20201129
* 우연히 유튜브에서 비전공자가 한달만에 로또 앱 만들어서 수익 냈따는 영상을 봄
* 그사람이 보고 공부했다는 영상과 책을 따라 구독하고 구매함
* 디모의 Kotlin 강좌
    * https://www.youtube.com/playlist?list=PLQdnHjXZyYadiw5aV3p6DwUdXV2bZuhlN
* 애프터스킬 안드로이드 with Kotlin 앱 프로그래밍 가이드
    * https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=177477102

### 20201130
* 디모의 Kotlin 강좌 시청 시작
    * 영상 1 ~ 16
    
### 20201201
* 디모의 Kotlin 강좌 시청 끝
    * 영상 17 ~ 31
* 주문한 책 도착 (너무 비싸서 중고로 구매)
    
### 20201202
* 책으로 공부 시작
    * P.140 까지 보면서 따라함
        * 여기까지는 자바 기초 문법과 프로그래밍 기초 상식이었음
        * 거의 2년 된 책이라 책과 현재 안드로이드 화면이 달라서 당황스러웠으나 따라할만 했음

### 20201203
* 책
    * 코틀린부분 들어갔는데 책에서 시킨대로 해도 처음부터 안됨
    * 자바 부분은 달라도 책이랑 달라도 감으로 따라한게 실행은 됐는데 코틀린은 실행조차 안됨
    * 멘붕에 빠져 잠시 앓아 누움
* 유튜브로 안드로이드 스튜디오 코틀린 강의를 찾아보니 다행히 올 여름에 올라온 강의가 있어서 그것부터 보기로 계획 변경
    * 한국인을 위한 안드로이드 스튜디오 코틀린 백과사전
        * https://www.youtube.com/watch?v=WlJszSmK_es&t=205s
        * 1:10까지 시청
            * 무난하게 따라 하다가 코틀린 파일로 진행할 때 MainActivity 파일에 버튼 id값을 넣으면 글씨가 빨갛게 되고 실행버튼 누르면 Unresolved reference : btn 이라고 계속 에러나서 멘붕-_-
                * alt + 엔터 치면 자동으로 변환된다는데 아무리 해도 안됨. 맥이라서 단축키가 다른가 command, option, control 다 번갈아 가며 눌러봤는데 안됨.
                * 구글링했는데 답 못찾고 마지막으로 유튜브에 검색에 넣어보니 누가 해결방법 영상 올려준거 보고 따라 했더니 됨-_-
                * https://www.youtube.com/watch?v=TWsVCmZw24o <- 이거 보고 bundle.gradle(Module어쩌고 이거에 넣어야함)에 플러그인 코드 복붙하니 안드로이드 스튜디오에서 코틀린 버전이 안맞다나? (아닐수도있음) 하면서 버전 다운 그레이드할래?해서 다운그래이드 했떠니 됨. 히율..
                    * 과연 나는 앱을 만들 수 있을것인가?
                    
### 20201204
* 한국인을 위한 안드로이드 스튜디오 코틀린 백과사전
    * 1:58 까지 시청
      
### 20201205
* 한국인을 위한 안드로이드 스튜디오 클린 백과사전
    * 2:10 까지 보다가 졸리고 피곤해서 공부 중단
      
### 20201206
* 한국인을 위한 안드로이드 스튜디오 코틀린 백과사전
    * 3:50붙이던가 하여간 끝까지 다 봄
          * 중간중간 삽질을 무지하게 했지만 그래도 필요한 부분은 다 따라 해봤고 끝까지 봤다
               * import 못하고 can not resolve 어쩌고가 뜰때 해결 방법 -> https://kim-hoya.tistory.com/4
               
### 20201207
* 책, 동영상 없이 UI 만지작 거려보고 파일들의 상관관계를 되 짚어 봄

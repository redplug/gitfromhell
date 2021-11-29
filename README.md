1. ### 깃 설치

   - URL : https://git-scm.com/downloads
   - 실행확인
   - ![image-20211122202531473](https://raw.githubusercontent.com/redplug/shareimages/master/img/image-20211122202531473.png)
   - 실행 후 git
   - ![image-20211122202538117](https://raw.githubusercontent.com/redplug/shareimages/master/img/image-20211122202538117.png)

2. 깃 명령어

   - git 사용을 위해서는 username과 email주소가 필요, 한번만 필요함.

     ```bash
     git config --global user.name redplug
     git config --global user.email redplug@gmail.com
     ```

     

   - git init : 깃을 사용하기 위해 초기화 하는 명령어

     ```bash
     git init
     ```

   - git add : 깃으로 관리하기 위해서 파일을 추가하거나 변경된 사항을 적용하기 위해 필요한 명령어, commit 하기 전에 필요함.

     ```bash
     git add f1.txt
     ```

   - git commit : 깃을 버젼관리하기 위해 실행하는 명령어, 커밋을 위해서는 메시지를 넣는 창이 뜸.(vi일 경우 i를 눌러서 INSERT모드에서 수정 후 esc > :wq로 저장)

     ```bash
     git commit
     ```

   - git stage area : git을 커밋하기 바로전에 최종적으로 확인할 수 있는 공간, add한 파일들이 여기에 있음.

   - git log : commit 한 히스토리를 확인할 떄 사용

     ```bash
     ## 로그 확인
     git log
     ## 소스상의 차이점 확인
     git log -p
     ```

     

     - ![image-20211129094811274](https://raw.githubusercontent.com/redplug/shareimages/master/img/image-20211129094811274.png)
     - ![image-20211129094010015](https://raw.githubusercontent.com/redplug/shareimages/master/img/image-20211129094010015.png)

   - git diff : commit 간 차이점을 확인해줌

     ```bash
     git diff 커밋주소1..커밋주소2
     ```

     ![image-20211129094153919](https://raw.githubusercontent.com/redplug/shareimages/master/img/image-20211129094153919.png)

   - git status : 깃 상태를 확인할 수 있음

     ```bash
     git status
     # 하기 녹색은 add한 파일 붉은색은 add하지 않은 파일
     ```

     ![image-20211129094338071](https://raw.githubusercontent.com/redplug/shareimages/master/img/image-20211129094338071.png)

   - 

   - 


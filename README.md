# Trpg 로그 백업용 블로그 만들기
**feat. Beautiful Jekyll**

본 내용은 Beautiful Jekyll 테마를 이용하여 만들고 있습니다.

Beautiful Jekyll은 MIT 라이선스를 가진 프로젝트로, 변경과 재배포가 허용되어 있습니다.

Beautiful Jekyll 테마에 대한 자세한 정보를 알고 싶은 분은 [원본 프로젝트 페이지](https://github.com/daattali/beautiful-jekyll)로 이동해 주세요.  



# Why Beautiful Jekyll?

뷰티풀 지킬 테마는 모바일 환경도 호환되면서 동시에 커스터마이징이 자유롭습니다.

사용 방법도 다른 테마에 비해 쉽고 간편하기 때문에 본 테마로 선정하였습니다.  


## 추천
티알피지 로그의 백업. html이든, plain text이든, pdf든 편하게 올리고 싶다! 하는 분들을 위해 추천합니다.

티스토리 구 버전 에디터가 종료되었기 때문에 html을 수정해야 하는 번거로운 작업에 지친 분들에게도 추천합니다.  


## 5분만에 따라할 수 있는 블로그 만들기!
![install-steps](assets/img/install-steps.gif)
### 1. 포크하기
우측 상단의 Fork 버튼을 눌러 이 레포지토리를 복사합니다.  


### 2. 이름 바꾸기
Settings 버튼을 누른 후, 레포지토리의 이름을 '유저명'.github.io로 변경합니다.  


### 3. 완성
https://'유저명'.github.io  링크로 들어가보면 사이트 완성!  



## 5분만에 따라할 수 있는 설정 변경하기

### 1. _config.yml 파일에 들어가기

파일에 들어가서 연필모양 아이콘을 누른 후 'My title' 이라고 써있는 부분을 찾습니다.

### 2. 블로그 제목 변경하기
제목을 원하는 문구로 저장합니다.

### 3. 블로그 아바타 변경하기
asset->img 폴더 안에 원하는 사진을 업로드한 후, 해당 파일 페이지에서 우측 상단의 '...' 모양 아이콘 누르고 'Copy path' 클릭하면 경로가 복사됩니다.  

그 경로를 _config.yml 파일 안에 있는 'avatar' 문구 옆에 붙여넣으면 끝!

### 4. 기타 설정 변경하기
파일 안의 '#' 에 있는 설명을 읽고 조절하세요.

## 5분만에 따라하는 포스팅하기

### 1. _posts 폴더에 들어가기

### 2. 파일 복사, 수정, 저장하기
공개 포스팅, 숨김 포스팅, 암호화 html 포스팅의 샘플 파일이 각각 들어있습니다.

encrypted_hidden -> 암호화& 숨김 포스트  
encrypted_open -> 암호화& 공개 포스트  
hidden_testlog -> 숨김 포스트  
open_testlog -> 공개 포스트  

파일 안의 내용을 복사 -> Add file-> Create new file -> 에디터에 그대로 복붙 후 내용을 수정합니다.

첨부할 html 파일은 반드시 '_posts' 폴더에 넣고, 포스트의 {% include_relative 파일이름.html %} 부분에 html 파일이름을 적어넣어야 합니다.  
 
**포스트 파일(.md)의 이름을 반드시 '년도4자리-월2자리-일2자리-파일이름.md' 로 저장해야 사이트 내에 보여집니다!!**  

#### <암호화 html>
원하는 html 을 다음 사이트에 들어가서 암호화합니다.  
- [pagecrypt](https://www.maxlaumeister.com/pagecrypt/)  

변환한 html 파일을 ' _posts ' 폴더에 넣습니다.

그 후, encrypted_open.md나 encrypted_hidden.md 중 하나의 파일을 골라 열고, 그 내용을 복사+새로운 파일을 만들어 붙여넣기 합니다.

파일 내용 중 {% include_relative 파일이름.html %} 라는 부분을 찾습니다.

'파일 이름' 부분을 우리가 다운로드한 암호화 html의 파일명으로 고쳐 씁니다.





**주의 : 비밀번호가 암호화되어서 어디에도 저장되지 않기 때문에, 잊어버리면 신선이 와도 비밀번호를 찾기 어렵습니다. 원본 파일을 버리지 않는 것을 추천합니다!**

**포스팅한 후 약 10분정도는 쿠키가 남아있어서 업로드한 내용이 반영되지 않을 수 있습니다.**

그럴 때에는 시크릿 모드로 창을 열어서 접속해봅시다.


## 참조
- [HTML 의 기초 배우기 (TCP school)](http://tcpschool.com/html/intro)
- [마크다운 사용법 밎 예제](https://theorydb.github.io/envops/2019/05/22/envops-blog-how-to-use-md/)







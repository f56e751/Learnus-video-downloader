# Learnus-video-downloader
Inspired by https://github.com/kyle8581/LearnUsDownloader

동영상을 다운로드하는 핵 코드는 위 git의 코드를 그대로 사용하였으며, 여러 동영상을 한번에 편리하게 다운로드 하기 위해 UI만 wrapping함.

입력 값에 대한 설명
 - cookie string: 
 
    lecture url을 요청하기 위해 필요한 session 정보가 담긴 쿠키 문자열. 
    
    [디버거]의 [네트워크]에서 https://ys.learnus.org/course/view.php?id=###### 요청을 선택한 뒤, 요청 헤더의 Cookie 항목을 선택하고 마우스 오른쪽 버튼 클릭하여 [값 복사] 눌러서 복사된 값을 붙여넣기.
 - lecture url: 
 
   런어스에서 동영상 다운로드 원하는 강좌를 클릭했을 때 나오는 URL. (https://ys.learnus.org/course/view.php?id=######)

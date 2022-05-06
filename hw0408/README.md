# LIKELION_FRONT_STUDY #1
### 유튜브 레이아웃 클론 코딩
***


>결과 화면 full screenshot
<br>

![test_screenshot](https://user-images.githubusercontent.com/100709499/166420730-b79a4843-27c5-4488-82e4-41cd8b5ea33c.png)
<br>
<br>
>header + 4개의 section으로 분류
1. header
2. video player
3. information
4. comments
5. recommended

>header
* logo, circle, search, user를 flex로 정의
* logo와 circle 사이 간격 때문에 애먹었는데, 그냥 logo의 margin-right를 크게 줘서 해결했다.
* header의 돋보기 아이콘은 Font-Awesome 사이트를 이용: head에 링크를 걸어주고, i class를 긁어오면 된다.


>video player
* html의 내장된 video 태그 사용, 동영상은 free download가 가능한 픽사베이에서 가져왔다.
* 이외의 삽입된 이미지 역시 픽사베이에서 가져왔다.

>information
* button + text를 같이 움직이기 위해서, figure/figcaption 태그를 사용했다.
* account info 부분은 grid로 묶고, image + user + SUBSCRIBE로 정렬했다.

>comments
* 3x4 gird로, image + text + likes로 정렬했다.
* text는 flex로 다시 정렬했다.

>recommended
* 4개의 추천 동영상을 grid로 정렬했다._(flex로 해도 상관 없었을 듯 하다.)_
* image + text를 다시 flex로 정렬했다.
* 그리고 text를 다시 title + name + view로 나누어 gird로 정렬했다.

<br>
<br>

>후기
* 다른 것보다.. 웹 페이지 제작을 할 때는 크게 레이아웃을 나누고 시작해야 시간 낭비를 안한다는 걸 배웠다.
* 팀원들과 협업하다보니 깃허브의 필요성을 절실히 느꼈다. 얼른 익숙해져서, 다음 스터디에서는 깃허브를 적극 이용하고 싶다.
* 주석 달기에 익숙해져야할 것 같다.
* flex와 grid를 정말 많이 사용한다는 걸 깨달았다.
* 뭔갈 배우면 무조건 정리하는 습관을 만들자!
* 프론트 팀원들과의 첫 스터디였는데, 처음이라 우여곡절도 많았지만 팀원들 모두 너무 열심히 했다. 프론트팀 최고 ^_^

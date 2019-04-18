# OP 구글 블로그 (블로거) 테마

## 공지:
### 추천하는 테마
* [New Day](https://github.com/treezi1004/op-blogger-themes/tree/master/other_languages/ko/2_Columns/New_Day): 2단형의 최신 테마로, 모바일 SEO 문제점을 해결하고 CSS 변수를 색과 폰트로 간략화했습니다.
* [The Beginning](https://github.com/treezi1004/op-blogger-themes/tree/master/other_languages/ko/1_Column/The_beginning): 1단 프로토타입 테마로, 모바일 SEO 문제점이 없습니다.

### 추천하지 않는 테마
* Today: 레이아웃 페이지에서 사이드바 사용불가
* RT: 레이아웃 페이지에서 사이드바 사용불가

### 나머지 테마들
구글 검색 콘솔의 모바일 SEO문제를 갖고 있지만 큰 문제점이 되지 않습니다. 사실 사용해도 문제는 없지만 걱정이 된다면 추천하는 테마를 사용하시면 됩니다.

### 최근 블로거 테마 에디터의 불안정 문제점
테마를 수정할 경우에는 구글 크롬을 웹브라우저로 사용해주시길 바랍니다. 파이어폭스와 다른 브라우저에서 블로거 테마 에디터가 매우 불안정한 상태입니다.

### 모바일 SEO 문제점
몇몇 모바일 버젼의 테마가 검색 엔진 최적화가 안되어있는 것을 발견했습니다. 테마는 사용자에게 잘 작동하고 있습니다만, 새 구글 검색 콘솔이 모바일 버젼을 제대로 렌더링하고 있지 않는 것으로 확인되었습니다. 만약 현재의 검색 엔진 최적화가 중요하다고 생각된다면 몇몇 OP 블로거 테마는 사용하지않는 것을 추천합니다. 대신 위 추천하는 테마를 사용할 수 있습니다.

웹마스터 관계자의 말에 의하면 그렇게 큰 문제를 일으키지는 않는다고 합니다.

관련 비디오: [https://www.youtube.com/watch?v=vugCZMGY3L8&feature=youtu.be&t=49](https://www.youtube.com/watch?v=vugCZMGY3L8&feature=youtu.be&t=49)

## 설명:
OP 블로거 테마는 구글 블로그 테마 개발을 위해 개발되었습니다.
이 프로젝트의 주 목적은 구글 블로그 테마 개발을 쉽게 하기 위한 깔끔한 베이스 테마를 개발하는 것 입니다.
OP 구글 블로그 테마는 추가적인 테마 개발 없이 바로 블로그에 사용할 수 있습니다.
각 폴더에는 다른 구글 블로그 테마가 담겨 있습니다.

## 기능:
1. 반응형 웹 디자인
2. 유연한 마이너 테마 디자인 컨트롤
3. 구글 블로그 CSS 변수
4. 오픈 그래프 메타 태그 (Open graph meta tags) : 추가 설정을 해주어야 합니다.
5. 반응형 웹 디자인을 위한 iframe 미디어(유튜브) 리사이징
6. 더 나은 카테고리 기술
7. 예쁜 구글 검색

## 테마 설치하는 법:
### 유튜브: https://www.youtube.com/watch?v=7MffCYMZEkA
### 블로그: https://www.treezi.org/2019/02/how-to-install-op-blogger-theme.html

1. 블로그 설정에서:
  * 블로그 설명 설정
  * 구글 블로그 메타 태그 활성
  * HTTPS 리다이렉션 활성
  * 같은 디자인의 타임 스탬프 (추천)
  * 테마에서 모바일 버젼 비활성화 (반응형 웹디자인의 테마이기 때문에 모바일 버젼이 필요없음)

2. 구글 블로그 테마 HTML 변경:

  * head 태그 안의 오픈 그래프 메타 태그와 다른 메타 태그 설정하기
    * 주석 처리된 태그들 안에 src 링크를 채워넣고 주석해제.
    * locale의 경우에는, 예시) ko_KR, en_US, en_NZ과 같은 식으로 채워넣기
    * 다른 메타 태그들도 설정하기 쉽습니다.
  * 기본 포스트 썸네일 이미지와 인기 포스트 썸네일 설정하기
    * 포스트 안에 이미지가 없는 경우를 위한 썸네일을 설정하여야 합니다. 추천하는 이미지 사이즈는 250px x 250px 입니다. 주석 처리된 이미지 태그 부분에 src 속성 값을 이미지 주소로 채워주면 됩니다. 인기 포스트의 경우에는  72px x 72px의 이미지 사이즈를 추천합니다.
  * PageList1 위젯에서 url 설정하기
    * blogger.com을 기본으로 넣어놨습니다. 사실 설정하지 않아도 블로그 기능에는 아무 문제가 없습니만, 기본적으로 현 블로그의 주소로 되어야만 합니다.

## 문제 & 해결

문: 이미지가 본문에서 삐져나옵니다.

답: 텍스트 에디터에 의해 자동으로 생성된 스타일이 원인입니다. 글 편집에서 이미지의 HTML 중 'style="margin-left: 1em; margin-right: 1em;"'를 모두 제거하면 됩니다. 글을 쓸 때마다 해야하니 크롬 브라우저의 확장 프로그램 replace를 이용하거나 파이어폭스의 부가기능의 replace를 이용하는 것을 추천합니다.


## 라이센스:
MIT

## 후원
* [후원 페이지](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=R5EKF6TRDDXE8&currency_code=USD&source=url)

후원을 해주시면 저같은 오픈소스 소프트웨어 개발자에게 도움이 됩니다.

## 저작자:
* 이름: 트리지
* 이메일: treezi1004@gmail.com
* 블로그: https://www.treezi.org/
* 유튜브: https://www.youtube.com/channel/UCEbeHYdBuQu3ayp29-ArYKA

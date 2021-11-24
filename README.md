# HTML/CSS Layout 실습
> 폴더명 : Site20211124
> 실습날자 : 2021년 11월 24일 웹프로그램밍 실습 markdown 연습
---  
# 1. Responsive Web Design(RWD.html, RWD.css)
    > CSS display관련 block과 in-line의 차이점 복습  
    역시 연습 안하면 까먹음을 다시 한번 알았다.  
    까먹어도 안 배웠다고 우기자.  알고 나서 부끄러워하고 사과하자.  
    인라인 https://www.w3schools.com/css/tryit.asp?filename=trycss_display_inline_list  
    블락 https://www.w3schools.com/css/tryit.asp?filename=trycss_display_block
    > box-sizing: border-box 가 핵심임.박스를 만들어서 거기에 다 넣는다.  
    css에서 이 값을 안주면 padding 값에 따라서 박스이 크기가 변하게 된다.  
    https://www.w3schools.com/css/css3_box-sizing.asp  

    > Viewport 웹페이지의 보이는 부분이다. 데스크탑에서는 상대적으로 넓고(최소 1024px ~ 최대 4096정도?),   
    스마트폰이나 테블릿에서는 상대적으로 좁다(커 봐야 400px ~ 800px 정도).  
    예제는 <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    > Grid view 
    컬럼을 12개로 나누어서 일정한 폭으로 나눈다.
    Layout을 정하고 메뉴를 정하는 연습을 한다.  
    https://www.w3schools.com/css/css_rwd_grid.asp  

    > Media query
    미디어 쿼리를 이용하여 스마트폰과 테블릿 화면을 자동으로 조정한다.  
    https://www.w3schools.com/css/css_rwd_mediaqueries.asp  
    > Images
    Chania 페이지에 이미지를 넣는 연습. 폭은 100% 높이는 자동으로 연습.  
    백그라운드 이미지를 사용할 때 찌그러지는 것 방지하는  
    background-size: cover 사용연습.  
    https://www.w3schools.com/css/css_rwd_images.asp  
    > Frameworks

# 2. CSS Grid
    > RWD(반응형 웹디자인) Grid과 달리 열과 행을 이용해서 Layout 제작  
    특히 float과 position을 사용하지 않고 구현하는 것이 특징이다. 이걸 보면  w3c가 html5 발표 후 놀은게 아니라 꾸준하게 업데이트를 한다는 점이다. 다음에 공부할 Flexbox도 보면 최신 버젼의 브라우저에서만 동작한다. 
    어쨌든  그리드 *레이아웃은 반드시 부모 요소(element)를 가지면서* display 속성(property)은 grid 또는 inline-grid 를 가져야 한다(display: grid  또는   display: inlie-grid). 
    > grid-container라는 박스, grid-item라는 구성요소 두가지가 있음.
    하옇든 grid-template-areas:  blabla....
    css에서 
    grid-template-areas: 
    'header header header header header header'
    'menu main main main right right'
    'menu footer footer footer footer footer'
    'menu bottom bottom bottom bottom bottom'
    'final final final final final final';
    그리고 5단 레이아웃  
    naming을 이용하는게 편하다.
    https://www.w3schools.com/css/tryit.asp?filename=trycss_grid_layout_named


# 2. CSS Flexbox


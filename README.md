# web<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Urbangrace</title>
    <style>
        
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@100..900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap')
        
        body{
            display: inline;
            }

        
        *{
            margin: 0 auto;
            padding: 0;
        }
        header
        {
            /* border: solid 1px black; */
            width: 1280px;
            height: 210px;
        }
        .logo
        {
            text-align: center;
            /* border: 1px solid green; */
            margin-top: 20px;
        }  
        .menubar 
        {
            display: inline-block;
            margin-top: 25px;
            /* border: solid 1px blueviolet; */
            height: 50px;
            width: 1280px;
        }

        #menupng 
        {
            /* border: 1px solid red; */
            display: flex;
            float: left;
            margin-top: 12px;
            /* size: 100%; */
        }
        #menutext
        {
            /* border: 1px solid red; */
            display: inline-block;
            line-height: 200%; /*text 사이즈 조절*/
            font-size: 20px;
            font-family: "Roboto", sans-serif;
            font-weight: 500;
            font-style: normal;
            letter-spacing: -1px; /*자간 조절*/


        }
        #m-menu
        {
            /* border: 1px solid pink; */
            float: right;
            font-size: 15px;
        }
        #m-menu li
        {
            list-style: none;
            display: inline-block;
            margin-top: 32px;
            margin-right: 10px;
            font-family: "Noto Sans KR", sans-serif;
            font-optical-sizing: auto;
            font-weight: 500;
            font-style: normal;
            font-size: 15px;
            letter-spacing: -1px;
        }
        #happyday
        {
            text-align: center;
            /* border: solid 1px black; */
            width: 1280px;
            height: 690px;
        }
        a 
        {
            color: inherit; 
            text-decoration: none;
        }
        #rankingtext
        {
            position: relative; /*부모요소의 포지션*/
            /* border: solid 1px green; */
            width: 1280px;
            height: 100px;
            font-size: 30px;
        }
        .king
        {
            position: absolute;  /*자식요소의 포지션 */
            bottom: 0%; 
            font-family: "Roboto", sans-serif;
            font-weight: 500;
            font-style: normal;
            font-size: 25px;
        }

        .items
            {   margin-top: 50px;
                display: flex;
                /* flex-wrap: wrap; flex의 영향을 안받는 느낌? */
                justify-content: space-between;
                /* margin-right: auto;
                margin-left: auto; */
                width: 1280px;
                /* height: 880px; */
                /* border: solid 1px tomato; */
            }
        .item
            {
                position: relative;
                width: 290px;
                height: 395px;
                /* border: solid 1px blue; */
                /* float: left; */
                margin: 0;
            }
        .imgbox:hover
            {
                background-color: white;
                opacity: 0.6;
                cursor: pointer;
            }
        .ritem
            {
                /* border: solid 1px red; */
            }
            
            
        .imgbox
            {
                /* border: 1px solid red; */
                width: 100%;
                height: 100%;
                /* border: solid 1px aqua; */
            }

        img 
            {
                background-repeat: no-repeat; /*이미지 반복 설정 x*/
                background-position: center;
                /* border: solid 1px green; */
                background-size: cover;
            }
        .rname
            {
                width: 100%;
                font-family: "Roboto", sans-serif;
                font-weight: 700;
                font-style: normal;
                letter-spacing: -1px;
                font-size: 16px;
                text-align: center;
                /* border: 1px solid ; */
            }
        .rprice
            {
                width: 100%;
                font-family: "Roboto", sans-serif;
                font-weight: 400;
                font-style: normal;
                text-align: center;
                letter-spacing: -1px;
                font-size: 16px;
            }
        .rank
            {
                position: absolute;
                top: 5px;
                font-family: "Noto Sans KR", sans-serif;
                font-optical-sizing: auto;
                font-weight: 700;
                font-style: normal;
            }
        .events
            {
                width: 1280px;
                /* height: 500px; */
                /* border: solid 1px palegreen; */
                margin-top: 50px;
                position: relative;
                height: 1455px;
            }
        .event
            {
                text-align: center;
                margin: 0;
                display: block;
                /* border: 1px solid red; */
                position: absolute;
                margin-left: 130px;
            }
        .bf
            {
                margin-left: -5px;
            }
        .snap
            {
                /* margin-top: 3px; */
            }
        .event2
            {
                text-align: center;
                margin: 0;
                display: block;
                /* border: 1px solid red; */
                /* margin-top: -9px; */
                position: absolute;
                margin-left: 304.5px;
                margin-top: 442.6px;
                
            }
        .popup
            {
                margin-left: -5.5px;
                /* margin-top: -5px; */
            }
        .event3
        {
        display: block;
        /* border: 1px solid black; */
        height: 606px; 
        position: absolute; 
        margin-top: 853px;  
        }    
        .dl
            {
                float: right;
                /* margin-top: 300px; */
                margin-right: 8.5px;
                margin-top: 300px;
            }
        .mg
            {
                margin-left: 10px;
            }
        .newbox
            {
                margin-top: 50px;
                /* border: solid 1px purple; */
                width: 1280px;
                display: flex;
                justify-content: space-between;
            }
        .ootd
        {
            margin-top: 50px;
            width: 1280px;
            /* border: 1px solid sandybrown; */
            position: relative;
            height: 836px;
        }
        .ootdq
        {
            /* border: solid 1px green; */
            position: absolute;
        }
        .ootdw
        {
            /* border: solid 1px; */
            position: absolute;
            margin-left: 255px;
            margin-top: 270px;
        }
        .ootde
        {
            /* border: solid 1px red; */
            position: absolute;
            margin-left: 530px;
        }
        .ootdr
        {
            /* border:  solid 1px orange; */
            position: absolute;
            margin-left:805px;
            margin-top: 250px;
        }
        .ootdq:hover
        {
            /* background-color: white; */
            opacity: 0.5;
            cursor: pointer;
        }
        .ootdw:hover
        {
            /* background-color: white; */
            opacity: 0.5;
            cursor: pointer;
        }
        .ootde:hover
        {
            /* background-color: white; */
            opacity: 0.5;
            cursor: pointer;
        }
        .ootdr:hover
        {
            /* background-color: white; */
            opacity: 0.5;
            cursor: pointer;
        }
        .sns
        {
            /* border: 1px solid purple; */
            display: flex;
            width: 500px;
            justify-content: space-between;
            margin-top: 300px;
            margin-left: 0;
        }
        .snsbox
        {
            /* border: solid 1px greenyellow; */
            width: 1280px;
        }
        .Introduction
        {
            margin-top: 30px;
            /* border: solid 1px orangered; */
            font-family: "Noto Sans KR", sans-serif;
            font-optical-sizing: auto;
            font-weight: 500;
            font-style: normal;
            font-size: 13px;
            letter-spacing: -1px;
            display: flex;
            margin-left: 0;
            justify-content: space-between;
            width: 550px;
        }
        .Introductionbox
        {
            width: 1280px;
            /* border: solid 1px blue; */
        }
    .a
    {
        margin-left: 0;
    }
    .b
    {
        margin-right: 0;
    }
    .urban
    {
        /* border: 1px solid black; */
        width: 1280px;
        margin-top: 30px;
        display: flex;
        position: relative;
        height: 90px;
    }
    .urbanq
    {
        font-family: "Noto Sans KR", sans-serif;
            font-optical-sizing: auto;
            font-weight: 600;
            font-style: normal;
            font-size: 13px;
            letter-spacing: -0.5px;        
    }
    .urbanw
    {
            font-family: "Noto Sans KR", sans-serif;
            font-optical-sizing: auto;
            font-weight: 700;
            font-style: normal;
            font-size: 13px;
            letter-spacing: -0.5px;
            color: red;
            border: solid 1px red;
            width: 220px;
            margin: 0;
            margin-top: 15px;
    }
    .urbanurban
    {
        /* border: solid 1px aqua; */
        width: 300px;
        margin-left: 0;
    }
    .urbane
    {
        /* border: solid 1px greenyellow; */
        margin-left: 300px;
        position: absolute;
    }
    .urbana
    {
        font-family: "Noto Sans KR", sans-serif;
        font-optical-sizing: auto;
        font-weight: 700;
        font-style: normal;
        font-size: 13px;
        letter-spacing: -0.5px;
    }
    .urbans
    {
        font-family: "Noto Sans KR", sans-serif;
        font-optical-sizing: auto;
        font-weight: 500;
        font-style: normal;
        font-size: 13px;
        letter-spacing: -0.5px;
        margin-top: 2px;
    }
    .urband
    {
        font-family: "Noto Sans KR", sans-serif;
            font-optical-sizing: auto;
            font-weight: 700;
            font-style: normal;
            font-size: 13px;
            letter-spacing: -0.5px;
            background-color: black;
            color: white;
            width: 100px;
            margin-left: 0;
            margin-top: 10px;
    }
    .footer
    {
        width: 1280px;
        /* border: solid 1px pink; */
        font-family: "Noto Sans KR", sans-serif;
            font-optical-sizing: auto;
            font-weight: 400;
            font-style: normal;
            font-size: 13px;
            letter-spacing: -0.5px;
            word-spacing: 1.5px;
            margin-top: 30px;
    }
    .wk
    {
        font-family: "Noto Sans KR", sans-serif;
            font-optical-sizing: auto;
            font-weight: 800;
            font-style: normal;
            font-size: 13px;
    }
    .tls
    {
        font-family: "Noto Sans KR", sans-serif;
            font-optical-sizing: auto;
            font-weight: 800;
            font-style: normal;
            font-size: 13px;        
    }


        



    </style>
    
</head>
<body>
    
    <header>
        <div>
            <div class="logo">
                <a href="#"><img src="/web design png/main page/logo.png" alt="">
                </a>   
            </div>
        </div>
        <div class="menubar">
        <div id="menupng">
            <a href="#">
                <img src="/web design png/main page/menu.png" alt="">
            </a>
            
                <div id="menutext">
                    MENU
                </div>
            </div>
            <ul id="m-menu">
                <a href="#"><li class="li">로그인</li></a> 
                <a href="#"><li class="li">마이페이지</li></a>
                <a href="#"><li class="li">최근 본 상품</li></a> 
                <a href="#"><li class="li">좋아요</li></a> 
                <a href="#"><li class="li">장바구니</li></a> 
                <a href="#"><li class="li">배송조회</li></a>
                <a href="#"><li class="li">고객센터</li></a> 
            </ul>
        </div>
    </header>
    
    <div id="happyday">
        <a href="#"><img src="/web design png/main page/happyday.png" alt=""></a>        
    </div>

    <div id="rankingtext">
        <p><span class="king">RANKING</span> </p>
    </div>
    
    <div class="items">
            <div class="item">
                <div class="ritem">
                    <img class="imgbox" src="/web design png/main page/best/1.png" alt="">
                </div>
                <div class="rname">
                        <a href="#">URBAN MODERN HOODIE</a>
                </div>
                <div class="rprice">
                8,8000WON
                </div>
                <div class="rank">
                    1위
                </div>
                </div>
            <div class="item">
                <div class="ritem">
                    <img class="imgbox" src="/web design png/main page/best/2.png" alt="">
                </div>
                <div class="rname">
                        <a href="#">STYLISH STREET HOODIE</a>
                </div>
                <div class="rprice">
                9,2000WON
                </div>
                <div class="rank">
                    2위
                </div>
            </div>
            <div class="item">
                <div class="ritem">
                    <img class="imgbox" src="/web design png/main page/best/3.png" alt="">
                </div>
                <div class="rname">
                        <a href="#">LUFT DENIM 33</a>
                </div>
                <div class="rprice">
                133,000WON
                </div>
                <div class="rank">
                    3위
                </div>
            </div>
            <div class="item">
                <div class="ritem">
                    <img class="imgbox" src="/web design png/main page/best/4-3.png" alt="">
                </div>
                <div class="rname">
                        <a href="#">FRAME WINDBREAKER</a>
                </div>
                <div class="rprice">
                129,000WON
                </div>
                <div class="rank">
                    4위
                </div>
            </div>
    </div>
    
    <div class="items">
        <div class="item">
            <div class="ritem">
                <img class="imgbox" src="/web design png/main page/best/5.png" alt="">
            </div>
            <div class="rname">
                <a href="#">URBAN EDGE BEANIE</a> 
            </div>
            <div class="rprice">
            74,000WON
            </div>
            <div class="rank">
                5위
            </div>
        </div>
        <div class="item">
            <div class="ritem">
                <img class="imgbox" src="/web design png/main page/best/6.png" alt="">
            </div>
            <div class="rname">
                <a href="#">EXPLORER WINDBREAKER</a> 
            </div>
            <div class="rprice">
            129,000WON
            </div>
            <div class="rank">
                6위
            </div>
        </div>
        <div class="item">
            <div class="ritem">
                <img class="imgbox" src="/web design png/main page/best/7.png" alt="">
            </div>
            <div class="rname">
                <a href="#">URBAN EDITION BACKPACK</a> 
            </div>
            <div class="rprice">
            184,000WON
            </div>
            <div class="rank">
                7위
            </div>
        </div>
        <div class="item">
            <div class="ritem">
                <img class="imgbox" src="/web design png/main page/best/8-1.png" alt="">
            </div>
            
            <div class="rname">
                <a href="#">UB SWEATSHIRT</a> 
            </div>
            <div class="rprice">
            95,000WON
            </div>
            <div class="rank">
                8위
            </div>
        </div>
    </div>

    <div id="rankingtext">
        <p><span class="king">EVENTS AND NEWS</span> </p>
    </div>

    <div class="events">
        <div class="event">
            <a href="#">
                <img class="rf" src="/web design png/main page/event/rp.png" alt="">
            </a>
            <a href="#">
                <img class="bf" src="/web design png/main page/event/bpp.png" alt="">
            </a>
        </div>
        <div class="event2">
            <a href="#">
                <img class="snap" src="/web design png/main page/event/snap.png" alt="">
            </a>
            <a href="#">
                <img class="popup" src="/web design png/main page/event/popupstore.png" alt="">
            </a>
        </div>
        <div class="event3">
            <a href="#">
                <img class="mg" src="/web design png/main page/event/mg.png" alt="">
            </a>
            <a href="#"><img class="dl" src="/web design png/main page/event/event.png" alt="">
            </a>
        </div>
    </div>
    <div id="rankingtext">
        <p><span class="king">NEW PRODUCT</span> </p>
    </div>
    
    <div class="newbox">
        <div class="item">
            <div class="ritem">
                <img class="imgbox" src="/web design png/main page/new/1.png" alt="">
            </div>
            <div class="rname">
                    <a href="#">URBAN TREND SWEATER </a>
            </div>
            <div class="rprice">
            114,000WON
            </div>
        </div>
        <div class="item">
            <div class="ritem">
                <img class="imgbox" src="/web design png/main page/new/2.png" alt="">
            </div>
            <div class="rname">
                    <a href="#">URBAN RAID DENIM</a>
            </div>
            <div class="rprice">
            174,000WON
            </div>
        </div>
        <div class="item">
            <div class="ritem">
                <img class="imgbox" src="/web design png/main page/new/3.png" alt="">
            </div>
            <div class="rname">
                    <a href="#">TRAIL ANORAK</a>
            </div>
            <div class="rprice">
            94,00WON
            </div>
        </div>
        <div class="item">
            <div class="ritem">
                <img class="imgbox" src="/web design png/main page/new/4.png" alt="">
            </div>
            <div class="rname">
                    <a href="#">FURRY GRIP FLOVES</a>
            </div>
            <div class="rprice">
            44,000WON
            </div>
        </div>
    </div>
    <div class="newbox">
        <div class="item">
            <div class="ritem">
                <img class="imgbox" src="/web design png/main page/new/5.png" alt="">
            </div>
            <div class="rname">
                    <a href="#">TRAVELER VEST</a>
            </div>
            <div class="rprice">
            160,00WON
            </div>
        </div>
        <div class="item">
            <div class="ritem">
                <img class="imgbox" src="/web design png/main page/new/6.png" alt="">
            </div>
            <div class="rname">
                    <a href="#">PLAYER DUFF BACKPACK</a>
            </div>
            <div class="rprice">
            78,000WON
        </div>
        </div>
        <div class="item">
            <div class="ritem">
                <img class="imgbox" src="/web design png/main page/new/7.png" alt="">
            </div>
            <div class="rname">
                    <a href="#">URBAN PROTECTOR PADDING</a>
            </div>
            <div class="rprice">
            614,000WON
            </div>
        </div>
        <div class="item">
            <div class="ritem">
                <img class="imgbox" src="/web design png/main page/new/8.png" alt="">
            </div>
            <div class="rname">
                    <a href="#">CITY CLASSIC SWEATER</a>
            </div>
            <div class="rprice">
            130,000WON
            </div>
        </div>
    </div>

    <div id="rankingtext">
        <p><span class="king">OOTD</span> </p>
    </div>

    <div class="ootd">
        <div class="ootdq">
                <img src="/web design png/main page/OOTD/1.png" alt="">
        </div>        
        <div class="ootde">
                <img src="/web design png/main page/OOTD/3.png" alt="">
        </div>
        <div class="ootdw">
            <img src="/web design png/main page/OOTD/2.png" alt="">
        </div>

        <div class="ootdr">
            <img src="/web design png/main page/OOTD/4.png" alt="">
        </div>
    </div>
    <div class="snsbox">
    
        <div class="sns">
        <a href="#">
            <img src="/web design png/main page/instargram.png" alt="">
        </a>
        <a href="#">
            <img src="/web design png/main page/ticktok.png" alt="">
        </a>
        <a href="#">
            <img src="/web design png/main page/youtube.png" alt="">
        </a>
        <a href="#">
            <img src="/web design png/main page/twiter.png" alt="">
        </a>
        <a href="#">
            <img src="/web design png/main page/appstore.png" alt="">
        </a>
    </div>

    
    </div>
    
    <div class="Introductionbox">
        <div class="Introduction">
            <span class="a"><a href="#">회사소개</a></span>
            <a href="#">공지사항</a>
            <a href="#">이벤트공지</a>
            <a href="#">입정/제휴/대량구매</a>
            <a href="#">개인정보처리방침</a>
            <a href="#">이용약관</a>
            <span class="b"><a href="#">로고 다운로드</a></span>
        </div>
    </div>

    <div class="urban">
        <div class="urbanurban">       
            <div class="urbanq">
                어반그레이스 <br>
                (34185) 대전 유성구 대학로 60 망치빌딩
            </div>
            <div class="urbanw">
                교환/환불 시 위 주소로 반품 하셔야 합니다.
            </div>
        </div>
        <div class="urbane">
            <div class="urbana">
                고객센터
            </div>
            <div class="urbans">
                1234-5678 (유료)&nbsp;&nbsp;&nbsp; 
                <a href="#">1대1문의</a> <br>
                평일오전 09시 - 18시
            </div>
            <div class="urband">
                <a href="#">
                    FAQ 자주 묻는 질문
                </a>
            </div>
        </div>
    </div>

    <div class="footer">
        어반그레이스 내 매거진, 스트리트스냅, 스토어 등 어반그레이스 자체 생성 콘텐츠는 어반그레이스닷컴 및 어반그레이스 계약업체에 저작권이 있습니다. <br> 

이러한 콘텐츠는 출처를 밝히고(어반그레이스닷컴 표기 및 www.urbanGrace.com 링크 포함 필수) 비상업적인 용도에서만 활용하실 수 있습니다. <a href="#" class="wk">자세히보기</a> <br> 

커뮤니티 및 중고장터, 댓글 등 어반그레이스 회원이 올린 이미지가 저작권에 위배될 경우 <a href="#" class="tls">신고</a> 하시면 검토 후 삭제 하겠습니다.
    </div>



        


    
</body>
</html>

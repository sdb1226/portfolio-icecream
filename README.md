<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>래스킨바빈스</title>
    <!-- 파비콘 -->
    <link rel="shortcut icon" href="../img/icon_baskicon.png">

    <!-- FontAwesome5, 구글 폰트(폰트, 아이콘) -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.10.2/css/all.min.css" />
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Jua&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Nanum+Gothic+Coding:wght@700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Nanum+Gothic+Coding:wght@400;700&display=swap"
        rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Gothic+A1&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Gothic+A1:wght@100&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Gothic+A1:wght@300&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Gothic+A1:wght@500&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Paytone+One&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Poor+Story&display=swap" rel="stylesheet">

<link href="https://fonts.googleapis.com/css2?family=Black+Han+Sans&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Cute+Font&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Do+Hyeon&display=swap" rel="stylesheet">

    <!-- Jquary, Swiper -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.css">
    <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css">
    <script src="https://unpkg.com/swiper/swiper-bundle.js"></script>
    <script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>

    <style>
        @font-face {
            src: url(../font/배스킨라빈스\ B.ttf);
            font-family: 'brb';
        }

        @font-face {
            src: url(../font/배스킨라빈스\ R.ttf);
            font-family: 'brr';
        }

        @font-face {
            src: url(../font/NanumGothic.ttf);
            font-family: 'nanumgo';
        }

        @font-face {
            src: url(../font/NanumSquareRoundR.ttf);
            font-family: 'NanumSquareRoundr';
        }

        @font-face {
            src: url(../font/NanumSquareRoundB.ttf);
            font-family: 'NanumSquareRoundb';
        }

        @font-face {
            src: url(../font/NanumSquareRoundEB.ttf);
            font-family: 'NanumSquareRoundeb';
        }

        @font-face {
            src: url(../font/NanumSquareRoundL.ttf);
            font-family: 'NanumSquareRoundl';
        }

        @font-face {
            src: url(../font/Maplestory\ Bold.ttf);
            font-family: 'maple_b';
        }

        @font-face {
            src: url(../font/Maplestory\ Light.ttf);
            font-family: 'maple_l';
        }



        /* font-family: 'Gothic A1', sans-serif; */
        /* font-family: 'Black Han Sans', sans-serif; */
        /* font-family: 'Cute Font', cursive; */
        /* font-family: 'Do Hyeon', sans-serif; */

        @media only screen and (max-width: 640px) {
            .wrap {
                width: 100%;
                background-color: aqua;
            }
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
        }

        li {
            list-style: none;
        }

        a {
            text-decoration: none;
        }

        body {
            background: #fff6e6;
        }

        .wrap {
            position: relative;
            overflow: hidden;
            background: #f7f7f7;
            min-width: 1100px;
        }

        /* 헤더 구간 시작 */

        .header {
            border-top: 3px solid #DF3E9C;
            background-color: #ffffff;
        }

        .logoandlogincontainer {
            margin: 0 74px;
            height: 100px;
            /* background-color: rgb(150, 150, 150); */
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .logincontainer {
            margin-right: 50px;
            /* background-color: darkturquoise; */
        }

        .logincontain {
            margin: 0 12px;
            float: left;
        }

        .logincontain>a {
            font-size: 15px;
            font-family: 'NanumSquareRoundr';
            color: #381F12;
        }

        .logincontain:nth-child(4)>a>i {
            color: #DF3E9C;
            /* color: #1f4c9a; */
        }

        .nav {
            position: relative;
            z-index: 100;
            background-color: #DF3E9C;
        }

        .nav_mainmenu_container {
            margin: 0 auto;
            width: 1056px;
            /* margin: 0 152px; */
            /* background-color: darkslategray; */
            display: flex;
            justify-content: space-around;
        }

        .nav_mainmenu {
            height: 48px;
            line-height: 48px;
            font-family: 'NanumSquareRoundeb';
            font-weight: bold;
            font-size: 20px;
            color: #fff;
            text-align: center;
            cursor: pointer;
        }

        .backboard {
            position: absolute;
            left: 0;
            top: 48px;
            width: 100%;
            height: 0;
            background-color: #ffffff;
            transition: all 0.5s;
            box-shadow: 0 10px 20px #381F1266;
            border-bottom: 1px solid #381F12;
        }

        .nav_mainmenu_container:hover .backboard {
            height: 210px;
        }

        .backboard_container {
            margin: 0 auto;
            width: 1056px;
            /* margin: 0 152px; */
            /* background-color: aqua; */
            height: 100%;
            overflow: hidden;
            display: flex;
            justify-content: space-around;
            text-align: center;
        }

        .backboard_submenu {
            /* background-color: rgb(204, 204, 83); */
            font-family: 'NanumSquareRoundl';
            font-size: 14px;
            text-align: center;
        }

        .backboard_submenu_box {
            height: 28px;
            line-height: 28px;
        }

        .backboard_submenu_container:nth-child(2),
        .backboard_submenu_container:nth-child(3),
        .backboard_submenu_container:nth-child(4),
        .backboard_submenu_container:nth-child(5) {
            margin-top: 19px;
        }

        .nav_mainmenu:nth-child(1),
        .backboard_submenu_container:nth-child(1) {
            width: 256px;
        }

        .nav_mainmenu:nth-child(2),
        .backboard_submenu_container:nth-child(2) {
            width: 130px;
        }

        .nav_mainmenu:nth-child(3),
        .nav_mainmenu:nth-child(5),
        .backboard_submenu_container:nth-child(3),
        .backboard_submenu_container:nth-child(5) {
            width: 127px;
        }

        .nav_mainmenu:nth-child(4),
        .backboard_submenu_container:nth-child(4) {
            width: 80px;
        }

        .backboard_submenu_icepic {
            cursor: pointer;
        }

        .backboard_submenu>a {
            color: #381F12;
            font-weight: normal;
        }

        .backboard_submenu>a:hover {
            color: #DF3E9C;
            border-bottom: 1px solid #DF3E9C;
        }

        /* 헤더 구간 종료, 메인 구간 시작 */

        .main {
            background-color: #ffffff;
        }

        /* 메인 1: 이달의 맛 구간 시작 */

        .main_at1 {
            background-image: linear-gradient(145deg, #efedee 30%, #ffec00 80%);
        }

        .main_fotm_container {
            margin: 0 auto;
            width: 1080px;
            position: relative;
            height: 720px;
            /* background-image: linear-gradient(135deg, #ea5e9e 10%, #fabb00 50%, #10a956 100%); */
            /* */
            display: flex;
            align-items: center;
            justify-content: center;
            /* */
        }

        @keyframes fotmupdown {
            from {
                /* top: 5px; */
                transform: translateY(5px);
            }

            to {
                /* bottom: 5px; */
                transform: translateY(-5px);
                
                
            }
        }

        .fotm {
            /* float: left;
            margin-left: 40px; */
            
            width: 420px;
            /* height: 720px; */
            height: 680px;
            /* background-color: yellowgreen; */
            background-image: url(http://www.baskinrobbins.co.kr/assets/images/flavoer/ice_img.png?ver=210701);
            background-repeat: no-repeat;
            background-position: center center;
            background-size: 100% auto;
            /* */
            position: absolute;
            left: 60px;
            /* */
        }

        .fotm::after {
            content: '';
            position: relative;
            
        }

        .fotm img {
            width: 508px;
            height: 167px;
            /* background-color: blanchedalmond; */
            position: absolute;
            left: -34px;
            top: 30%;
        }

        /* .fotm .straw {
            position: absolute;
            right: 10px;
            top: 70px;
            width: 120px;
            height: 120px;
            background-color: rgb(216, 53, 47);
            z-index: 500;
        }

        .fotm .vanillaice {
            position: absolute;
            right: 10px;
            top: 220px;
            width: 120px;
            height: 120px;
            background-color: rgb(244, 255, 196);
            z-index: 500;
        }

        .fotm .melon {
            position: absolute;
            left: 10px;
            bottom: 220px;
            width: 120px;
            height: 120px;
            background-color: rgb(112, 240, 133);
            z-index: 500;
        }

        .fotm .yellowsome {
            position: absolute;
            right: 10px;
            bottom: 70px;
            width: 120px;
            height: 120px;
            background-color: rgb(221, 210, 54);
            z-index: 500;
        } */

        




        .fotm_anima {
            animation: fotmupdown 1.5s ease infinite;
            animation-timing-function: linear;
            /* animation-delay: 2s; */
            animation-direction: alternate;
            animation-play-state: running;
        }





        .fotm_info {
            /* float: right; */
            /* */
            position: absolute;
            right: 15px;
            /* */
            width: 610px;
            height: 720px;
            /* background-color: #e4c6d7; */
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: space-around;
            letter-spacing: -0.05em;
            cursor: default;
        }

        .fotm_info>p {
            margin-top: 140px;
            /* font-family: 'NanumSquareRoundr'; */
            font-family: 'Do Hyeon', sans-serif;
            font-size: 36px;
            color: #dabb49;
        }

        .fotm_info>p>b {
            /* font-family: 'NanumSquareRoundeb'; */
            font-family: 'Do Hyeon', sans-serif;
        }

        .fotm_info>b:nth-child(2) {
            font-family: 'Black Han Sans', sans-serif;
            font-size: 70px;
            color: #f5a300;
            font-weight: 450;
        }

        .fotm_info>span {
            font-family: 'NanumSquareRoundr';
            font-size: 18px;
            font-weight: 300;
            color: #fff;
            letter-spacing: -0.05em;
            
        }

        .fotm_info>input {
            margin: 0 auto;
            width: 168px;
            height: 41px;
            background-color: #e7423e;
            color: #fff;
            border: none;
            font-family: 'NanumSquareRoundb';
            font-size: 16px;
            border-radius: 20px;
            transition: all 0.6s;
            cursor: pointer;
        }

        .fotm_info>input:hover {
            /* box-shadow: 0 10px 20px #ffffffe0; */

            -moz-box-shadow: 0 0 20px 3px #ffffffe0;
            -webkit-box-shadow: 0 0 20px 5px #ffffffe0;
            box-shadow: 0 0 20px 5px #ffffffe0;
            /* color: #381F12;
            background-color: #68615e; */
        }

        input:focus {
            outline: none;
        }

        .photo_container {
            margin-bottom: 120px;
            height: 140px;
            /* background-color: rgb(228, 202, 99); */
            display: flex;
            align-items: center;
            justify-content: space-evenly;
        }

        .photo {
            width: 138px;
            height: 138px;
            border: 1px solid #381F1280;
            border-radius: 100%;
            background-color: #ffffff;
            position: relative;
            overflow: hidden;
        }

        .index_photo_container>.photo:nth-child(1) {
            background-position: top 12px center;
            background-size: 90%;
            background-repeat: no-repeat;
            background-image: url(http://www.baskinrobbins.co.kr/assets/images/flavoer/ice_img.png?ver=210701);
        }

        .index_photo_container>.photo:nth-child(2) {
            background-position: center center;
            background-size: 115%;
            background-repeat: no-repeat;
            background-image: url(http://www.baskinrobbins.co.kr/upload/product/1680660542.png);
        }

        .index_photo_container>.photo:nth-child(3) {
            background-position: center center;
            background-size: 115%;
            background-repeat: no-repeat;
            background-image: url(http://www.baskinrobbins.co.kr/upload/product/1609896003.png);
        }

        .index_photo_container>.photo:nth-child(4) {
            background-position: center center;
            background-size: 115%;
            background-repeat: no-repeat;
            background-image: url(http://www.baskinrobbins.co.kr/upload/product/1688518948.png);
        }

        .photo>div {
            position: absolute;
            z-index: 0;
            left: 138px;
            width: 138px;
            height: 138px;
            background-color: #805500c9;
            transition: all 0.4s;
            border-radius: 100%;
            background-position: center center;
            background-repeat: no-repeat;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Black Han Sans', sans-serif;
            color: #f5a300;
            font-size: 30px;
            font-weight: 200;
        }

        .photo:nth-child(1)>div {
            background-image: url(../img/fotm_txt01.png);
            background-size: 37.5%;
        }

        .photo:nth-child(2)>div {
            background-image: url(../img/fotm_txt02.png);
            background-size: 50%;
        }

        .photo:nth-child(3)>div {
            background-image: url(../img/fotm_txt03.png);
            background-size: 37.5%;
        }

        .photo:nth-child(4)>div {
            background-image: url(../img/fotm_txt04.png);
            background-size: 50%;
        }

        .photo:hover>div {
            left: -1px;
        }

        .photo>div>span {
            cursor: default;
            line-height: 46px;
            color: rgb(77, 74, 66);
        }

        /* 메인 1: 이달의 맛 구간 종료, 메인 2: 메뉴 구간 시작,*/

        .main_at2 {
            position: relative;
            /* background-color: rgb(112, 112, 31); */
        }

        .main_menu {
            margin: 0 auto;
            /* background-color: #FF486D; */
            width: 1080px;
            overflow: hidden;
        }

        .main_menu_title,
        .main_event_title,
        .main_sns_title {
            height: 150px;
            /* background-color: blue; */
            display: flex;
            flex-direction: column;
            justify-content: center;
            text-align: center;
            cursor: default;
        }

        .main_store_title,
        .main_order_title {
            width: 420px;
            height: 240px;
            /* border: 1px solid rgb(154, 154, 255); */
            display: flex;
            flex-direction: column;
            justify-content: space-evenly;
            text-align: center;
            cursor: default;
        }



        .main_menu_title>h2,
        .main_event_title>h2,
        .main_store_title>h2,
        .main_order_title>h2,
        .main_sns_title>h2 {
            font-size: 42px;
            font-family: 'Paytone One', sans-serif;
        }

        .main_menu_title>p,
        .main_event_title>p,
        .main_store_title>p,
        .main_order_title>p,
        .main_sns_title>p {
            font-size: 19px;
            font-family: 'Gothic A1', sans-serif;
        }

        .main_menu_title>p:nth-child(3),
        .main_event_title>p:nth-child(3),
        .main_store_title>p:nth-child(3),
        .main_order_title>p:nth-child(3),
        .main_sns_title>p:nth-child(3) {
            font-size: 14px;
            font-family: 'Gothic A1', sans-serif;
        }

        .main_store_title>button,
        .main_order_title>button {
            margin: 0 auto;
            border-radius: 45px;
            width: 155px;
            height: 43px;
            border: 2px solid #fff;
            outline: none;
            background-color: #1f4c9a;
        }

        .main_menu_circle_container {
            height: 370px;
            /* background-color: #ffd9d9; */
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .circle_group {
            margin: 0 7px;
            /* background-color: blueviolet; */
            text-align: center;
            height: 320px;
            display: flex;
            flex-direction: column;
            justify-content: space-evenly;
        }

        .circle {
            width: 176px;
            height: 176px;
            /* background-color: #faf9eb; */
            background-color: #fff67c;
            border-radius: 100%;
            transition: all 0.5s;
        }

        .circle_group:nth-child(1) .circle {
            background-position: center center;
            background-size: 68%;
            background-repeat: no-repeat;
            background-image: url(http://www.baskinrobbins.co.kr/assets/images/flavoer/ice_img.png?ver=210701);
        }

        .circle_group:nth-child(2) .circle {
            background-position: center center;
            background-size: 100%;
            background-repeat: no-repeat;
            background-image: url(http://www.baskinrobbins.co.kr/upload/product/1680660542.png);
        }

        .circle_group:nth-child(3) .circle {
            background-position: center center;
            background-size: 100%;
            background-repeat: no-repeat;
            background-image: url(http://www.baskinrobbins.co.kr/upload/product/1609896003.png);
        }

        .circle_group:nth-child(4) .circle {
            background-position: center center;
            background-size: 100%;
            background-repeat: no-repeat;
            background-image: url(https://www.baskinrobbins.co.kr/upload/product/1619857592.png);
        }

        .circle_group:nth-child(5) .circle {
            background-position: center center;
            background-size: 100%;
            background-repeat: no-repeat;
            background-image: url(http://www.baskinrobbins.co.kr/upload/product/1688518948.png);
        }

        .circle_group>b {
            font-family: 'Quicksand';
            font-size: 18px;
            font-weight: bold;
            cursor: default;
        }

        .circle_group>p {
            font-size: 15px;
            font-family: 'NanumSquareRoundl';
            cursor: default;
        }

        .circle_group>a {
            font-family: 'Quicksand';
            font-size: 13px;
            color: #6A6A6A;
        }

        /* 메인 2: 메뉴 구간 종료, 메인 3: 이벤트 구간 시작 */

        .main_at3 {
            background-color: #ffffff;
        }

        .main_event {
            margin: 0 auto;
            /* background-color: #bd6879; */
            /* width: 1080px; */
            width: 960px;
            height: 500px;
            overflow: hidden;
        }


        .main_event_container {
            height: 370px;
            /* background-color: #d15794; */
            display: flex;
            align-items: center;
            justify-content: center;
        }



        /* 슬라이드 기본 */
        .swiper-container {
            width: 100%;
            height: 100%;
        }

        .swiper-slide {
            text-align: center;
            font-size: 18px;
            /* Center slide text vertically */
            display: -webkit-box;
            display: -ms-flexbox;
            display: -webkit-flex;
            display: flex;
            -webkit-box-pack: center;
            -ms-flex-pack: center;
            -webkit-justify-content: center;
            justify-content: center;
            -webkit-box-align: center;
            -ms-flex-align: center;
            -webkit-align-items: center;
            align-items: center;
        }




        .main_event_container {

            /* width: 1080px; */
            width: 960px;
            height: 320px;
            /* background-color: fuchsia; */
        }

        .swiper-event-slide {
            height: 320px;
            display: flex;
            flex-direction: column;
            justify-content: space-evenly;
            /* background-color: wheat; */
        }

        .swiper-event-slide>div {
            width: fit-content;
            height: fit-content;
            /* background-color: wheat; */
        }

        .swiper-event-slide>div>img {
            cursor: pointer;
            width: 213px;
            height: 213px;
            border-radius: 20px;
        }

        .swiper-event-slide>div>p {
            cursor: default;
        }

        .swiper-event-slide>div>.p_event_due {
            font-size: 12px;
        }

        .swiper-event-slide>div>.p_event_info {
            font-size: 18px;
        }


        .main_event_container .swiper-button-next::after,
        .main_event_container .swiper-button-prev::after {
            display: none;
        }

        .swiper-button-next>i,
        .swiper-button-prev>i {
            font-size: 2em;
            color: #d66fa9;
        }
















        .main_at4 {
            /* background-color: rgb(71, 117, 60); */
            background-color: none;
        }

        .main_store {
            margin: 0 auto;
            /* background-color: #a5374d; */
            width: 1080px;
            height: 380px;
            overflow: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .main_store_inner_l,
        .main_order_inner_l {
            width: 450px;
            height: 300px;
            background-color: #10a956;
            display: flex;
            flex-direction: column;
            text-align: center;
            align-items: center;
            justify-content: space-around;
        }

        .main_store_inner_r,
        .main_order_inner_r {
            width: 450px;
            height: 300px;
            background-color: #b8c6ed;
            background-image: linear-gradient(125deg, #efedee 40%, #ffec00 80%);
            display: flex;
            flex-direction: column;
            text-align: center;
            align-items: center;
            justify-content: space-around;
        }







        .main_at5 {
            /* background-color: rgb(94, 191, 255); */
            background-color: none;
        }

        .main_order {
            margin: 0 auto;
            /* background-color: #ccb876; */
            width: 1080px;
            height: 370px;
            overflow: hidden;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .main_at6 {
            background-color: rgb(99, 99, 43);
        }

        .main_sns {
            margin: 0 auto;
            background-color: #b46f7d;
            width: 1080px;
            height: 500px;
            overflow: hidden;
        }

        .footer {
            background-color: rgb(255, 255, 255);
        }

        .ft_hd {
            background-color: #545454;
        }

        .ft_hd_container {
            margin: 0 auto;
            width: 1032px;
            height: 70px;
            /* background-color: lightpink; */
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .ft_hd_container>li {
            color: #ffffff;
            font-size: 15px;
            cursor: pointer;
        }

        .ft_md_container>li>select {
            width: 172px;
            height: 37px;
            border: 1px solid #AAAAAA;
            text-indent: 5px;
        }

        .ft_md {
            height: 65px;
            background-color: #ffffff;
        }

        .ft_md_container {
            margin: 0 auto;
            width: 1200px;
            /* background-color: cyan; */
            height: 65px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .ft_md_container>li:not(.ft_md_container > li:nth-child(1), .ft_md_container > li:nth-child(7)) {
            margin-left: -370px;
        }

        .ft_bd {
            background-color: #ffffff;
        }

        .ft_bd_container {
            margin: 0 auto;
            width: 1200px;
            height: 200px;
            /* background-color: darkcyan; */
            display: flex;
            flex-direction: column;
            justify-content: space-evenly;
        }

        .ft_bd_container>a {
            margin-top: 5px;
            width: 239px;
            /* background-color: darkgrey; */
        }

        .ft_bd_container>span {
            font-size: 13px;
            color: #999999;
        }
    </style>
</head>

<body>
    <div class="wrap">
        <div class="header">
            <div class="logoandlogincontainer">
                <a href="#">
                    <img src="https://logos-download.com/wp-content/uploads/2016/04/Baskin-Robbins-logo_2.png"
                        width="329px" height="auto" alt="홈">
                </a>
                <ul class="logincontainer">
                    <li class="logincontain"><a href="">로그인&#183;회원가입</a></li>
                    <li class="logincontain"><a href="../PORTFOLIO_GALLERY_main.html">고객센터</a></li>
                    <li class="logincontain"><a href="">CONTACT US</a></li>
                    <li class="logincontain"><a href=""><i class="fas fa-search"></i></a></li>
                </ul>
                <!--logincontainer end-->
            </div>
            <!--logoandlogincontainer end-->
            <div class="nav">
                <ul class="nav_mainmenu_container">
                    <li class="nav_mainmenu">FLAVOR OF THE MONTH</li>
                    <li class="nav_mainmenu">MENU</li>
                    <li class="nav_mainmenu">EVENT</li>
                    <li class="nav_mainmenu">STORE</li>
                    <li class="nav_mainmenu">ABOUT</li>
                    <li class="backboard">
                        <div class="backboard_container">
                            <ul class="backboard_submenu_container">
                                <li class="backboard_submenu backboard_submenu_icepic" onclick="location.href='#'">
                                    <img src="http://www.baskinrobbins.co.kr/assets/images/common/flavor/img_monthly_fom.png?v=210701"
                                        height="210px;" alt="">
                                </li>
                            </ul>

                            <ul class="backboard_submenu_container">
                                <li class="backboard_submenu backboard_submenu_box">
                                    <a href="">아이스크림</a>
                                </li>
                                <li class="backboard_submenu backboard_submenu_box">
                                    <a href="">아이스크림 케이크</a>
                                </li>
                                <li class="backboard_submenu backboard_submenu_box">
                                    <a href="">커피</a>
                                </li>
                                <li class="backboard_submenu backboard_submenu_box">
                                    <a href="">음료</a>
                                </li>
                                <li class="backboard_submenu backboard_submenu_box">
                                    <a href="">디저트</a>
                                </li>
                            </ul>

                            <ul class="backboard_submenu_container">
                                <li class="backboard_submenu backboard_submenu_box"><a href="">진행 중인 이벤트</a></li>
                                <li class="backboard_submenu backboard_submenu_box"><a href="">당첨자 발표</a></li>
                            </ul>

                            <ul class="backboard_submenu_container">
                                <li class="backboard_submenu backboard_submenu_box"><a href="">매장찾기</a></li>
                                <li class="backboard_submenu backboard_submenu_box"><a href="">고객센터</a></li>
                            </ul>

                            <ul class="backboard_submenu_container">
                                <li class="backboard_submenu backboard_submenu_box"><a href="">공지사항</a></li>
                                <li class="backboard_submenu backboard_submenu_box"><a href="">보도자료</a></li>
                                <li class="backboard_submenu backboard_submenu_box"><a href="">채용정보</a></li>
                                <li class="backboard_submenu backboard_submenu_box"><a href="">점포개설문의</a></li>
                                <li class="backboard_submenu backboard_submenu_box"><a href="">CONTACT US</a></li>
                            </ul>
                        </div>
                    </li>
                </ul>
                <!--nav_mainmenu_container end-->
            </div>
            <!--nav end-->
            <script>
                const nav = document.querySelector('.nav');
                const navTopOffset = nav.offsetTop;
                window.addEventListener('scroll', e => {

                    if (window.pageYOffset >= navTopOffset) {
                        nav.style.position = 'fixed';
                        nav.style.top = 0;
                        nav.style.left = 0;
                        nav.style.right = 0;
                    } else {
                        nav.style.position = '';
                        nav.style.top = '';
                    }
                });
            </script>
            <!-- <script>
                $(window).scroll(function(){
                    $('.nav').css('left', 0-$(this).scrollLeft());
                });
            </script> -->

        </div>
        <!--header end-->
        <div class="main">
            <div class="main_at1">
                <div class="main_fotm_container">
                    <div class="fotm fotm_anima">
                        
                            <img src="http://www.baskinrobbins.co.kr/assets/images/flavoer/ice_material.png?ver=210701" alt="">
                        
                        <!-- <div class="straw">1</div>
                        <div class="vanillaice">2</div>
                        <div class="melon">3</div>
                        <div class="yellowsome">4</div> -->
                    </div>
                    <div class="fotm_info">
                        <p>먼저 만나는 <b>8</b>월<b>&nbsp;이달의 맛</b></p>
                        <b>꿀.바.망</b>
                        <span>허니망고 아이스크림과<br>바나나 아이스크림 속에<br>망고 다이스가 쏙쏙!</span>
                        <input value="이달의 맛 맛보기" type="button" onclick="location.href=''">
                        <div class="photo_container index_photo_container">
                            <div class="photo">
                                <div>
                                    꿀 바 망
                                </div>
                            </div>
                            <div class="photo">
                                <div>
                                    
                                </div>
                            </div>
                            <div class="photo">
                                <div>
                                   
                                </div>
                            </div>
                            <div class="photo">
                                <div>
                                    꿀 바 망
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <!--main_wallpaper end-->
            </div>
            <!--main_cont end-->
            <div class="main_at2">
                <div class="main_menu">
                    <div class="main_menu_title">
                        <h2>MENU</h2>
                        <p>배스킨라빈스의 다양한 제품을 만나보세요!</p>
                    </div>
                    <div class="main_menu_circle_container">
                        <div class="circle_group">
                            <div class="circle"></div>
                            <b>ICE CREAM</b>
                            <p>아이스크림의 기준은?<br>배스킨라빈스!</p>
                            <a href="">more&nbsp;&nbsp;&nbsp;<i class="fas fa-long-arrow-alt-right"></i></a>
                        </div>
                        <div class="circle_group">
                            <div class="circle"></div>
                            <b>ICE CREAM CAKE</b>
                            <p>아이 어른 모두 좋아하는<br>아이스크림을 케이크 하나로!</p>
                            <a href="">more&nbsp;&nbsp;&nbsp;<i class="fas fa-long-arrow-alt-right"></i></a>
                        </div>
                        <div class="circle_group">
                            <div class="circle"></div>
                            <b>BEVERAGE</b>
                            <p>아이스크림으로 즐기는<br>배스킨라빈스만의 음료</p>
                            <a href="">more&nbsp;&nbsp;&nbsp;<i class="fas fa-long-arrow-alt-right"></i></a>
                        </div>
                        <div class="circle_group">
                            <div class="circle"></div>
                            <b>COFFEE</b>
                            <p>배스킨라빈스만의<br>부드러운 촉감과 달콤한 풍미!</p>
                            <a href="">more&nbsp;&nbsp;&nbsp;<i class="fas fa-long-arrow-alt-right"></i></a>
                        </div>
                        <div class="circle_group">
                            <div class="circle"></div>
                            <b>DESSERT</b>
                            <p>아이스크림을 더<br>재미있고 간편히 즐기는 방법!</p>
                            <a href="">more&nbsp;&nbsp;&nbsp;<i class="fas fa-long-arrow-alt-right"></i></a>
                        </div>
                    </div>
                </div>
            </div>
            <div class="main_at3">
                <div class="main_event">
                    <div class="main_event_title">
                        <h2>EVENT</h2>
                        <p>배스킨라빈스와 함께하는 다양한 혜택과 이벤트</p>
                    </div>
                    <div class="swiper-container main_event_container">
                        <div class="swiper-wrapper">
                            <div class="swiper-slide swiper-event-slide">
                                <div onclick="location.href=''">
                                    <img src="http://www.baskinrobbins.co.kr/upload/event/image/1609897104.jpg" alt="">
                                    <p class="p_event_due">상시진행</p>
                                    <p class="p_event_info">1-32</p>
                                </div>

                            </div>


                            <div class="swiper-slide swiper-event-slide">
                                <div onclick="location.href=''">
                                    <img src="http://www.baskinrobbins.co.kr/upload/event/image/1630631151.jpg" alt="">
                                    <p class="p_event_due">2-32</p>
                                    <p class="p_event_info">1-32</p>
                                </div>

                            </div>


                            <div class="swiper-slide swiper-event-slide">
                                <div onclick="location.href=''">
                                    <img src="http://www.baskinrobbins.co.kr/upload/event/image/1639297260.png" alt="">
                                    <p class="p_event_due">2-32</p>
                                    <p class="p_event_info">1-32</p>
                                </div>

                            </div>


                            <div class="swiper-slide swiper-event-slide">
                                <div onclick="location.href=''">
                                    <img src="http://www.baskinrobbins.co.kr/upload/event/image/1625114283.png" alt="">
                                    <p class="p_event_due">2-32</p>
                                    <p class="p_event_info">1-32</p>
                                </div>
                            </div>


                            <div class="swiper-slide swiper-event-slide">
                                <div onclick="location.href=''">
                                    <img src="http://www.baskinrobbins.co.kr/upload/event/image/1570702843.png" alt="">
                                    <p class="p_event_due">2-32</p>
                                    <p class="p_event_info">1-32</p>
                                </div>

                            </div>



                            <div class="swiper-slide swiper-event-slide">
                                <div onclick="location.href=''">
                                    <img src="http://www.baskinrobbins.co.kr/upload/event/image/1578277305.png" alt="">
                                    <p class="p_event_due">2-32</p>
                                    <p class="p_event_info">1-32</p>
                                </div>

                            </div>


                            <div class="swiper-slide swiper-event-slide">
                                <div onclick="location.href=''">
                                    <img src="http://www.baskinrobbins.co.kr/upload/event/images/banner_delivery.png"
                                        alt="">
                                    <p class="p_event_due">2-32</p>
                                    <p class="p_event_info">1-32</p>
                                </div>

                            </div>

                        </div>
                        <!-- <div class="swiper-pagination"></div> -->
                        <div class="swiper-button-next">
                            <i class="far fa-arrow-alt-circle-right"></i>
                        </div>
                        <div class="swiper-button-prev">
                            <i class="far fa-arrow-alt-circle-left"></i>
                        </div>
                    </div>
                    <script>
                        var swiper = new Swiper('.main_event_container', {
                            slidesPerView: 4,
                            spaceBetween: 0,
                            // slidesPerGroup: 1,


                            pagination: {
                                el: '.swiper-pagination',
                                clickable: true,
                            },
                            navigation: {
                                nextEl: '.swiper-button-next',
                                prevEl: '.swiper-button-prev',
                            },
                        });
                    </script>
                </div>
            </div>
            <div class="main_at4">
                <div class="main_store">
                    <div class="main_store_inner_l">

                    </div>
                    <div class="main_store_inner_r">
                        <div class="main_store_title">
                            <h2>STORE</h2>
                            <p><b>다양한 즐거움과 새로움! 우리동네 배스킨라빈스!</b></p>
                            <p>내 주변 가장 가까운 베스킨라빈스 매장을 찾아보세요!</p>
                            <button id="" class="" onclick="">매장찾기<i class="fas fa-search"></i></button>
                        </div>
                    </div>
                </div>
            </div>
            <div class="main_at5">
                <div class="main_order">
                    <div class="main_order_inner_l">
                        <div class="main_order_title">
                            <h2>HAPPY DELIVERY&<br>ORDER</h2>
                            <p><b>주문에서 결제/배송까지 간편하게!</b></p>
                            <p>배스킨라빈스 모바일 사전주문 & 배달서비스</p>
                            <button id="" class="" onclick="">매장찾기<i class="fas fa-search"></i></button>
                        </div>
                    </div>
                    <div class="main_order_inner_r">

                    </div>
                </div>
            </div>
            <div class="main_at6">
                <div class="main_sns">
                    <div class="main_sns_title">
                        <h2>SNS</h2>
                        <p>배스킨라빈스의 즐거움을 다같이 나누고 싶다면?</p>
                    </div>
                </div>
            </div>
        </div>
        <!--main end-->
        <div class="footer">
            <div class="ft_hd">
                <ul class="ft_hd_container">
                    <li onclick="location.href=''">점포개설문의</li>
                    <li onclick="location.href=''">채용문의</li>
                    <li onclick="location.href=''">윤리신고센터</li>
                    <li onclick="location.href=''">이용약관</li>
                    <li onclick="location.href=''">개인정보처리방침</li>
                    <li onclick="location.href=''">영상정보처리기기운영관리방침</li>
                    <li onclick="location.href=''">거래희망회사사전등록</li>
                </ul>
            </div>
            <div class="ft_md">
                <ul class="ft_md_container">
                    <li><img src="file:///D:/html5,css3,javascript/%ED%8F%AC%ED%86%A0%ED%8F%B4%EB%A6%AC%EC%98%A4%20%EB%B2%A0%EC%8A%A4%ED%82%A8%EB%9D%BC%EB%B9%88%EC%8A%A4(20200218)/img/btn_happypoint.png"
                            alt=""></li>
                    <li><img src="file:///D:/html5,css3,javascript/%ED%8F%AC%ED%86%A0%ED%8F%B4%EB%A6%AC%EC%98%A4%20%EB%B2%A0%EC%8A%A4%ED%82%A8%EB%9D%BC%EB%B9%88%EC%8A%A4(20200218)/img/btn_happymarket.png"
                            alt=""></li>
                    <li><img src="file:///D:/html5,css3,javascript/%ED%8F%AC%ED%86%A0%ED%8F%B4%EB%A6%AC%EC%98%A4%20%EB%B2%A0%EC%8A%A4%ED%82%A8%EB%9D%BC%EB%B9%88%EC%8A%A4(20200218)/img/btn_spc_story.png"
                            alt=""></li>
                    <li><img src="file:///D:/html5,css3,javascript/%ED%8F%AC%ED%86%A0%ED%8F%B4%EB%A6%AC%EC%98%A4%20%EB%B2%A0%EC%8A%A4%ED%82%A8%EB%9D%BC%EB%B9%88%EC%8A%A4(20200218)/img/btn_norton.gif"
                            alt=""></li>
                    <li><img src="file:///D:/html5,css3,javascript/%ED%8F%AC%ED%86%A0%ED%8F%B4%EB%A6%AC%EC%98%A4%20%EB%B2%A0%EC%8A%A4%ED%82%A8%EB%9D%BC%EB%B9%88%EC%8A%A4(20200218)/img/btn_ccm.gif"
                            alt=""></li>
                    <li><img src="file:///D:/html5,css3,javascript/%ED%8F%AC%ED%86%A0%ED%8F%B4%EB%A6%AC%EC%98%A4%20%EB%B2%A0%EC%8A%A4%ED%82%A8%EB%9D%BC%EB%B9%88%EC%8A%A4(20200218)/img/btn_ksa.png"
                            alt=""></li>
                    <li>
                        <select>
                            <optgroup label="Family Site">
                                <option value="">Family Site</option>
                                <option value="">배스킨 스쿨</option>
                                <option value="">SPC그룹사이트</option>
                                <option value="">SPC MAGAZINE</option>
                                <option value="">BR코리아</option>
                                <option value="">해피포인트카드</option>
                                <option value="">파스쿠찌</option>
                                <option value="">삼립</option>
                                <option value="">파리바게트</option>
                                <option value="">던킨도너츠</option>
                            </optgroup>
                        </select>
                    </li>


                </ul>
            </div>
            <div class="ft_bd">
                <div class="ft_bd_container">
                    <a href="">
                        <img src="file:///D:/html5,css3,javascript/%ED%8F%AC%ED%86%A0%ED%8F%B4%EB%A6%AC%EC%98%A4%20%EB%B2%A0%EC%8A%A4%ED%82%A8%EB%9D%BC%EB%B9%88%EC%8A%A4(20200218)/img/baskinlogoblack.png"
                            width="239px" alt="">
                    </a>
                    <span>
                        사업자 등록번호 : 303-81-09535 비알코리아(주) 대표이사 김창대 서울특별시 서초구 남부순환로 2620(양재동 11-149번지)<br>
                        TEL : 080-555-3131 개인정보관리책임자 : 김경우<br>
                        Copyright ⓒ 2016 BRKOREA Company. All Rights Reserved.
                    </span>
                </div>

            </div>
        </div>
        <!--footer end-->
    </div>
    <!--wrap end-->
</body>

</html>
